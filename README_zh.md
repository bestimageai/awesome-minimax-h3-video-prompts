# Awesome MiniMax H3 视频提示词

[![bestimage.ai](https://bestimage.ai/images/logo.svg)](https://bestimage.ai/)

![Awesome MiniMax H3 视频提示词库概念主视觉](./assets/hero-minimax-h3-video-prompts.png)

> 由 bestimage.ai 团队整理扩展的 MiniMax H3 音视频提示词手册，覆盖广告、电商、UGC、旅行、美食、时尚、电影、动画、体育、VFX、UI、音乐、教育、建筑、出行、自然、工业与公共服务。

[![License: MIT](https://img.shields.io/badge/license-MIT-0b7285.svg)](./LICENSE)
[![英文提示词](https://img.shields.io/badge/English_prompts-100-ff6b6b.svg)](./prompts/README.md)
[![实用分类](https://img.shields.io/badge/practical_categories-21-7950f2.svg)](./prompts/README.md)
[![非英文提示词示例](https://img.shields.io/badge/localized_prompt_examples-8-2f9e44.svg)](./docs/multilingual-prompting.md)
[![静态概念图](https://img.shields.io/badge/concept_images-9-f59f00.svg)](./assets/README.md)
[![欢迎贡献](https://img.shields.io/badge/contributions-welcome-2f9e44.svg)](./CONTRIBUTING.md)
[![由 bestimage.ai 维护](https://img.shields.io/badge/maintained_by-bestimage.ai-228be6.svg)](https://bestimage.ai/)

**README 语言：** [English](./README.md) · [简体中文](./README_zh.md) · [日本語](./README_ja.md) · [한국어](./README_ko.md) · [Español](./README_es.md) · [Français](./README_fr.md) · [Deutsch](./README_de.md) · [Português](./README_pt.md)

**SEO 主题：** MiniMax H3 提示词、MiniMax H3 开放权重、MiniMax H3 本地部署、MiniMax H3 SGLang、FL2VA、Ref2VA、MiniMax 视频提示词、海螺 AI 视频提示词、AI 视频生成案例、原生音视频生成、多模态视频、图生视频提示词、视频编辑、视频续写、运镜迁移、声音驱动视频、多语言对白、角色表演、AI 广告、电商视频、UGC 视频、电影感提示词、动画提示词、VFX 提示词和通用视频模板。

| [浏览全部 100 条提示词](./prompts/README.md) | [贡献提示词与文档](./CONTRIBUTING.md) | [API 工作流](./docs/api-workflow.md) |
|---|---|---|

[H3 模型说明](./docs/minimax-h3-overview.md) · [开源部署指南](./docs/deployment-guide.md) · [官方视频示例](./docs/official-h3-examples.md) · [制作模板](./templates/README.md) · [H3 提示词指南](./docs/prompting-guide.md) · [场景矩阵](./docs/use-case-matrix.md) · [多语言提示词](./docs/multilingual-prompting.md) · [H3 参考图简报](./assets/minimax-h3-reference-image-prompts.md) · [贡献指南](./CONTRIBUTING.md)

## 你将获得

- 21 个制作分类、100 条可直接改写的英文音视频提示词；
- 为每张图片、每段视频和每段音频明确职责的参考素材映射；
- 包含清晰节拍、运镜、状态变化、声音意图和结尾状态的时间线；
- 人物、服装、产品、场景、UI、屏幕方向和编辑范围锁定规则；
- 覆盖品牌、电商、酒店、餐饮、时尚、游戏、教育和社交媒体的实用场景；
- 8 种 README 入口，以及 8 个非英文语言的提示词示例；这不表示 100 条提示词均已完成多语言翻译；
- 1 张封面和 8 张案例静态概念图，以及 H3 首帧/参考图简报；
- 覆盖 FL2VA、Ref2VA、SGLang、本地 768p 和混合 2K 流程的部署指南，包含简体中文详解、英文参考和另外 7 种语言的摘要；
- 标明官方来源的视频、Skill、可复现请求脚本和效果对照画廊；
- 面向发布的原创性、版权、安全、事实核验和成片审查规则。

## bestimage.ai API 工作流

- **视频生成：** [MiniMax H3 英文落地页](https://bestimage.ai/models/minimax/minimax-h3-text-to-video/)，用于了解视频生成入口及当前支持的输入方式。
- **首帧与参考图准备：** [GPT Image 2 英文落地页](https://bestimage.ai/models/openai/gpt-image-2/)，用于准备静态图像素材。GPT Image 2 是图片模型，与 MiniMax H3 是两个独立模型。
- 接入步骤、输入准备与验证边界见 [API 工作流](./docs/api-workflow.md)。

封面和案例图由内置图像生成工具生成，用于首帧、构图和氛围参考，是静态概念图，不是 H3 视频输出。

## 欢迎提交你的原创 H3 工作流

如果某条提示词帮你解决了真实制作问题，欢迎按[贡献指南](./CONTRIBUTING.md)准备提案。成片不是必需项；高质量提案应说明交付目标、参考素材职责、可见动作、时间线、连续性锁定、声音意图、易错点，以及内容是概念版还是已测试版本。

适合首次参与的任务包括：测试现有配方、补充真实场景缺口、改进审查清单、增加母语适配，或报告已经失效的官方文档。提交前请阅读[贡献指南](./CONTRIBUTING.md)；内容必须原创、权利清晰、可复核，并且不能包含隐藏推广或追踪链接。

## 为什么按 H3 特性组织

MiniMax 官方 H3 资料强调三类能力：文字、图片、音频、视频的原生多模态理解与生成；对人物、物体、场景、声音和节奏的多维编辑控制；面向影视、广告、电商、数字体验、游戏和动画的商用内容生成。详见 [MiniMax 官方 H3 亮点示例](https://platform.minimaxi.com/docs/guides/video-prompt)。

本项目将这些能力整理为可复用的提示词契约：

```text
参考素材映射：每张图、视频或音频允许控制什么
交付要求：渠道、比例、目标时长、受众、目标
创意方向：场景、主体、故事、风格、光线、色彩
时间线：开场状态 → 动作节拍 → 结束状态
镜头：景别、屏幕方向、运镜、剪辑和转场规则
连续性锁定：身份、产品、服装、环境、UI、道具
声音意图：环境音、音效、对白或音乐的职责
编辑范围：允许修改什么、必须保持什么
避免：视觉、物理、连续性、法律和品牌风险
```

仓库不会编造接口参数。请先阅读 [H3 模型说明与官方资源](./docs/minimax-h3-overview.md)，当前模型标识、支持输入、限制、API 字段、模型许可和可下载版本能力以 MiniMax 官方文档及模型卡为准。

## MiniMax H3 官方与开放权重地址

- **H3 官方仓库：** [MiniMax-AI/MiniMax-H3](https://github.com/MiniMax-AI/MiniMax-H3)
- **H3 模型卡与开放权重：** [MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)
- **本地部署：** [开源部署指南：中文详解、英文参考及另外 7 种语言摘要](./docs/deployment-guide.md)
- **官方视频和 Skill：** [带来源标注的官方示例画廊](./docs/official-h3-examples.md)
- **H3 官方能力与提示词示例：** [MiniMax 视频提示词指南](https://platform.minimaxi.com/docs/guides/video-prompt)
- **托管视频生成流程：** [MiniMax 视频生成文档](https://platform.minimaxi.com/docs/guides/video-generation)

当前开放版本提供 H3-Base FL2VA 与 Ref2VA 权重，可在本地生成 768p 原生音视频；H3-Context-IR 与 H3-Regenerate-2K 仍是托管组件，完整 2K 流程需要本地生成与官方 API 配合。部署或商用前，请核对最新 Community License、支持任务、硬件/运行时要求和实际发布文件。

## MiniMax H3 官方效果示例

以下预览通过远程链接引用自 MiniMax-H3 官方仓库，并直接链接回官方 Skill。媒体文件没有复制到本项目，也不会被描述成本提示词库的生成结果。

| 产品广告 | 3D 动画 | 音乐视频 |
|---|---|---|
| [![MiniMax H3 官方极简产品广告示例](https://raw.githubusercontent.com/MiniMax-AI/MiniMax-H3/main/assets/minimalist-product-ad-generator.gif)](https://github.com/MiniMax-AI/MiniMax-H3/tree/main/skills/minimalist-product-ad-generator) | [![MiniMax H3 官方 3D 动画短片示例](https://raw.githubusercontent.com/MiniMax-AI/MiniMax-H3/main/assets/3d-animation-short-generator.gif)](https://github.com/MiniMax-AI/MiniMax-H3/tree/main/skills/3d-animation-short-generator) | [![MiniMax H3 官方音乐视频字幕示例](https://raw.githubusercontent.com/MiniMax-AI/MiniMax-H3/main/assets/music-video-subtitle-generator.gif)](https://github.com/MiniMax-AI/MiniMax-H3/tree/main/skills/music-video-subtitle-generator) |

在[带来源标注的官方示例画廊](./docs/official-h3-examples.md)中，可以继续查看可复现的 T2VA、FL2VA、Ref2VA 请求脚本、768p MP4 输出和 2K 流程对照。

## 静态参考图画廊

这些图片由内置图像生成工具生成，用于提示词的首帧、构图和氛围参考，不是 H3 输出，也不是模型跑分。静态图不能验证动作、时间连续性或声音效果。

| 场景 | 静态参考图 | 对应英文提示词 |
|---|---|---|
| 太阳能咖啡亭开店 | ![太阳能咖啡亭开店](./assets/gallery/solar-coffee-kiosk.png) | [BRD-004](./prompts/01-brand-advertising.md#brd-004-solar-coffee-kiosk-opening) |
| 并排双内盒便当装餐 | ![并排双内盒便当装餐](./assets/gallery/modular-lunchbox.png) | [PRD-004](./prompts/02-product-ecommerce.md#prd-004-two-tray-lunchbox-packing) |
| 旅行线材收纳包演示 | ![旅行线材收纳包演示](./assets/gallery/travel-cable-pouch.png) | [UGC-004](./prompts/03-ugc-lifestyle.md#ugc-004-cable-pouch-packing-demo) |
| 纸艺灯塔信标 | ![纸艺灯塔信标](./assets/gallery/paper-lighthouse.png) | [ANI-004](./prompts/08-animation-stylized.md#ani-004-paper-lighthouse-beacon) |
| 羽毛球分腿垫步训练 | ![羽毛球分腿垫步训练](./assets/gallery/badminton-split-step.png) | [ACT-004](./prompts/09-action-sports.md#act-004-badminton-split-step-drill) |
| 波动水槽中的狭缝传播 | ![波动水槽中的狭缝传播](./assets/gallery/wave-tank-gap.png) | [EDU-005](./prompts/14-education-documentary-science.md#edu-005-wave-tank-through-a-narrow-gap) |
| 陶瓷砖运镜研究 | ![陶瓷砖运镜研究](./assets/gallery/ceramic-tile-camera-study.png) | [MRF-005](./prompts/20-multireference-camera-transfer.md#mrf-005-ceramic-tile-camera-study) |
| 刺猬舞台排练 | ![刺猬舞台排练](./assets/gallery/hedgehog-stage-dialogue.png) | [CHR-005](./prompts/21-character-dialogue-performance.md#chr-005-hedgehog-stage-rehearsal) |

9 个视觉概念的制作说明见 [H3 首帧与参考图简报](./assets/minimax-h3-reference-image-prompts.md)，来源和生成记录见[素材制作记录](./assets/README.md)。

## 21 个实用分类

| 分类 | 数量 | 重点场景 |
|---|---:|---|
| [品牌与广告](./prompts/01-brand-advertising.md) | 5 | 新品发布、本地活动、多比例适配 |
| [产品与电商](./prompts/02-product-ecommerce.md) | 5 | 功能演示、材质片、商品旋转展示 |
| [UGC 与生活方式](./prompts/03-ugc-lifestyle.md) | 5 | 真实体验、生活流程、装包测试 |
| [旅行与酒店](./prompts/04-travel-hospitality.md) | 4 | 目的地、客房、夜市动线 |
| [美食与饮料](./prompts/05-food-beverage.md) | 4 | 烘焙、出餐、饮料微距 |
| [时尚与美妆](./prompts/06-fashion-beauty.md) | 4 | 眼镜大片、唇妆材质、换装转场 |
| [电影叙事](./prompts/07-cinematic-storytelling.md) | 4 | 未寄信件、车站告别、屋顶悬疑 |
| [动画与风格化影像](./prompts/08-animation-stylized.md) | 5 | 剪纸科普、黏土角色、水墨变形 |
| [动作与运动](./prompts/09-action-sports.md) | 4 | 攀岩、雨地骑行、乒乓球、羽毛球 |
| [奇幻、科幻与 VFX](./prompts/10-fantasy-scifi-vfx.md) | 4 | 玻璃花房、微缩城市、光点礼服 |
| [UI、游戏与数字体验](./prompts/11-ui-game-digital.md) | 4 | App 演示、硬件 UI、游戏背包 |
| [转场、喜剧与社交内容](./prompts/12-transitions-comedy-social.md) | 4 | 匹配剪辑、办公室植物、洗衣房外星人 |
| [音乐、表演与声音驱动视频](./prompts/13-music-performance-audio.md) | 5 | 现场音乐、多语言对唱、舞蹈、声音可视化 |
| [教育、纪录与科学](./prompts/14-education-documentary-science.md) | 6 | 科普、博物馆、操作安全、显微世界、波动水槽 |
| [建筑、室内与房地产](./prompts/15-architecture-interiors-real-estate.md) | 5 | 房产漫游、光照、改造、智能家居 |
| [汽车与出行](./prompts/16-automotive-mobility.md) | 5 | 汽车内饰、货运自行车、卧铺列车、配送机器人 |
| [自然、动物与宠物](./prompts/17-nature-animals-pets.md) | 5 | 野生动物、宠物、植物生长、潮池微距 |
| [工业、商业与公共服务](./prompts/18-industry-business-public-service.md) | 5 | 装配、冷链、疏散、双语服务 |
| [视频编辑、续写与本地化](./prompts/19-editing-continuation-localization.md) | 5 | 背景清理、镜头续写、本地化、重布光 |
| [多参考与运镜迁移](./prompts/20-multireference-camera-transfer.md) | 6 | 微缩长镜头、运镜语法、工艺匹配剪辑、教程 |
| [角色、对白与表演](./prompts/21-character-dialogue-performance.md) | 6 | 纸艺角色、克制情绪、双语维修、群像叙事、舞台排练 |

## 快速开始

1. 按最终交付物和主要制作风险选择配方。
2. 只上传真正需要的参考素材，并为每个素材标记职责。
3. 替换所有 `[方括号变量]`，使用虚构设定或获得授权的真实素材。
4. 根据 H3 当前工作流支持的时长调整时间线。
5. 先生成结构版本，再增加复杂声音、文字或特效。
6. 每次只修复一个问题：动作、身份、产品、镜头、文字或声音。
7. 以正常速度、逐帧、静音和最终展示尺寸分别检查。

多语言制作应从英文规范源开始，完整翻译动作、镜头、声音和约束，而不是只翻译风格词。[多语言指南](./docs/multilingual-prompting.md)提供简体中文、日语、韩语、西班牙语、法语、德语、葡萄牙语和阿拉伯语完整示例。

## 原创、版权与安全

- 只提交原创提示词以及拥有必要权利的输入和输出；
- 不仿制受保护角色、在世艺术家、私人个体、广告活动、商品或界面；
- 口碑、评分、价格、日期、性能、地图与历史事实必须经过核验；
- 确保身份、声音、音乐、品牌、场地和素材获得必要同意与授权；
- 在法律或平台要求的场景中标注生成或大幅修改的媒体；
- 发布示例时保存模型/工具、输入、设置、日期、人工修改和已知缺陷。

详细规则见[原创与来源政策](./docs/originality-policy.md)、[CONTRIBUTING.md](./CONTRIBUTING.md)和[素材制作规范](./assets/README.md)。

## 关于 bestimage.ai

本提示词库由 [bestimage.ai](https://bestimage.ai/) 团队整理与维护，将实用创作流程与图像、视频模型 API 连接起来。

## 加入 bestimage.ai 联盟推广计划

制作教程、分享提示词或发布 API 集成案例？加入 [bestimage.ai 联盟推广计划](https://bestimage.ai/affiliate-program/)，向你的受众推荐 bestimage.ai，并获得推荐佣金。

- 受推荐用户的首笔有效付费订单，佣金为 **20%**。
- 该用户**注册后 60 天内**的后续有效付费订单，佣金为 **10%**。

订单资格与结算以[现行联盟协议](https://bestimage.ai/affiliate-agreement/)为准。

## 许可证

[MIT](LICENSE).
