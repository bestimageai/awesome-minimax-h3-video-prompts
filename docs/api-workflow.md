# MiniMax H3 and GPT Image 2 API workflows

This page separates bestimage.ai's published API from MiniMax's direct API and local H3-Base deployment. A recipe is a creative specification; request fields belong to the selected provider.

See the [official H3 capability examples](https://platform.minimaxi.com/docs/guides/video-prompt) for multimodal creative workflows and the [official video generation guide](https://platform.minimaxi.com/docs/guides/video-generation) for currently documented request modes and fields.

For downloadable use, start with the official [MiniMax-AI/MiniMax-H3 repository](https://github.com/MiniMax-AI/MiniMax-H3), [model card and open weights](https://huggingface.co/MiniMaxAI/MiniMax-H3), and this project's [multilingual deployment guide](./deployment-guide.md). Open-weight checkpoints and hosted product/API features are separate integration surfaces; do not assume identical task coverage, preprocessing, acceleration, limits, or outputs.

## bestimage.ai entry points

| Model or purpose | Page language | Model page |
|---|---|---|
| MiniMax H3 text-to-video; related image/reference modes are linked on the page | English | [MiniMax H3 API](https://bestimage.ai/models/minimax/minimax-h3-text-to-video/) |
| GPT Image 2 for a separate first-frame, product-reference or concept-image step | English | [GPT Image 2 API](https://bestimage.ai/models/openai/gpt-image-2/) |
| Current model documentation and integration details | English | [API documentation](https://bestimage.ai/docs/) |

All eight README editions use these English API landing pages and label the language. A localized README does not imply that its linked API page is translated.

### Published API host

**Use `https://api.flaq.ai` for bestimage.ai API requests.** Authenticate with an API key issued through your bestimage.ai account and keep it outside public files. The examples below use this host for submission and polling.

### Model identifiers and request differences

| Purpose | Published model ID | Key request fields |
|---|---|---|
| Text to video | `minimax-h3-text-to-video` | `prompt`, `duration`, `resolution`, `aspect_ratio` |
| First-frame video, optional end frame | `minimax-h3-image-to-video` | `prompt`, `duration`, `resolution`, `image_url`; optional `image_end_url`; no `aspect_ratio` field |
| Multimodal reference video | `minimax-h3-reference-to-video` | `prompt`, `duration`, `resolution`, `aspect_ratio`; optional `images`, `videos`, `audios` arrays |
| Separate reference-image generation | `gpt-image-2` | `prompt`, `width`, `height`, `resolution`, `quality` |

For the bestimage.ai H3 API, duration is 5–15 seconds, video resolution is `768p` or `2k`, and text/reference aspect ratios are `21:9`, `16:9`, `4:3`, `1:1`, `3:4`, `9:16`. Do not copy MiniMax's direct 4–15-second range into this provider's request validation. Some retained recipe formats are broader creative delivery goals; generate a supported format and arrange any separately needed crop/edit yourself.

Reference-array entries are image, video and audio URLs, with published per-type limits of 9, 3 and 3. Also check the underlying model's combined-input rules. In an explicit reference prompt, `<<<image_1>>>` means `images[0]`, `<<<video_1>>>` means `videos[0]`, and `<<<audio_1>>>` means `audios[0]`. A cookbook label such as “Image 1” is not a request parameter. Upload rights-cleared media through your chosen authorized workflow; this repository does not host your private references.

### Example request bodies

Send JSON with `Authorization: Bearer YOUR_API_KEY` and `Content-Type: application/json`. Keep credentials outside the repository.

**H3 text-only motion concept:** `POST https://api.flaq.ai/api/v1/video/task`

```json
{
  "model_name": "minimax-h3-text-to-video",
  "prompt": "A fixed medium shot of one small garden bird perched on a shallow ceramic birdbath. The bird touches its beak to the water once, lifts its head and stays on the rim while small ripples settle. Natural daylight, soft ambient air, no text or additional birds. Fictional generated nature illustration.",
  "duration": 10,
  "resolution": "768p",
  "aspect_ratio": "16:9"
}
```

**GPT Image 2 reference-image step:** `POST https://api.flaq.ai/api/v1/image/task`

```json
{
  "model_name": "gpt-image-2",
  "prompt": "One matte terracotta lunchbox with two empty cream trays and a dark teal lid beside it. Three-quarter overhead studio product photo on a pale tabletop, soft window light, no text, logos or extra parts.",
  "width": 16,
  "height": 9,
  "resolution": "1k",
  "quality": "medium"
}
```

The image request does not call H3. After independently reviewing the result, its authorized accessible image URL can become `image_url` in a separate H3 image-to-video request. The PNGs bundled in this repository were generated with the recorded built-in tool, not by executing this example.

### Submission, polling and failure handling

1. Check the HTTP response and the provider response code; a successful transport alone does not prove that generation was accepted.
2. Store `data.task_id` only after successful submission. Do not automatically repeat a chargeable creation request after an ambiguous timeout; first check whether it was accepted.
3. Poll `GET https://api.flaq.ai/api/v1/video/{taskId}` or `GET https://api.flaq.ai/api/v1/image/{taskId}` with the authorized key. Use a bounded timeout and a reasonable interval; respect rate-limit responses.
4. The published task states are `submitted`, `processing`, `succeed` and `failed`. Stop on failure and retain the diagnostic message; do not loop forever or silently resubmit.
5. On `succeed`, check the returned array before reading `data.task_result.videos[0].url` or `data.task_result.images[0].url`. Inspect the media, not just its URL.
6. Record the provider, exact model, inputs, request settings, output, edits and observed defects. Do not publish credentials, private URLs or sensitive task information.

## Official MiniMax workflow

For direct MiniMax H3 integration, start with the current **V2** documentation, not a copied legacy Hailuo example:

- [H3 video generation V2](https://platform.minimax.io/docs/api-reference/video-generation-v2-create)
- [H3-Context-IR](https://platform.minimax.io/docs/api-reference/video-generation-v2-h3-context-ir)
- [H3-Regenerate-2K](https://platform.minimax.io/docs/api-reference/video-generation-v2-regeneration)

Choose the supported text, first/last-frame or reference workflow, submit according to that endpoint's schema, query its task status and retrieve the documented output. MiniMax's own model identifier, authentication, task fields and media representation must not be replaced with bestimage.ai's `model_name` or polling paths. The general video guide also describes other model generations; it is not a substitute for the current H3 V2 contract.

## Keep prompt content separate from API configuration

Store these as two layers:

```text
Creative specification
- prompt text
- image, video, and audio reference roles
- reference conflict priority
- continuity and safety constraints
- precise edit scope
- delivery intent

Request configuration
- current official model identifier
- supported generation mode
- duration and resolution
- input asset URLs or encoded data
- provider-specific optional fields
```

This separation lets the cookbook remain useful when model identifiers or API fields change.

## Hosted API versus open-weight workflow

| Concern | Hosted MiniMax workflow | Open-weight/local workflow |
|---|---|---|
| Source of truth | Current platform and API docs | Current H3 model card, release files, license and runtime docs |
| Identifier | Exact API model string | Exact checkpoint/task variant and revision |
| Inputs | Only fields accepted by the endpoint | Only modalities supported by the selected checkpoint and pipeline |
| Infrastructure | Provider-managed | User-managed hardware, storage, dependencies and optimization |
| Record | Task ID, file ID, request settings | Checkpoint, revision, runtime, hardware, settings and output hashes |
| Capability claims | What the current endpoint documents | What the downloaded release and tested runtime actually demonstrate |

Use [T12](../templates/README.md#t12-open-weightlocal-generation-record) to make local examples reproducible.

## Suggested generation record

```yaml
recipe_id: BRD-001
recipe_version: 1
generated_at: YYYY-MM-DD
provider: MiniMax
model: <exact model identifier returned/accepted by the API>
mode: text-to-video
duration: <requested value>
resolution: <requested value>
aspect_ratio: <delivery ratio>
input_assets:
  - <file name, URL, or content hash>
prompt: |
  <exact submitted prompt>
result:
  task_id: <optional; remove before public sharing if sensitive>
  file_name: <local artifact name>
review:
  status: pass | needs-revision
  notes:
    - <observed issue or manual edit>
```

Never commit API keys, authorization headers, private input URLs, personal data, or expiring download URLs.

## Version and capability policy

- Copy model identifiers and accepted parameters from the current official documentation;
- Record the exact model used for every tested prompt;
- Label untested prompt recipes as concepts;
- Treat limits, prices, duration, resolution, and available modes as changeable provider data;
- Link H3 capability claims to the official capability page;
- Add H3 request examples only when model identifiers and parameters can be verified against the official integration surface being used.
- Keep hosted and open-weight results clearly labeled; do not attribute one workflow's behavior to the other.

Return to the [main README](../README.md), read the [H3 overview](./minimax-h3-overview.md), or follow the [deployment guide](./deployment-guide.md).
