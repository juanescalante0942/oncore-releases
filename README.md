# Oncore installers

Official compiled installers for Oncore, the Spotify desktop lyrics companion by Juan Escalante.

Application and website source code are private. This repository contains distribution metadata only; no source-code license is granted for Oncore.

## macOS

Apple Silicon, macOS 13 or later. Version 1.6.0. Ad-hoc signed; not Apple-notarized.

[Download DMG](https://github.com/juanescalante0942/oncore-releases/releases/download/mac-v1.6.0/Oncore-1.6.0-mac-arm64.dmg)

With Homebrew installed:

```sh
brew install --cask juanescalante0942/tap/oncore
```

## Windows

Experimental x64 build, version 0.7.0. Unsigned installer.

[Download installer](https://github.com/juanescalante0942/oncore-releases/releases/download/windows-v0.7.0/Oncore-Setup-0.7.0-x64.exe)

[WinGet draft submission #490118](https://github.com/microsoft/winget-pkgs/pull/490118) is pending Windows install validation, owner completion of Microsoft’s contributor agreement, and Microsoft review/indexing. Use the direct installer until the package is available in the catalog. The intended package ID is `JuanEscalante.Oncore`.

SHA-256 checksum files accompany each release. Normal operating-system security checks apply. Physical-device release validation is pending.

## Interactive setup and presets

Mac 1.6.0 and Windows 0.7.0 include four-step interactive setup with a separate sample overlay. Try presets, adjust text and backgrounds, drag/resize/place the overlay, and connect Spotify when ready. Finish saves; Skip setup discards previews. Reopen Getting started from the app menu or system tray.

Ten built-in presets include Dev’s Pick (Juan’s saved look), Focus, Glass, Cinema, and Terminal. Older custom presets are preserved under a unique “(saved)” name if they collide with a new built-in.
