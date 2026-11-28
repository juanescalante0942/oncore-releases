# Oncore installers

Official compiled installers for Oncore, the Spotify desktop lyrics companion by Juan Escalante.

Application and website source code are private. This repository contains distribution metadata only; no source-code license is granted for Oncore.

## macOS

Apple Silicon, macOS 13 or later. Version 1.8.3. Ad-hoc signed; not Apple-notarized.

[Download DMG](https://github.com/juanescalante0942/oncore-releases/releases/download/mac-v1.8.3/Oncore-1.8.3-mac-arm64.dmg)

With Homebrew installed:

```sh
brew install --cask juanescalante0942/tap/oncore
```

## Windows

Experimental x64 build, version 0.9.2. Unsigned installer.

[Download installer](https://github.com/juanescalante0942/oncore-releases/releases/download/windows-v0.9.2/Oncore-Setup-0.9.2-x64.exe)

[WinGet draft submission #490118](https://github.com/microsoft/winget-pkgs/pull/490118) is pending Windows install validation, owner completion of Microsoft’s contributor agreement, and Microsoft review/indexing. Use the direct installer until the package is available in the catalog. The intended package ID is `JuanEscalante.Oncore`.

SHA-256 checksum files accompany each release. Normal operating-system security checks apply. Physical-device release validation is pending.

## Interactive setup and presets

Mac 1.8.0 and Windows 0.9.0 include three-step setup: Your look, Your space, and Your music. A large preview accompanies preset choices; the desktop sample has a temporary red outline and Your lyrics label. Use Find my overlay to bring it forward, drag/resize/place it, and connect Spotify when ready. Finish saves; Skip setup discards previews; closing setup preserves a resumable draft. First launch opens setup even when appearance preferences already exist. Reopen Getting started from the app menu or system tray.

Ten built-in presets include Dev’s Pick (Juan’s saved look), Focus, Glass, Cinema, and Terminal. Older custom presets are preserved under a unique “(saved)” name if they collide with a new built-in.

## In-app updates

Mac 1.8.0 and Windows 0.9.0 introduce in-app updates. Install one of these versions manually once; future updates can be downloaded and installed inside Oncore. Optional updates allow Later and continued use. Required updates gate affected older versions until they update, with Retry and Quit available. Mac 1.8.1 and Windows 0.9.1 are required updates for earlier updater-enabled versions when they receive the signed policy. Presets and settings are preserved.

Signed update policies and platform feeds live in `updates/`. The private signing keys and application source are never published here. Mac uses Sparkle’s signed feed and archive; Windows verifies its installer against signed policy digests. Actual Sparkle replacement and native Windows upgrade testing remain pending.

## Required settings update — Mac 1.8.1 / Windows 0.9.1

Adds Quick Access, editable slider values, independent song detail colors in every lyric color mode, triple-click locking and in-app support options. Windows Appearance autosaves preserve newer lock changes. The signed policies require Mac 1.8.1 and Windows 0.9.1; older builds without updater support need a manual installation. Existing preferences and placement are kept.

## Mac 1.8.2 — Smooth lyric motion fix

Preserves in-flight transitions when macOS reapplies an unchanged appearance and keeps your Smooth lyric motion choice while battery saver is active. Includes the corrected website URL and first-launch instructions in READ ME FIRST.txt and the app’s Help menu. This update is optional for 1.8.1; the minimum supported version remains 1.8.1.

## Required workspace update — Mac 1.8.3 / Windows 0.9.2

Adds settings search, nine-section Mac navigation with App and Studio, context-sensitive Brat panel controls, free offscreen placement and customizable notch mode. Windows settings now include Quit Oncore. Earlier updater-enabled versions must update after receiving the signed policy. Saved preferences are retained.
