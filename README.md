# Abay Download Manager

Download **Abay Download Manager Developer Preview** from [GitHub Releases](https://github.com/ayeletare21/abay-download-manager-releases/releases).

This repository hosts distribution packages and release notes only. The Developer Preview is for testing and is not the final stable 1.0.0 release.

## Supported platforms

- **Windows 10/11 x64** — portable Developer Preview.
- **macOS 13+ on Apple Silicon (arm64)** — Developer Preview; Intel Macs are not supported.

Extract the application ZIP before use. On Windows, keep the application in a permanent folder. On macOS, move Abay Download Manager.app to Applications if desired. Start Abay and run Browser Integration setup/repair when required.

**The macOS Developer Preview is not yet notarized.** Developer ID signing and Gatekeeper approval are not claimed.

## Chrome extension: Developer Mode installation

Chrome Web Store approval is pending. Until approval, install the separate extension manually:

1. Download `Abay-Chrome-Extension-1.0.0-preview-developer.zip` from [Releases](https://github.com/ayeletare21/abay-download-manager-releases/releases).
2. Extract the ZIP.
3. Open `chrome://extensions`.
4. Enable **Developer mode**.
5. Choose **Load unpacked**.
6. Select the extracted extension folder containing `manifest.json`, not the ZIP.

Expected extension ID: `geljkkdncoiekbhcldckgkplcdmalkpg`.

Keep the extracted extension folder on the computer while using this preview.

## Download flow

Choose quality in the browser overlay → Confirm in Abay → Download.

SHA-256 checksum files are included beside the application and extension ZIPs in each release.
