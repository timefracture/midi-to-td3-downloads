# MIDI to TD-3 — Official Downloads

Official beta installers for **MIDI to TD-3** by **timefracture**.

Instagram: [@timefracture.techno](https://www.instagram.com/timefracture.techno/)

MIDI to TD-3 converts Standard MIDI files into Behringer TD-3 and TD-3-MO patterns. It can save SynthTribe-compatible `.seq` files and experimentally write patterns directly to a connected TD-3 or TD-3-MO.

## Download

Use the official [`timefracture/midi-to-td3-downloads` Releases page](https://github.com/timefracture/midi-to-td3-downloads/releases) to download the latest installer.

**T-1.12 is the earliest supported and available public beta.** Earlier builds are intentionally not distributed here. Do not install, mirror, or redistribute unofficial older builds.

## Supported systems

| System | Availability | Installer |
| --- | --- | --- |
| Mac with an Intel processor | **Available now** | Universal macOS DMG |
| Mac with an Apple M-series processor (Apple Silicon) | **Available now** | Universal macOS DMG |
| Windows | **Not available yet** | Planned next |

The same universal macOS DMG supports both Intel Macs and Apple Silicon Macs, including M1, M2, M3, M4 and later M-series processors. There is currently no official Windows installer in this repository.

## Feature roadmap

The currently planned development order is:

1. **Windows support** — build, test and publish a native Windows version with the same core conversion and TD-3 functionality as the Mac version.
2. **32-step sequences** — extend the current 16-step limit by splitting and flashing a 32-step sequence across two TD-3 pattern banks.

These are planned features and are not included in the current beta downloads. Roadmap details may be refined during hardware testing.

## Installing or updating on macOS

The current independent beta is not yet signed and notarized through Apple's paid Developer Program. macOS may therefore say that Apple could not verify the app is free of malware. This means Apple has not notarized the build; it does not mean macOS detected malware.

After copying the app to **Applications** and attempting to open it once, go to **Apple menu → System Settings → Privacy & Security**, scroll to **Security**, and click **Open Anyway**. Only approve a DMG downloaded from this repository, and compare its SHA-256 checksum with the release page.

Read the complete step-by-step guide before installing or replacing a beta: **[Install or update MIDI to TD-3 on macOS](MACOS_INSTALLATION.md)**.

## Before using direct TD-3 transfer

This is experimental beta software. Make a complete backup of your TD-3 or TD-3-MO with SynthTribe before writing patterns. Direct transfer could overwrite or clear pattern data if something goes wrong.

## Beta distribution terms

Copyright © 2026 timefracture. All rights reserved.

You may download and use these beta builds without charge for personal use and for commercial music production. You may not sell, mirror, redistribute, modify, or repackage the application or its installers. Source code is not included in this downloads repository.

The software is provided without warranty. You use it at your own risk. See the in-app disclaimer before use.

Each beta has a built-in expiry date. Expiry encourages testers to install current builds and ensures feedback relates to the software currently being developed.
