# Scriptlane releases

An original Android word processor powered by a native Rust document engine. Edit DOCX, text and HTML offline with touch formatting, tables, pictures, comments, tracked text changes, draft recovery and Android PDF printing.

Download the universal APK from the [latest release](https://github.com/Benighter/Scriptlane-Releases/releases/latest). It supports Android 8 or later on ARM64, ARM32 and x86_64. Runtime verification currently covers the Android 16 x86_64 emulator.

Scriptlane checks for newer versions when opened, when resumed, and every five minutes while foregrounded. A review notice includes release notes. Downloads are verified, the working draft is protected, and Android asks before installation. The original local 0.1.0 build needs a one-time installation of 0.1.1 to enable this channel.

This is a mobile editing preview. Complete Microsoft Word feature/settings parity and exact Word pagination are not included. Complex documents should be reviewed against their originals. Scriptlane is independent of Microsoft and contains no Microsoft implementation code or visual assets.

This repository contains public release artifacts and update metadata only. Application source is maintained in the private Scriptlane repository. Third-party notices are included under Settings and attached to each release. Signing keys and personal documents are never published here.

Stable update manifest: [android-update.json](https://github.com/Benighter/Scriptlane-Releases/releases/latest/download/android-update.json).
