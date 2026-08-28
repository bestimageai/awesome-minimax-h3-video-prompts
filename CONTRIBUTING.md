# Contributing

Thank you for helping build Awesome MiniMax H3 Video Prompts. The bestimage.ai team maintains this edition. The project accepts reusable, reviewable original work and appropriately licensed adaptations with clear provenance. Read the [source policy](./docs/originality-policy.md) before contributing.

## Good first contributions

- Test an existing original recipe and submit a complete generation record;
- Propose a new recipe in a category with a clear production gap, using the next unused ID;
- Improve a production template or failure-mode checklist;
- Add a verified link to primary MiniMax documentation;
- Fix unclear language, broken links, or inconsistent IDs;
- Submit an original example with a complete generation record.

Use an issue before making a large taxonomy change, adding many media files, or introducing a new language edition.

Use this repository's issue and pull-request templates to submit your contribution.

## Three ways to contribute

1. **Propose:** use the [guided prompt proposal](./.github/ISSUE_TEMPLATE/prompt-proposal.yml) when you have a complete original idea but do not want to edit repository files.
2. **Test:** run an existing recipe, then submit the exact model/tool, inputs, settings, date, edits, defects, and rights-cleared output record.
3. **Build:** open a pull request for a finished recipe, translation, checklist, documentation correction, or original media package.

Concept recipes are welcome; a generated video is not required. Tested status is awarded only when the execution record is complete enough for another contributor to understand what was actually run.

## Prompt requirements

Every prompt recipe must include:

1. A unique ID using the category prefix;
2. A clear English title and one-sentence delivery goal;
3. Generation mode, format, and concept/tested status;
4. A complete copy-ready prompt rather than a keyword list;
5. Start state, primary action, end state, camera, and timing;
6. Continuity locks, constraints, and likely failure modes;
7. Production notes and input assumptions;
8. For tested entries, the exact model/tool, settings, date, and material edits.

Use the canonical format in [prompts/README.md](./prompts/README.md#canonical-recipe-format).

## ID policy

| Prefix | Category |
|---|---|
| `BRD` | Brand and advertising |
| `PRD` | Product and e-commerce |
| `UGC` | UGC and lifestyle |
| `TRV` | Travel and hospitality |
| `FNB` | Food and beverage |
| `FSH` | Fashion and beauty |
| `CIN` | Cinematic storytelling |
| `ANI` | Animation and stylized video |
| `ACT` | Action and sports |
| `VFX` | Fantasy, sci-fi and VFX |
| `DIG` | UI, game and digital experience |
| `SOC` | Transitions, comedy and social formats |
| `MUS` | Music, performance and audio-driven video |
| `EDU` | Education, documentary and science |
| `ARC` | Architecture, interiors and real estate |
| `MOB` | Automotive and mobility |
| `NAT` | Nature, animals and pets |
| `IND` | Industry, business and public service |
| `EDT` | Editing, continuation and localization |
| `MRF` | Multi-reference and camera transfer |
| `CHR` | Character, dialogue and performance |

IDs are assigned sequentially and never reused. Ask a maintainer to confirm the next ID when another pull request could conflict.

## Content we do not accept

- Prompts copied or lightly rewritten without the necessary license, permission and attribution;
- Hidden tracking links, misleading promotion or third-party watermarks presented as our own work; required author and license credits must remain;
- Unauthorized celebrity, private-person, protected-character, brand, voice, or campaign imitation;
- Deceptive testimonials, fake evidence, fraudulent ads, or misleading medical/financial claims;
- Vague keyword piles with no executable motion, camera, time, or continuity specification;
- Media with unclear ownership, consent, or redistribution rights;
- Claims about model capabilities that cannot be verified from a primary source.

Common use cases are not owned by a prompt collection, but wording, story details, reference mappings, characters, brands, shot design, examples, and media can be protected or attributable. Independently author those elements or document the permission, license, source credits and changes for an adaptation.

## Tested examples

A tested example must be original and must document:

- Exact submitted prompt;
- Exact model identifier and tool/provider;
- Generation mode and supported settings;
- Input assets, ownership, and consent;
- Date generated and useful iteration notes;
- Manual editing, compositing, typography, audio, or cleanup;
- Known defects and review result.

Follow [assets/README.md](./assets/README.md). Never commit credentials, private URLs, personal data, or unlicensed media.

## Pull request checklist

- [ ] I have the rights and consent needed for all submitted text and media;
- [ ] The contribution is original or appropriately licensed, with required author credits and source information preserved;
- [ ] Facts and capability claims link to reliable primary sources;
- [ ] The prompt is understandable without hidden conversation context;
- [ ] The entry uses the correct category, ID, status, and recipe structure;
- [ ] Required text, claims, product details, and safety constraints were checked;
- [ ] New files are linked from an index and all relative Markdown links work;
- [ ] Tested examples disclose model/tool, inputs, settings, edits, and known limitations.

By submitting a contribution, you agree that it may be distributed under this repository's MIT License.
