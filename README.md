# Oncore installers

Official compiled installers for Oncore, the Spotify desktop lyrics companion by Juan Escalante.

Application and website source code are private. This repository contains distribution metadata only; no source-code license is granted for Oncore.

## macOS

Apple Silicon, macOS 13 or later. Version 1.7.0. Ad-hoc signed; not Apple-notarized.

[Download DMG](https://github.com/juanescalante0942/oncore-releases/releases/download/mac-v1.7.0/Oncore-1.7.0-mac-arm64.dmg)

With Homebrew installed:

```sh
brew install --cask juanescalante0942/tap/oncore
```

## Windows

Experimental x64 build, version 0.8.0. Unsigned installer.

[Download installer](https://github.com/juanescalante0942/oncore-releases/releases/download/windows-v0.8.0/Oncore-Setup-0.8.0-x64.exe)

[WinGet draft submission #490118](https://github.com/microsoft/winget-pkgs/pull/490118) is pending Windows install validation, owner completion of Microsoft’s contributor agreement, and Microsoft review/indexing. Use the direct installer until the package is available in the catalog. The intended package ID is `JuanEscalante.Oncore`.

SHA-256 checksum files accompany each release. Normal operating-system security checks apply. Physical-device release validation is pending.

## Interactive setup and presets

Mac 1.7.0 and Windows 0.8.0 include three-step setup: Your look, Your space, and Your music. A large preview accompanies preset choices; the desktop sample has a temporary red outline and Your lyrics label. Use Find my overlay to bring it forward, drag/resize/place it, and connect Spotify when ready. Finish saves; Skip setup discards previews; closing setup preserves a resumable draft. First launch opens setup even when appearance preferences already exist. Reopen Getting started from the app menu or system tray.

Ten built-in presets include Dev’s Pick (Juan’s saved look), Focus, Glass, Cinema, and Terminal. Older custom presets are preserved under a unique “(saved)” name if they collide with a new built-in.
