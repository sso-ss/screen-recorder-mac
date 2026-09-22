# screen-recorder-mac

Download **Screen**, a screen recording app for macOS.

**Newest test build: [Screen 0.1.2, build 3](https://github.com/sso-ss/screen-recorder-mac/releases/tag/v0.1.2)**

[Download for Apple Silicon](https://github.com/sso-ss/screen-recorder-mac/releases/download/v0.1.2/Screen-share-0.1.2-build3.zip)

Version 0.1.2 is marked as a prerelease for testing. GitHub's **Latest** badge still points to 0.1.1; use the link above for the newest test build.

![Screen interface showing the recording preview and audio, webcam, quality, and cursor settings](screen-interface.png)

This is the download-only repository for Screen. It contains installation instructions and packaged app releases, not the app's source code or development project. The installed app is named **Screen**.

## What It Can Do

Use Screen to record app demos, walkthroughs, tutorials, and presentations on your Mac.

- **Record your screen** with a choice of 30 or 60 FPS.
- **Capture audio** from your microphone, your Mac's system audio, or both.
- **Add a webcam overlay** with adjustable size and corner placement.
- **Highlight clicks with smart zoom** that automatically zooms in on clicked areas in your exported video.
- **Choose recording backgrounds**, including the new Prism, Lagoon, Ember, and Midnight presets.
- **Make your cursor easier to follow** with cursor visibility, size controls, and click highlights.
- **Preview videos** inside the app, including recordings and imported video files.
- **Save recordings as MOV files** to share or use in your preferred video editor.

This is a test build. Recording behavior can vary by device and macOS version; make a short test recording before capturing anything important.

Version 0.1.2 improves repeated-click zoom: nearby clicks extend the hold, distant clicks pan to the new target, and unfinished zoom-outs are interrupted from the current view. Smart zoom remains experimental; preview your exported recording before sharing.

## Requirements

- An Apple Silicon Mac (M1 or newer). This build does not support Intel Macs.
- macOS 13 Ventura or later.

## Download and Install

1. Open the [0.1.2 test release](https://github.com/sso-ss/screen-recorder-mac/releases/tag/v0.1.2).
2. Download **Screen-share-0.1.2-build3.zip** under **Assets**, not GitHub's automatically generated source code archives.
3. Double-click the ZIP to extract **Screen.app**.
4. Move **Screen.app** to your **Applications** folder and open it.

## macOS Security Warning

This is a development build shared for testing. It is not notarized by Apple, so macOS may block it on first launch.

Only proceed if you trust the person who shared this app:

1. Try opening **Screen** once.
2. Open **System Settings > Privacy & Security**.
3. Find the message about Screen and click **Open Anyway**, if available.
4. Confirm the macOS prompt.

Do not disable macOS security protections. If no override is available or the app still will not open, report the exact message to the person who shared it.

## Permissions

Allow **Screen Recording** when prompted. On newer macOS versions, this setting may be called **Screen & System Audio Recording**.

Microphone and camera features also require **Microphone** and **Camera** access. You can manage these permissions in **System Settings > Privacy & Security**. Quit and reopen Screen if macOS asks you to.

## Hotkey Guide

These shortcuts are active during recording:

| Shortcut | Action | Where it works |
| --- | --- | --- |
| Control + Z | Toggle manual zoom | System-wide, including while another app is focused |
| Control + Space | Pause or resume recording | System-wide, including while another app is focused |
| Escape | Stop recording | System-wide |
| Z | Toggle manual zoom | When Screen receives keyboard input |
| Space | Pause or resume recording | When Screen receives keyboard input |

**Watch for shortcut conflicts:** Control + Space may also be used to switch keyboard languages. Plain Space can accidentally pause a recording while Screen is focused, and Escape can stop recording when you intended to dismiss something in another app. Use the toolbar's Play button to resume a paused recording.

Manual zoom toggles take priority over automatic click zoom for that recording. These shortcuts control the camera zoom, not macOS Undo.

When a recording preview is ready, **Command + S** opens the Save dialog in Screen. To start recording, use the app's recording controls; Command + Shift + 2 is not connected to a working recording action in this build.

## Updates and Feedback

To update, quit Screen, download a newer release, and replace the app in Applications.

Report problems through this repository's **Issues** section. Include your macOS version, Mac model, release version, and what happened. Remove private information from screenshots and recordings before sharing them.