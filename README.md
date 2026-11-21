# DJ Library Master — releases

**DJ Library Master** cleans, analyzes and organizes your DJ music library on macOS. You confirm each track's identity; the app suggests genre, DJ styles and year from several sources, and only after you have reviewed every track it writes clean tags to your files or to copies in a new folder. It also includes a Metadata Converter, a Duplicate Finder (duplicates go to the macOS Trash) and an optional account for the DJLM Community.

It is free. Version **1.0.0** is the first version of the new DJ Library Master; the old 0.6.x series is retired.

## Download & install

1. Download **`DJ_Library_Master_<version>.dmg`** from the [latest release](../../releases/latest).
2. Open the DMG and drag **DJ Library Master** into **Applications**.
3. Open the app.

> **First start: "Open Anyway".** The app is not yet notarized by Apple, so macOS may block the first start. If it does:
> **System Settings → Privacy & Security → Open Anyway**. Then open the app again.
> You only need to do this once.

**Requirements:** macOS 13 Ventura or later, on Apple Silicon or Intel. Everything the app needs is inside it: no Python, no Homebrew, no extra downloads.

## Updates

The app checks this page for new versions when it starts. It **asks you** before downloading anything, verifies the developer's signature and installs the update by itself.

You can turn the check off in **Settings → Updates**.

## Feedback

- **In the app:** Settings → Support. Crash and error reports are sent only after you have seen their full content and pressed Send; each one gets a reference code (R-XXXXX-XXXXX).
- **On GitHub:** open an [issue](../../issues). Include the reference code if you have one. Never post passwords or tokens.

## What each release contains

| File | What it is |
|---|---|
| `DJ_Library_Master_<version>.dmg` | the app, for a first install |
| `DJ_Library_Master_<version>.zip` | the same app as a zip |
| `djlm-app-<version>.zip` | the update package the app downloads by itself |
| `latest.json` | version, notes, checksum and Ed25519 signature |
| `SOURCES.md`, `SHA256SUMS` and the source archives | the unmodified source code of the LGPL / MPL components (Qt, PySide6, FFmpeg, Chromaprint, certifi) |

This repository holds only the published packages.

© SWEV Development & Graphics · [swev.gr](https://swev.gr) · info@swev.gr
