# WATTY

WATTY is a macOS menu bar app for checking battery charge, power flow, device batteries, and the apps using energy.

## Download

[Download WATTY for macOS 26 or later](https://raw.githubusercontent.com/KrinskyP03/WATTY/main/downloads/WATTY-macOS-preview.zip). The app runs on Apple silicon and Intel Macs.

This preview is ad-hoc signed and has not been notarized by Apple. Gatekeeper may block a downloaded copy. The privileged Low Power Mode helper requires a team-signed build. Installation on a second Mac and end-to-end Tessie login are pending.

## Tesla

Tesla readings are optional and off by default. To enable them, supply your own Tessie token in Settings. WATTY stores it in this Mac’s Keychain and asks Tessie for the latest vehicle state. It does not wake the vehicle or send vehicle commands.

## Verify the download

SHA-256 for the preview ZIP:

```
b5a1bec450fdf5b726eacde0068d2c928b6f90bff09963481c6f5d967e7c5d0a
```
