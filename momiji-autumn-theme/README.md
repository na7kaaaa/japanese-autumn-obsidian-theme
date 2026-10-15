# Momiji Autumn

> 紅葉の深い紅、和紙のような生成り、秋の夕暮れの金色。日本の秋をイメージした、オリジナルのObsidianテーマです。

**作者：** なこと　｜　**X：** [@Nakot_otanotion](https://x.com/Nakot_otanotion)　｜　**ライセンス：** MIT

![Momiji Autumnのライトモードとダークモードの配色プレビュー](assets/theme-preview.png)

*画像は配色イメージを示すコンセプトモックアップです。Obsidianの実画面キャプチャではありません。*

## テーマの特徴

- **ライト／ダーク対応**：Obsidianの外観設定に合わせて自動で切り替わります。
- **日本の秋色**：紅葉色 `#D93448`、墨色 `#2f3136`、銀杏色 `#ffba0d` を中心に構成。
- **読みやすいノート画面**：日本語の明朝体、控えめな見出し装飾、コードブロック、行内コード、リンク、タグ、ハイライト、表、引用、コールアウトを調整。
- **舞い落ちる紅葉**：さりげないCSSアニメーション。OSで「視差効果を減らす」が有効な場合は停止します。
- **外部通信なし**：外部画像やネットワーク呼び出しを使いません。

## インストール

### 手動でインストールする

1. このリポジトリを **Code → Download ZIP** からダウンロードし、解凍します。
2. 解凍したテーマフォルダを `Momiji Autumn` に名前変更します。フォルダ名は `manifest.json` のテーマ名と一致させます。
3. フォルダをVault内の `.obsidian/themes/` に配置します。
4. Obsidianの **設定 → 外観 → テーマ** を開き、**Momiji Autumn** を選びます。
5. ライト／ダークを確認するには、**基本カラースキーム**を「ライト」「ダーク」「システムに合わせる」に切り替えます。

### GitHubへファイルをアップロードする

ZIP内の `momiji-autumn-theme` フォルダそのものではなく、**フォルダの中身**をリポジトリのルートにアップロードしてください。`assets/` と `templates/` のフォルダ構成は保ちます。

## 和歌・百人一首ノートテンプレート

`templates/waka-hyakunin-isshu-template.md` を同梱しています。和歌の原文・よみ・現代語訳・技法・季節や情景・解釈・かるたの覚え書き・出典をまとめられる、鑑賞用テンプレートです。

1. MarkdownファイルをVaultのTemplatesフォルダにコピーします。
2. Obsidianのコアプラグイン **テンプレート** を有効にし、設定でTemplatesフォルダを指定します。
3. コマンドパレットからテンプレートを新しいノートに挿入します。

テンプレートには `karuta-note` と `waka-note` のクラスが設定されており、`karuta-note` にテーマ固有の見出し・引用装飾が適用されます。

## カラーパレット

| 色 | カラーコード | イメージ |
| --- | --- | --- |
| 紅葉色 | `#D93448` | 紅葉・朱印のアクセント |
| 墨色 | `#2f3136` | 墨のようなチャコール |
| 銀杏色 | `#ffba0d` | 秋の夕暮れ・銀杏の差し色 |

## バージョン・コミュニティ公開について

現在のテーマバージョンは **1.0.0**、最小対応Obsidianバージョンは **1.10.6** です。コミュニティテーマ一覧への申請前に、実際のObsidian画面のスクリーンショット、ライセンス、作者名を確認してください。申請用リリースを作る際は、`manifest.json` と `versions.json` のバージョンを揃え、同じバージョン番号のGitHub Releaseを作成します。

## English

**Momiji Autumn** is an original Obsidian theme inspired by Japanese fall colors. It includes automatic light and dark palettes, Japanese typography, autumn-styled Markdown elements, subtle falling-leaf animation, and a waka / Hyakunin Isshu note template. The preview above is a concept mockup, not an actual Obsidian screenshot.

## ライセンス

[MIT License](LICENSE)
