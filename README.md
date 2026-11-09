<div align="center">
  <img src="findex-icon.png" width="128" height="128" alt="Findex icon" />
  <h1>Findex</h1>
  <p><b>A fast, extensible file explorer for macOS.</b></p>
  <p>
    <a href="https://github.com/serfom256/findex-downloads/releases/latest/download/Findex-macos.dmg">⬇&nbsp;&nbsp;Download for macOS (Apple Silicon)</a>
  </p>
  <p><sub>Current version: 0.4.0 · Free beta</sub></p>
</div>

---

## What is Findex?

Findex is a file explorer for macOS built around a dedicated Rust search engine and a
plugin system. It lets you search, preview and organise local, archived, remote and
mobile files from a single window.

## Features

- **Instant search** over file names *and* contents, with typo tolerance, path-segment
  matching and correction for text entered in the wrong keyboard layout.
- **Archives as folders** — browse, preview, extract from, and add into `.zip`, `.tar`,
  `.7z` and `.rar` in place. Documents, images, audio and video can be previewed inside an
  archive without extracting it first.
- **Remote and mobile storage** — connect to SFTP and FTP servers and to Android devices
  (MTP), all browsed within the application, with nothing extra to install.
- **Built-in previews** — images, audio and video (with custom playback controls), PDF,
  Word and Excel documents, and text and source code — in a split view you can page through
  with the arrow keys.
- **Command palette** (`⌘K`) — jump to any file, folder or action with fuzzy matching and
  your recent locations ranked first.
- **Themes and plugins** — several built-in themes, including the new **Mint** theme, plus
  sandboxed JavaScript plugins to extend the application.
- **Dual panes, tabs** and off-thread processing keep the interface responsive.

## Installation

1. Download **[Findex-macos.dmg](https://github.com/serfom256/findex-downloads/releases/latest/download/Findex-macos.dmg)** and open it.
2. Drag **Findex** into your **Applications** folder.
3. On first launch, right-click the app → **Open** → **Open** again. This beta is not yet
   notarized by Apple, so macOS asks for confirmation only this once.

Alternatively, clear the quarantine flag from the terminal:

```sh
xattr -cr /Applications/Findex.app
```

## Requirements

Apple Silicon (M1 and later), macOS 12 or newer.

## Links

- 🌐 Website and live demo: https://findexapp.pages.dev
- This repository hosts the downloads only; it contains no source code.

---

© 2026 · Free beta.
