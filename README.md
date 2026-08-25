# MIDI to TD-3 — Official Downloads

Official beta installers for **MIDI to TD-3** by **timefracture**.

Instagram: [@timefracture.techno](https://www.instagram.com/timefracture.techno/) · **[Support development on Ko-fi](https://ko-fi.com/timefracturetechno)**

MIDI to TD-3 converts Standard MIDI files into Behringer TD-3 and TD-3-MO patterns. It can save SynthTribe-compatible `.seq` files and experimentally write patterns directly to a connected TD-3 or TD-3-MO.

MIDI to TD-3 is independently developed. If it saves you time or helps your music, please consider [buying timefracture a coffee on Ko-fi](https://ko-fi.com/timefracturetechno). Support helps fund continued development, testing, and the upcoming Windows version.

## Download

Download the current installer from the official **[MIDI to TD-3 T-1.17 release page](https://github.com/timefracture/midi-to-td3-downloads/releases/tag/T-1.17)**.

**T-1.17 is the only supported and available public beta.** Older builds are intentionally no longer distributed. Do not install, mirror, or redistribute unofficial older builds.

## Supported systems

| System | Availability | Installer |
| --- | --- | --- |
| Mac with an Intel processor | **Available now** | Universal macOS DMG |
| Mac with an Apple M-series processor (Apple Silicon) | **Available now** | Universal macOS DMG |
| Windows 11 | **Not available yet** | In development |

The same universal macOS DMG supports both Intel Macs and Apple Silicon Macs, including M1, M2, M3, M4 and later M-series processors. **macOS for Intel Macs is now supported.** A native Windows 11 version is being worked on, but it is not ready or available yet.

## Feature roadmap

The currently planned development order is:

1. **Windows 11 support** — build, test and publish a native Windows version with the same core conversion and TD-3 functionality as the Mac version.
2. **32-step sequences** — extend the current 16-step limit by splitting and flashing a 32-step sequence across two TD-3 pattern banks.

These are planned features and are not included in the current beta downloads. Roadmap details may be refined during hardware testing.

## Installing or updating on macOS

The current independent beta is not yet signed and notarized through Apple's paid Developer Program. macOS may therefore say that Apple could not verify the app is free of malware. This means Apple has not notarized the build; it does not mean macOS detected malware.

After copying the app to **Applications** and attempting to open it once, go to **Apple menu → System Settings → Privacy & Security**, scroll to **Security**, and click **Open Anyway**. Only approve a DMG downloaded from this repository, and compare its SHA-256 checksum with the release page.

Read the complete step-by-step guide before installing or replacing a beta: **[Install or update MIDI to TD-3 on macOS](MACOS_INSTALLATION.md)**.

## Major upgrade: in-app updater

The current T-1.17 beta can download, verify, install, and restart into a newer beta directly from inside the app. This is a major upgrade to the release workflow: normal beta updates no longer require manually downloading a new DMG and replacing the application.

A beta remains usable while it is the newest official release. Publishing a newer release starts an update window for compatible older versions: **14 days by default**. The release page may announce a different period with a visible `Update grace period: N days` line. After the displayed deadline, the update becomes mandatory before normal use can continue. A policy the app has already observed remains cached during network outages.

## Support development

MIDI to TD-3 is offered as an independent beta. Your support helps make continued macOS improvements, Windows 11 support, broader hardware testing, and future features possible.

**[Support MIDI to TD-3 on Ko-fi](https://ko-fi.com/timefracturetechno)** and follow **[@timefracture.techno on Instagram](https://www.instagram.com/timefracture.techno/)** for development news.

## Before using direct TD-3 transfer

This is experimental beta software. Make a complete backup of your TD-3 or TD-3-MO with SynthTribe before writing patterns. Direct transfer could overwrite or clear pattern data if something goes wrong.

## Beta distribution terms

Copyright © 2026 timefracture. All rights reserved.

You may download and use these beta builds without charge for personal use and for commercial music production. You may not sell, mirror, redistribute, modify, or repackage the application or its installers. Source code is not included in this downloads repository.

The software is provided without warranty. You use it at your own risk. See the in-app disclaimer before use.

T-1.17 uses the release-relative update policy described above instead of a fixed built-in calendar expiry. Mandatory updates encourage testing and feedback against actively maintained code.
