# MarkdownPreview

**Preview Markdown files in macOS Finder with Quick Look — just press Space.**

MarkdownPreview is a lightweight macOS Quick Look extension. Select a `.md` file
in Finder, hit the spacebar, and see it rendered as clean, readable HTML instead
of raw text — no app to open, no window to manage.

## Features

- **Instant previews** for `.md`, `.markdown`, `.mdown`, and `.mkd` files
- **GitHub-style rendering** — headings, tables, lists, blockquotes, links
- **Syntax highlighting** for fenced code blocks (powered by highlight.js)
- **Math typesetting** with KaTeX — inline `$...$` and display `$$...$$`
- **Light & dark mode** — follows your system appearance automatically
- **Sandboxed, offline, and fast** — nothing leaves your Mac
- **Automatic updates** — built-in updater keeps you on the latest version

## Requirements

- macOS 26 (Tahoe) or later

## Installation

1. Download the latest **`MarkdownPreview-x.x.zip`** from the
   [**Releases page**](https://github.com/jjnicolas/MarkdownPreview-releases/releases/latest).
2. Unzip it and drag **`MarkdownPreview.app`** into your **Applications** folder.
3. **Launch the app once.** This registers the Quick Look extension with the
   system. You can quit it afterward — the preview keeps working.
4. Select any Markdown file in Finder and press **Space**.

The app is signed with a Developer ID and notarized by Apple, so it runs without
Gatekeeper warnings.

### Not seeing previews?

Quick Look sometimes needs a nudge after first install:

```sh
qlmanage -r          # reset the Quick Look cache
```

You can also confirm the extension is enabled under
**System Settings → General → Login Items & Extensions → Quick Look**.

## Updating

MarkdownPreview checks for updates automatically and will prompt you when a new
version is available. You can also check manually from the app's menu.

## License

MIT © Julien Nicolas

---

<sub>This repository hosts the public release builds and the Sparkle update feed
(`appcast.xml`) for MarkdownPreview.</sub>
