# Awesome MiniMax H3 Video Prompts

<p align="center"><a href="https://bestimage.ai/"><img src="https://bestimage.ai/images/logo.svg" width="72" alt="bestimage.ai logo"></a></p>

![Awesome MiniMax H3 video prompt library hero](./assets/hero-minimax-h3-video-prompts.png)

> A curated and expanded, practical MiniMax H3 audiovisual prompt cookbook for advertising, e-commerce, UGC, travel, food, fashion, film, animation, sports, VFX, UI, music, education, architecture, mobility, nature, industry, and public-service content.

[![License: MIT](https://img.shields.io/badge/license-MIT-0b7285.svg)](./LICENSE)
[![Prompt recipes](https://img.shields.io/badge/prompt_recipes-100-ff6b6b.svg)](./prompts/README.md)
[![Practical categories](https://img.shields.io/badge/practical_categories-21-7950f2.svg)](./prompts/README.md)
[![Sampler languages](https://img.shields.io/badge/localized_samples-8-2f9e44.svg)](./docs/multilingual-prompting.md)
[![Concept images](https://img.shields.io/badge/concept_images-9-f59f00.svg)](./assets/README.md)
[![Contributions welcome](https://img.shields.io/badge/contributions-welcome-2f9e44.svg)](./CONTRIBUTING.md)
[![Maintained by bestimage.ai](https://img.shields.io/badge/maintained_by-bestimage.ai-228be6.svg)](https://bestimage.ai/)

**README languages:** [English](./README.md) · [简体中文](./README_zh.md) · [日本語](./README_ja.md) · [한국어](./README_ko.md) · [Español](./README_es.md) · [Français](./README_fr.md) · [Deutsch](./README_de.md) · [Português](./README_pt.md)

**SEO topics:** MiniMax H3 prompts, MiniMax H3 open weights, MiniMax H3 local deployment, MiniMax H3 SGLang, FL2VA, Ref2VA, MiniMax video prompts, Hailuo AI video prompts, AI video prompt examples, audiovisual generation, multimodal video generation, image-to-video prompts, video editing, video continuation, camera transfer, audio-driven video, multilingual dialogue, character performance, product video, AI advertising, UGC video, cinematic prompts, animation, VFX, and reusable video prompt templates.

| [Browse all 100 prompts](./prompts/README.md) | [Submit an original prompt](./CONTRIBUTING.md) | [Improve the documentation](./CONTRIBUTING.md) | [Open a pull request](./CONTRIBUTING.md) |
|---|---|---|---|

[H3 overview](./docs/minimax-h3-overview.md) · [Open-weight deployment](./docs/deployment-guide.md) · [Official example gallery](./docs/official-h3-examples.md) · [Production templates](./templates/README.md) · [Prompting guide](./docs/prompting-guide.md) · [Use-case matrix](./docs/use-case-matrix.md) · [Multilingual prompts](./docs/multilingual-prompting.md) · [Reference-image briefs](./assets/minimax-h3-reference-image-prompts.md) · [Contributing](./CONTRIBUTING.md)

## What you get

- 100 copy-ready audiovisual recipes across 21 practical production categories;
- Reference maps that assign a precise role to every image, video, and audio input;
- Timelines with readable beats, camera behavior, state changes, sound intent, and endings;
- Identity, wardrobe, product, location, UI, screen-direction, and edit-scope locks;
- Commercial scenarios spanning campaigns, e-commerce, hospitality, food, fashion, games, education, and social media;
- Eight README entry pages, including English, and eight sample prompts in non-English languages; these are not full translations of the 100-recipe library;
- Nine newly generated static concept images with exact prompts and recorded tool provenance;
- A detailed Chinese deployment guide, an English reference and seven other language summaries for FL2VA, Ref2VA, local 768p generation and the hybrid 2K workflow;
- An attributed gallery linking official H3 skills, reproducible scripts, and hosted example videos;
- Originality, rights, safety, fact-checking, and output-review rules for practical publishing.

## Create reference images, then generate video

Maintained by the **[bestimage.ai](https://bestimage.ai/) team**, this library connects reusable creative briefs with two distinct workflows:

- **[MiniMax H3 API](https://bestimage.ai/models/minimax/minimax-h3-text-to-video/):** generate video from a text brief, a first frame, or supported references. The [API workflow](./docs/api-workflow.md) separates bestimage.ai's published request schema from MiniMax's direct API and local deployment.
- **[GPT Image 2 API](https://bestimage.ai/models/openai/gpt-image-2/):** prepare a product reference, character concept or opening frame before a separate H3 video request. GPT Image 2 produces images; it is not the H3 video endpoint.

Both links above open English pages. Check the [API documentation](https://bestimage.ai/docs/) for current access and fields.

## Bring an original H3 workflow

Have a prompt that solved a real production problem? [Open the guided prompt proposal](./CONTRIBUTING.md)—a polished video is welcome but not required. A strong submission explains the deliverable, reference roles, visible action, timing, continuity locks, sound intent, likely failure modes, and whether the recipe is conceptual or tested.

Good first contributions include testing an existing recipe, filling a practical scenario gap, improving a review checklist, adding a native-language adaptation, or reporting stale official documentation. Please read [CONTRIBUTING.md](./CONTRIBUTING.md); contributions must be original, rights-cleared, reproducible, and free of hidden promotional or tracking links.

## Why the recipes are structured for H3

MiniMax's official H3 materials highlight three areas: native multimodal understanding and generation across text, images, audio, and video; precise multimodal editing and control over people, objects, scenes, sound, and rhythm; and commercial content generation for film, advertising, e-commerce, digital experiences, games, and animation. See the [official MiniMax H3 capability examples](https://platform.minimaxi.com/docs/guides/video-prompt).

This library turns those capabilities into a repeatable prompt contract:

```text
Reference map: what each image, video, or audio input controls
Deliverable: channel, aspect ratio, duration target, audience, goal
Creative direction: scene, subject, story, style, light, color
Timeline: opening state → action beats → final state
Camera: framing, screen direction, movement, cut and transition rules
Continuity locks: identity, product, wardrobe, environment, UI, props
Sound intent: ambience, effects, dialogue or music role
Edit scope: what may change and what must remain untouched
Avoid: likely visual, physical, continuity, legal, and brand failures
```

The repository does not invent request parameters. See the [H3 overview and official resources](./docs/minimax-h3-overview.md), then confirm current model identifiers, supported inputs, limits, API fields, model license, and downloadable-release behavior in MiniMax's official documentation and model card.

## Official H3 and open-weight resources

- **Official H3 repository:** [MiniMax-AI/MiniMax-H3](https://github.com/MiniMax-AI/MiniMax-H3)
- **H3 model card and open weights:** [MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)
- **Local deployment guide:** [Nine-language deployment documentation](./docs/deployment-guide.md)
- **Official videos and skills:** [Attributed example gallery](./docs/official-h3-examples.md)
- **Official H3 capability examples:** [MiniMax video prompt guide](https://platform.minimaxi.com/docs/guides/video-prompt)
- **Hosted video workflow:** [MiniMax video generation guide](https://platform.minimaxi.com/docs/guides/video-generation)

The current release provides H3-Base FL2VA and Ref2VA weights for local 768p audiovisual generation. H3-Context-IR and H3-Regenerate-2K remain hosted components, so the full 2K workflow combines local generation with official APIs. Check the current Community License, supported tasks, runtime requirements, and release files before local or commercial use.

## Official H3 examples

The following previews are remotely referenced from and linked back to the official MiniMax-H3 repository. They are not stored in this repository and are not presented as outputs of this prompt library.

| Product advertising | 3D animation | Music video |
|---|---|---|
| [![Official MiniMax H3 minimalist product advertisement](https://raw.githubusercontent.com/MiniMax-AI/MiniMax-H3/main/assets/minimalist-product-ad-generator.gif)](https://github.com/MiniMax-AI/MiniMax-H3/tree/main/skills/minimalist-product-ad-generator) | [![Official MiniMax H3 3D animation short](https://raw.githubusercontent.com/MiniMax-AI/MiniMax-H3/main/assets/3d-animation-short-generator.gif)](https://github.com/MiniMax-AI/MiniMax-H3/tree/main/skills/3d-animation-short-generator) | [![Official MiniMax H3 music-video subtitle example](https://raw.githubusercontent.com/MiniMax-AI/MiniMax-H3/main/assets/music-video-subtitle-generator.gif)](https://github.com/MiniMax-AI/MiniMax-H3/tree/main/skills/music-video-subtitle-generator) |

Browse the [complete attributed official example gallery](./docs/official-h3-examples.md) for reproducible T2VA, FL2VA and Ref2VA request scripts, 768p MP4 outputs, and 2K workflow comparisons.

## Reference-image gallery

These eight newly generated static concepts illustrate this edition's new recipes. Together with the cover, they make nine images. They were created with Codex's built-in image generation tool, **not MiniMax H3**, and are not video frames from a tested H3 run. See [exact prompts](./assets/minimax-h3-reference-image-prompts.md) and [production records](./assets/README.md).

| Solar coffee kiosk opening | Two-tray lunchbox packing | Cable pouch packing demo |
|---|---|---|
| ![Solar coffee kiosk opening: generated static concept](./assets/gallery/solar-coffee-kiosk.png) | ![Two-tray lunchbox packing: generated static concept](./assets/gallery/modular-lunchbox.png) | ![Cable pouch packing demo: generated static concept](./assets/gallery/travel-cable-pouch.png) |
| [BRD-004 recipe](./prompts/01-brand-advertising.md#brd-004-solar-coffee-kiosk-opening) | [PRD-004 recipe](./prompts/02-product-ecommerce.md#prd-004-two-tray-lunchbox-packing) | [UGC-004 recipe](./prompts/03-ugc-lifestyle.md#ugc-004-cable-pouch-packing-demo) |

| Paper lighthouse beacon | Badminton split-step drill | Wave tank through a narrow gap |
|---|---|---|
| ![Paper lighthouse beacon: generated static concept](./assets/gallery/paper-lighthouse.png) | ![Badminton split-step drill: generated static concept](./assets/gallery/badminton-split-step.png) | ![Wave tank through a narrow gap: generated static concept](./assets/gallery/wave-tank-gap.png) |
| [ANI-004 recipe](./prompts/08-animation-stylized.md#ani-004-paper-lighthouse-beacon) | [ACT-004 recipe](./prompts/09-action-sports.md#act-004-badminton-split-step-drill) | [EDU-005 recipe](./prompts/14-education-documentary-science.md#edu-005-wave-tank-through-a-narrow-gap) |

| Ceramic tile camera study | Hedgehog stage rehearsal |
|---|---|
| ![Ceramic tile camera study: generated static concept](./assets/gallery/ceramic-tile-camera-study.png) | ![Hedgehog stage rehearsal: generated static concept](./assets/gallery/hedgehog-stage-dialogue.png) |
| [MRF-005 recipe](./prompts/20-multireference-camera-transfer.md#mrf-005-ceramic-tile-camera-study) | [CHR-005 recipe](./prompts/21-character-dialogue-performance.md#chr-005-hedgehog-stage-rehearsal) |

## Browse the cookbook

| Collection | Recipes | Highlights |
|---|---:|---|
| [Brand and advertising](./prompts/01-brand-advertising.md) | 5 | Product launch, local campaign, multi-ratio adaptation |
| [Product and e-commerce](./prompts/02-product-ecommerce.md) | 5 | Feature demo, material film, 360° listing rotation |
| [UGC and lifestyle](./prompts/03-ugc-lifestyle.md) | 5 | Honest first impression, routine, packing test |
| [Travel and hospitality](./prompts/04-travel-hospitality.md) | 4 | Destination film, guesthouse reveal, market walkthrough |
| [Food and beverage](./prompts/05-food-beverage.md) | 4 | Bakery craft, noodle service, sparkling drink macro |
| [Fashion and beauty](./prompts/06-fashion-beauty.md) | 4 | Eyewear editorial, lip texture, four-look transition |
| [Cinematic storytelling](./prompts/07-cinematic-storytelling.md) | 4 | Unsent letter, train farewell, rooftop mystery |
| [Animation and stylized video](./prompts/08-animation-stylized.md) | 5 | Paper ecology, clay robot, ink transformation |
| [Action and sports](./prompts/09-action-sports.md) | 4 | Climbing, wet-circuit cycling, table tennis |
| [Fantasy, sci-fi and VFX](./prompts/10-fantasy-scifi-vfx.md) | 4 | Glasshouse stars, miniature water system, light dress |
| [UI, game and digital experience](./prompts/11-ui-game-digital.md) | 4 | App walkthrough, hardware UI, game inventory |
| [Transitions, comedy and social](./prompts/12-transitions-comedy-social.md) | 4 | Match cut, office plant comedy, laundromat alien |
| [Music, performance and audio-driven video](./prompts/13-music-performance-audio.md) | 5 | Live music, multilingual duet, dance, audio visualizer |
| [Education, documentary and science](./prompts/14-education-documentary-science.md) | 6 | Science explainer, museum object, safety procedure, microscopy |
| [Architecture, interiors and real estate](./prompts/15-architecture-interiors-real-estate.md) | 5 | Property tour, daylight study, renovation, smart home |
| [Automotive and mobility](./prompts/16-automotive-mobility.md) | 5 | Car interior, cargo bicycle, sleeper train, delivery robot |
| [Nature, animals and pets](./prompts/17-nature-animals-pets.md) | 5 | Wildlife, pet fit check, plant diary, tide-pool macro |
| [Industry, business and public service](./prompts/18-industry-business-public-service.md) | 5 | Assembly, cold chain, evacuation, bilingual service |
| [Editing, continuation and localization](./prompts/19-editing-continuation-localization.md) | 5 | Background cleanup, clip extension, localization, relighting |
| [Multi-reference and camera transfer](./prompts/20-multireference-camera-transfer.md) | 6 | One-take miniature, motion grammar, craft match actions, tutorial |
| [Character, dialogue and performance](./prompts/21-character-dialogue-performance.md) | 6 | Paper characters, restrained emotion, bilingual repair, ensemble scene |

## Quick start

1. Choose a recipe by the final deliverable and its biggest production risk.
2. Upload only the references you need and label each one by role.
3. Replace every `[bracketed variable]`; keep fictional placeholders or insert rights-cleared assets.
4. Adapt the timeline to the duration available in your H3 workflow.
5. Generate a structure pass before adding complex sound, typography, or effects.
6. Revise one failure class at a time: motion, identity, product, camera, text, or sound.
7. Review at normal speed, frame by frame, muted, and at final delivery size.

For multilingual work, start from the English canonical recipe and localize the complete specification. The [multilingual guide](./docs/multilingual-prompting.md) includes ready-to-copy examples in Simplified Chinese, Japanese, Korean, Spanish, French, German, Portuguese, and Arabic.

## Originality, rights, and safety

- Submit original or appropriately licensed prompt text, preserve required source credits, and use rights-cleared inputs or outputs;
- Do not imitate a protected character, living artist, private person, campaign, product, or interface;
- Treat testimonials, ratings, prices, dates, performance claims, maps, and historical facts as verified data—not creative filler;
- Obtain consent and the necessary rights for identity, voice, music, brands, locations, and footage;
- Disclose generated or materially altered media where law or platform rules require it;
- Keep the exact model/tool, inputs, settings, date, edits, and known defects for published examples.

See the [originality policy](./docs/originality-policy.md), [CONTRIBUTING.md](./CONTRIBUTING.md), and the [asset production rules](./assets/README.md).

## About bestimage.ai

This prompt library is curated and maintained by the [bestimage.ai](https://bestimage.ai/) team, connecting practical creative workflows with image and video model APIs.

## Earn with the bestimage.ai Affiliate Program

Build tutorials, share prompts, or publish API integrations? Join the [bestimage.ai Affiliate Program](https://bestimage.ai/affiliate-program/) and earn commissions by introducing your audience to bestimage.ai.

- **20%** on a referred user's first valid paid order.
- **10%** on subsequent valid paid orders made within **60 days after that user registers**.

Order eligibility and payouts follow the [current affiliate agreement](https://bestimage.ai/affiliate-agreement/).

## License

[MIT](LICENSE).
