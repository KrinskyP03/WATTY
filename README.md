# WATTY

WATTY shows your Mac’s power flow, the apps using energy, and your devices’ battery levels in the menu bar. Connect your Tesla through Tessie to see its battery level and charging status alongside your other devices.

## Download

[Download WATTY for macOS 26 or later](https://raw.githubusercontent.com/KrinskyP03/WATTY/main/downloads/WATTY-macOS-preview.zip). The download includes native builds for Apple silicon and Intel (x86_64). Testing on Intel hardware is still pending.

This preview is ad-hoc signed and has not been notarized by Apple. Gatekeeper may block a downloaded copy. Installation on a second Mac and end-to-end Tessie login are pending.

## Open WATTY on your Mac

1. Unzip `WATTY-macOS-preview.zip`, move **WATTY.app** to **Applications**, then double-click it. Look for WATTY in the menu bar.
2. If macOS says Apple can’t verify WATTY, dismiss the alert. If you trust the download and its [checksum](#verify-the-download) matches, open **System Settings → Privacy & Security**.
3. Under **Security**, find the message about WATTY, click **Open Anyway**, and confirm when prompted. This option appears after the first launch attempt and is available for about an hour. If macOS reports malware or a damaged app, stop there. [Apple’s guide to opening apps safely](https://support.apple.com/en-us/102445)

## Low Power Mode

On supported Macs, you can use WATTY’s Low Power Mode switch with administrator approval. This preview uses the macOS password prompt when you change the setting. A future build signed with the publisher’s Apple Developer ID can support a helper that you approve once.

## Tesla

Tesla readings are optional and off by default. To enable them, supply your own Tessie token in Settings. Your Mac stores the token in Keychain. WATTY reads the latest vehicle state from Tessie. It does not wake the vehicle or send vehicle commands.

## Verify the download

SHA-256 for the preview ZIP:

```
b5a1bec450fdf5b726eacde0068d2c928b6f90bff09963481c6f5d967e7c5d0a
```
