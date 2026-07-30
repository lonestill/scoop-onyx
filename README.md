# Onyx Launcher Scoop bucket

This bucket provides the official portable Windows build of
[Onyx Launcher](https://lonestill.github.io), an open-source Minecraft launcher.

## Install

```powershell
scoop bucket add onyx https://github.com/lonestill/scoop-onyx
scoop install onyx/onyx-launcher
```

## Update

```powershell
scoop update
scoop update onyx-launcher
```

The manifest downloads release assets directly from the
[Onyx Launcher repository](https://github.com/lonestill/onyx-launcher/releases).
Windows builds are currently unsigned. Verify the published SHA-256 checksum if
SmartScreen displays a warning.
