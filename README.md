# Oncore installers

Official compiled installers for Oncore, the Spotify desktop lyrics companion by Juan Escalante.

Application and website source code are private. This repository contains distribution metadata only; no source-code license is granted for Oncore.

## macOS

Apple Silicon, macOS 13 or later. Version 1.5.2. Ad-hoc signed; not Apple-notarized.

[Download DMG](https://github.com/juanescalante0942/oncore-releases/releases/download/mac-v1.5.2/Oncore-1.5.2-mac-arm64.dmg)

With Homebrew installed:

```sh
brew install --cask juanescalante0942/tap/oncore
```

## Windows

Experimental x64 build, version 0.6.2. Unsigned installer.

[Download installer](https://github.com/juanescalante0942/oncore-releases/releases/download/windows-v0.6.2/Oncore-Setup-0.6.2-unsigned-x64.exe)

[WinGet draft submission #490118](https://github.com/microsoft/winget-pkgs/pull/490118) is pending Windows install validation, owner completion of Microsoft’s contributor agreement, and Microsoft review/indexing. Use the direct installer until the package is available in the catalog. The intended package ID is `JuanEscalante.Oncore`.

SHA-256 checksum files accompany each release. Normal operating-system security checks apply. Physical-device release validation is pending.
