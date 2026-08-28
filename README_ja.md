# Awesome MiniMax H3 動画プロンプト

[![bestimage.ai](https://bestimage.ai/images/logo.svg)](https://bestimage.ai/)

![MiniMax H3 動画プロンプト集のコンセプトビジュアル](./assets/hero-minimax-h3-video-prompts.png)

> 広告、商品動画、UGC、旅行、料理、ファッション、物語、アニメーション、スポーツ、VFX、UI、ショート動画向けの実用的な MiniMax H3 プロンプト集です。

**言語：** [English](./README.md) · [简体中文](./README_zh.md) · [日本語](./README_ja.md) · [한국어](./README_ko.md) · [Español](./README_es.md) · [Français](./README_fr.md) · [Deutsch](./README_de.md) · [Português](./README_pt.md)

## 内容

- 21カテゴリ、100本の英語動画プロンプト
- 画像・動画・音声参照の役割を明確にする H3 向け構造
- 人物、商品、衣装、場所、画面方向を守る連続性ルール
- テキスト動画、画像動画、広告、UI、アニメーション向けテンプレート
- 8言語の README と、英語以外の8言語による[プロンプト例](./docs/multilingual-prompting.md)。100本すべてを各言語に翻訳したものではありません
- [導入ガイド](./docs/deployment-guide.md)は、簡体字中国語の詳細解説、英語のリファレンス、その他7言語の要約で構成されています
- 新規生成した表紙1点と参考画像8点。いずれも静止画のコンセプトで、H3 の生成結果ではありません

→ **[100本のプロンプトを見る](./prompts/README.md)**

[H3概要](./docs/minimax-h3-overview.md) · [導入ガイド](./docs/deployment-guide.md) · [API ワークフロー](./docs/api-workflow.md) · [公式動画例](./docs/official-h3-examples.md) · [テンプレート](./templates/README.md) · [プロンプトガイド](./docs/prompting-guide.md) · [ユースケース表](./docs/use-case-matrix.md) · [投稿ガイド](./CONTRIBUTING.md)

## bestimage.ai での API ワークフロー

- **動画生成：** [MiniMax H3（英語ページ）](https://bestimage.ai/models/minimax/minimax-h3-text-to-video/)。動画用のプロンプトと、利用する入力方式を確認します。
- **開始フレーム・参考画像の準備：** [GPT Image 2（英語ページ）](https://bestimage.ai/models/openai/gpt-image-2/)。これは画像モデルであり、MiniMax H3 とは別のモデルです。
- 接続手順と確認事項は [API ワークフロー](./docs/api-workflow.md)をご覧ください。

参考画像は内蔵の画像生成ツールで作成した静止画のコンセプトです。H3 の動画出力ではなく、動作や時間的な連続性、音声の品質を示すものではありません。

## 参考画像ギャラリー

各画像は開始フレームや構図を検討するためのコンセプトです。動作、時間的な連続性、音声を検証した動画ではありません。

| コンセプト | 静止画の参考画像 | 対応する英語プロンプト |
|---|---|---|
| 太陽光発電コーヒーキオスクの開店 | ![太陽光発電コーヒーキオスクの開店](./assets/gallery/solar-coffee-kiosk.png) | [BRD-004](./prompts/01-brand-advertising.md#brd-004-solar-coffee-kiosk-opening) |
| トレー2つを横に並べた弁当箱の詰め方 | ![トレー2つを横に並べた弁当箱の詰め方](./assets/gallery/modular-lunchbox.png) | [PRD-004](./prompts/02-product-ecommerce.md#prd-004-two-tray-lunchbox-packing) |
| 旅行用ケーブルポーチへの収納 | ![旅行用ケーブルポーチへの収納](./assets/gallery/travel-cable-pouch.png) | [UGC-004](./prompts/03-ugc-lifestyle.md#ugc-004-cable-pouch-packing-demo) |
| 紙工作の灯台の光 | ![紙工作の灯台の光](./assets/gallery/paper-lighthouse.png) | [ANI-004](./prompts/08-animation-stylized.md#ani-004-paper-lighthouse-beacon) |
| バドミントンのスプリットステップ練習 | ![バドミントンのスプリットステップ練習](./assets/gallery/badminton-split-step.png) | [ACT-004](./prompts/09-action-sports.md#act-004-badminton-split-step-drill) |
| 波動水槽で狭い隙間を通る波 | ![波動水槽で狭い隙間を通る波](./assets/gallery/wave-tank-gap.png) | [EDU-005](./prompts/14-education-documentary-science.md#edu-005-wave-tank-through-a-narrow-gap) |
| 陶製タイルのカメラワーク研究 | ![陶製タイルのカメラワーク研究](./assets/gallery/ceramic-tile-camera-study.png) | [MRF-005](./prompts/20-multireference-camera-transfer.md#mrf-005-ceramic-tile-camera-study) |
| ハリネズミの舞台稽古 | ![ハリネズミの舞台稽古](./assets/gallery/hedgehog-stage-dialogue.png) | [CHR-005](./prompts/21-character-dialogue-performance.md#chr-005-hedgehog-stage-rehearsal) |

[画像の制作記録](./assets/README.md) · [開始フレーム・参考画像の制作指示](./assets/minimax-h3-reference-image-prompts.md)

## 投稿と出典

**投稿歓迎：** 実際の制作課題を解決したオリジナルの H3 プロンプトを提案する際は、[投稿ガイド](./CONTRIBUTING.md)をご覧ください。完成動画は必須ではありませんが、参照素材の役割、時間軸、連続性、音声、テスト状況を明記してください。

本プロジェクトは独立したコミュニティ資料であり、MiniMax の公式プロジェクトではありません。モデル仕様と入力条件は [MiniMax 公式 H3 ドキュメント](https://platform.minimaxi.com/docs/guides/video-prompt)で確認してください。[公式動画例](./docs/official-h3-examples.md)は MiniMax の出典を明記した外部参照であり、本リポジトリのプロンプトの生成結果ではありません。

## bestimage.ai について

このプロンプト集は [bestimage.ai](https://bestimage.ai/) チームが編集・保守し、実践的な制作ワークフローを画像・動画モデルの API につなげます。

## bestimage.ai のアフィリエイトプログラムに参加

チュートリアル、プロンプト、API 連携事例を公開していますか？[bestimage.ai アフィリエイトプログラム](https://bestimage.ai/affiliate-program/)に参加し、読者や視聴者に bestimage.ai を紹介して報酬を得られます。

- 紹介したユーザーの初回の対象有料注文に対して **20%**。
- そのユーザーの**登録後 60 日以内**の、2 回目以降の対象有料注文に対して **10%**。

対象注文と支払いの条件は[現行のアフィリエイト契約](https://bestimage.ai/affiliate-agreement/)に従います。

## ライセンス

[MIT](LICENSE).
