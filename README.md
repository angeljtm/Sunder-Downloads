# Sunder

A monochrome datamosh video editor for macOS.

## Download

**Get the latest beta from [Releases](https://github.com/angeljtm/Sunder-Downloads/releases).**

Sunder is currently a friends beta for **Apple Silicon Macs (M1 or newer)** running **macOS 14 or newer**.

## Required: FFmpeg

Sunder intentionally does **not** bundle FFmpeg. Install FFmpeg through Homebrew before launching Sunder:

```bash
brew install ffmpeg
```

If you do not have Homebrew yet, install it from [brew.sh](https://brew.sh), then run the command above.

## Install Sunder

1. Open the [Releases page](https://github.com/angeljtm/Sunder-Downloads/releases).
2. Download the newest **Sunder-…-Beta.dmg** file under **Assets**.
3. Open the DMG and drag **Sunder** into **Applications**.
4. Try opening Sunder.
5. Because these friend builds are not Apple-notarized, macOS may block the first launch. Go to **System Settings → Privacy & Security → Open Anyway**, authenticate, and confirm **Open**.

Do **not** disable Gatekeeper globally.

## What to test

Try importing video and music, generating/rerolling a cut, timeline zoom and scrubbing, per-clip effects, rendering, cancelling a render, rerendering, and saving the final MP4.

If something breaks, open a [bug report](https://github.com/angeljtm/Sunder-Downloads/issues/new?template=bug.yml).

## About the source-code download links

GitHub automatically adds **Source code (zip)** and **Source code (tar.gz)** to every release. Those archives contain only this public downloads repository. The Sunder application source is kept in a separate private repository.
