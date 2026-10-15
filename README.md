# Momiji Autumn

作者：なこと｜X：[@Nakot_otanotion](https://x.com/Nakot_otanotion)

紅葉の深い紅、和紙のような生成り、秋の夕暮れの金色を組み合わせた、日本の秋をイメージしたオリジナルのObsidianテーマです。ライト／ダークはObsidianの外観設定に合わせて自動で切り替わります。

![Momiji Autumn theme preview showing light and dark palettes](./assets/theme-preview.png)

*Theme concept mockup for palette preview; it is not a literal Obsidian screenshot.*

## Features

- Palette: momiji red `#D93448`, sumi charcoal `#2f3136`, gingko gold `#ffba0d`, with deeper beni and ember-orange supporting accents
- Light and dark color schemes
- Japanese serif text styling and restrained heading decorations
- Styled code blocks, inline code, links, tags, highlights, tables, quotes, and callouts
- Subtle falling momiji leaf animation, disabled when reduced motion is preferred
- No network calls or remote assets

## Install locally

1. Unzip this package. For local installation, rename the extracted `momiji-autumn-theme` folder to `Momiji Autumn` (the folder name must match the theme name in `manifest.json`), then place it in your vault's `.obsidian/themes/` folder.
2. In Obsidian, open **Settings → Appearance → Themes**.
3. Choose **Momiji Autumn** from the theme list.
4. Change **Base color scheme** to Light, Dark, or Adapt to system to preview both palettes.

For GitHub, upload the contents of the extracted `momiji-autumn-theme` folder to the repository root. For local development, use the `Momiji Autumn` folder name under `.obsidian/themes/`. Restart Obsidian after changing `manifest.json`; CSS changes can be previewed after reloading the theme.

## Waka & Hyakunin Isshu note template

The package includes `templates/waka-hyakunin-isshu-template.md`, an original study template with fields for the poem, author, source, reading, modern paraphrase, literary devices, season and scenery, interpretation, karuta memory cues, related notes, and references. It uses the `karuta-note` and `waka-note` CSS classes for optional note-specific styling.

To use it, copy the Markdown file into your vault's Templates folder, enable Obsidian's core **Templates** plugin, and set that folder in **Settings → Templates**. Insert the template into a new note from the Command palette.

## Community directory submission checklist

This repository is a starter theme package. Before submitting it to the Obsidian Community directory:

1. Confirm the public author name and license. The current package uses the MIT License as a starting point; change it if that is not the intended reuse policy.
2. Replace the included concept mockup with a real screenshot captured from Obsidian. The included `assets/theme-preview.png` is not an application screenshot. Obsidian recommends a 16:9 image around 512 × 288 pixels.
3. Confirm the GitHub repository is public and includes `README.md`, `LICENSE`, `manifest.json`, and `theme.css` at its root.
4. Create a GitHub Release whose tag matches `version` in `manifest.json` (currently `1.0.0`) and attach `manifest.json` and `theme.css`.
5. Sign in to the Obsidian Community directory, link the GitHub account, submit the theme, and address any automated review feedback.

For the official requirements, see [Submit your theme](https://docs.obsidian.md/themes/app-themes/submit-theme), [Theme guidelines](https://docs.obsidian.md/Themes/App+themes/Theme+guidelines), and [Developer policies](https://docs.obsidian.md/Developer+policies).

## Versioning

Use `x.y.z` versions. When publishing an update, update `manifest.json` and `versions.json`, then create a GitHub Release with a matching tag and attach the release files.
