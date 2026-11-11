# WATTY

WATTY shows your Mac’s power flow, the apps using energy, and your devices’ battery levels in the menu bar. Connect your Tesla through Tessie to see its battery level and charging status alongside your other devices.

## Download

[Download WATTY for macOS 26 or later](https://raw.githubusercontent.com/KrinskyP03/WATTY/main/downloads/WATTY-macOS-preview.zip). The download includes native builds for Apple silicon and Intel (x86_64). Testing on Intel hardware is still pending.

This preview is ad-hoc signed and has not been notarized by Apple. Gatekeeper may block a downloaded copy. The privileged Low Power Mode helper requires a team-signed build. Installation on a second Mac and end-to-end Tessie login are pending.

## Tesla

Tesla readings are optional and off by default. To enable them, supply your own Tessie token in Settings. Your Mac stores the token in Keychain. WATTY reads the latest vehicle state from Tessie. It does not wake the vehicle or send vehicle commands.

## Verify the download

SHA-256 for the preview ZIP:

```
b5a1bec450fdf5b726eacde0068d2c928b6f90bff09963481c6f5d967e7c5d0a
```
