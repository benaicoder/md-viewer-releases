# MD Viewer — Releases

Installers and auto-update feed for **MD Viewer** (Markdown, PDF, Word, Excel, HTML & JSON viewer for macOS and Windows).

Download the latest version from the [Releases page](https://github.com/benaicoder/md-viewer-releases/releases), or directly:

- [Windows](https://github.com/benaicoder/md-viewer-releases/releases/latest/download/MD-Viewer-win-x64.exe)
- [Mac — Apple Silicon](https://github.com/benaicoder/md-viewer-releases/releases/latest/download/MD-Viewer-mac-arm64.dmg)
- [Mac — Intel](https://github.com/benaicoder/md-viewer-releases/releases/latest/download/MD-Viewer-mac-x64.dmg)

## First launch (builds are not yet code-signed)

- **Windows:** at the SmartScreen prompt click **More info → Run anyway**. Installed copies update themselves automatically.
- **macOS:** Gatekeeper reports downloaded unsigned apps as **"damaged"**. After copying MD Viewer to Applications, run this once in Terminal, then open the app normally:

  ```sh
  xattr -cr "/Applications/MD Viewer.app"
  ```

  Until signed builds ship, macOS updates are manual (download + copy + repeat the command).

> **Note:** the "Source code" links GitHub attaches to each release are automatic archives of *this repository* — which contains only this README. MD Viewer's application source is not published here.
