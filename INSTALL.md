# Install VidPrompt 1.2.2 preview

Requires an Apple silicon Mac with macOS 26.0 or later.

1. [Download VidPrompt.dmg](https://github.com/juniornkanabassi/vidprompt-releases/releases/latest/download/VidPrompt.dmg).
2. Open the disk image and drag **VidPrompt.app** onto the **Applications** shortcut.
3. Eject the disk image, then open VidPrompt from Applications.

## If macOS blocks the first launch

This preview is locally signed, without Apple Developer ID signing or notarisation. Apple has not reviewed it.

1. Try opening VidPrompt once.
2. Open **System Settings > Privacy & Security**. Under Security, choose **Open Anyway** for VidPrompt **if macOS offers it**.
3. Confirm only if you trust the copy you downloaded.

Do not disable Gatekeeper or remove quarantine attributes in Terminal. [Apple explains the risks and these steps](https://support.apple.com/guide/mac-help/open-a-mac-app-from-an-unknown-developer-mh40616/mac).

## First use

1. Open VidPrompt, import a script or choose **New Script**.
2. In **Script settings**, choose **Manual** or **Voice**.
3. Press **Present**, then **Start**. Use **Pause** or **Back to start** as needed.

Manual scrolling needs no microphone or speech download. Voice follows speech on your Mac and may require an internet connection for Apple's speech assets on first use. Allow microphone access for Voice and camera access when using the camera. If Voice cannot get ready, check the connection and permissions, retry, or use Manual. Voice asset download/retry and real camera/microphone combinations still need broader fresh-Mac testing.

Imported Markdown files stay linked both ways with the original. Editing them in VidPrompt edits the original file. Other import formats are converted and are not linked.

## Update and remove

VidPrompt does **not** update itself. Download the latest disk image manually, quit VidPrompt, and replace the app in Applications. Keep a backup of your scripts before updating.

To remove the app, quit it and move it to the Bin. Scripts remain in `~/Library/Application Support/VidPrompt`; recordings default to `~/Movies/VidPrompt`. Removing the app does not delete those files.

The bundled command-line helper is `VidPrompt.app/Contents/Helpers/vidprompt`; it does not need Node. The optional MCP adapter is `Contents/Resources/mcp/vidprompt-mcp.mjs` and needs Node 18 or later. Drag installation does not create a command link or configure an AI host. These optional controls are limited to the same user account on the same Mac.
