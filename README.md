# VidPrompt preview downloads

VidPrompt is a native Markdown teleprompter for Mac, with manual scrolling, on-device voice following and a camera workspace.

[Download VidPrompt.dmg](https://github.com/juniornkanabassi/vidprompt-releases/releases/latest/download/VidPrompt.dmg) · [Release notes](https://github.com/juniornkanabassi/vidprompt-releases/releases/latest) · [Installation guide](INSTALL.md)

## Current preview

**Version 1.2.2, build 37.** Requires **Apple silicon (arm64)** and **macOS 26.0 or later**. Intel Macs are not supported by this download.

This is an unnotarised preview, signed with a local development identity rather than an Apple Developer ID. Apple has not reviewed this build. macOS may block the first launch. Follow the conditional **Open Anyway** steps in the installation guide only if you trust this download. Do not disable Gatekeeper or remove quarantine attributes in Terminal.

There is no automatic updater. Download the latest disk image manually to update. Fresh-Mac installation, permissions, voice downloads, and individual camera/microphone combinations have not all been verified. A passing local test suite is not a guarantee for every Mac. Manual mode needs no microphone or speech download; Voice may need Apple speech assets and microphone permission.

The downloaded disk image contains the app, an Applications shortcut and an installation note. It contains no personal script library, recordings or recovery data. This repository publishes download assets and documentation only.

## Download integrity

`VidPrompt.dmg` is **4,125,791 bytes**. SHA-256:

```text
b94363f4aca53e95a89be847321807d00f794921c2ea4b71896ffc56f2c1eccf
```

[SHA256SUMS](SHA256SUMS) records the same checksum. Local verification confirmed the disk-image checksum, app version/build, arm64 app and helper, minimum macOS version, and strict deep code-signature integrity. Signature integrity does not mean Apple notarisation or a malware guarantee.
