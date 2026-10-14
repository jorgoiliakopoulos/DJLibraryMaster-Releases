# DJ Library Master — releases

**DJ Library Master** cleans, analyzes and organizes your DJ music library on macOS: tags, duplicates, decades and genres, file names, DJ software libraries. There is also an optional community database of corrections.

It is free. The current version is a **Public Beta**.

## Download & install

1. Download **`DJ_Library_Master_<version>.dmg`** from the [latest release](../../releases/latest).
2. Open the DMG and drag **DJ Library Master** into **Applications**. If you already have it, choose *Replace*: your library, settings and sign-in are kept.
3. Open the app.

> **First start: "Open Anyway".** This beta is not yet notarized by Apple, so macOS may block the first start. If it does:
> **System Settings → Privacy & Security → Open Anyway**. Then open the app again.
> You only need to do this once.

**Requirements:** macOS 13 Ventura or later, on Apple Silicon or Intel. Everything the app needs is inside it: no Python, no Homebrew, no extra downloads.

## Updates

The app checks this page for new versions when it starts and every 6 hours. It **asks you** before downloading anything. It verifies the developer's signature and installs the update by itself. If an update ever fails to start, the app goes back to the previous version by itself.

You can turn the check off in **Settings → Updates**.

## What each release contains

| File | What it is |
|---|---|
| `DJ_Library_Master_<version>.dmg` | the app, for a first install |
| `DJ_Library_Master_<version>.zip` | the same app as a zip |
| `djlm-app-<version>.zip` | the update package the app downloads by itself |
| `latest.json` | version, notes, checksum and Ed25519 signature |

This repository holds only the published packages.

© SWEV Development & Graphics · [swev.gr](https://swev.gr) · info@swev.gr
