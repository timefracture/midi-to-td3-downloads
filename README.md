# MIDI to TD-3 — Official Downloads

Official beta installers for **MIDI to TD-3** by **timefracture**.

Instagram: [@timefracture.techno](https://www.instagram.com/timefracture.techno/) · **[Support development on Ko-fi](https://ko-fi.com/timefracturetechno)**

> ⚠️ **UNOFFICIAL, EXPERIMENTAL SOFTWARE — USE AT YOUR OWN RISK**
>
> MIDI to TD-3 is independent community software and is not made, approved, or supported by Behringer. Direct USB transfer is based on reverse engineering of SynthTribe's undocumented TD-3 pattern protocol, not an official Behringer specification.
>
> Before using direct USB transfer, make and verify a complete backup with SynthTribe. A software defect, interrupted connection, firmware difference, or unexpected device response could corrupt or erase one pattern, multiple patterns, or all pattern banks. In the worst case, a TD-3 or TD-3-MO could stop responding or become unusable.
>
> The software is provided “as is.” To the maximum extent permitted by law, timefracture and contributors accept no liability for data loss, equipment damage, lost income, or related losses.

MIDI to TD-3 converts Standard MIDI files into Behringer TD-3 and TD-3-MO patterns. It can save SynthTribe-compatible `.seq` files and experimentally write patterns directly to a connected TD-3 or TD-3-MO.

If it saves you time or helps your music, please consider [buying timefracture a coffee on Ko-fi](https://ko-fi.com/timefracturetechno). Support helps fund continued development and hardware testing.

## Download

Download the current installers from the official **[MIDI to TD-3 T-1.18 release page](https://github.com/timefracture/midi-to-td3-downloads/releases/tag/T-1.18)**.

**T-1.18 is the only supported and available public beta.** Older builds are intentionally no longer distributed. Do not install, mirror, or redistribute unofficial older builds.

## Supported systems

| System | Availability | Installer |
| --- | --- | --- |
| Mac with an Intel processor | **Available and tested** | Universal macOS DMG |
| Mac with an Apple M-series processor | **Available and tested** | Universal macOS DMG |
| Windows 11 x64 | **Available and tested** | Windows `.exe` |
| Windows 10 x64 | **May run, but untested** | Windows `.exe` |
| Windows ARM64, 32-bit Windows, Windows 7/8 | **Unsupported** | None |

The same universal macOS DMG supports Intel and Apple Silicon. The Windows installer is a native x64 build tested on Windows 11 with MIDI conversion and direct TD-3 USB transfer. Windows 10 x64 may run, but has not passed real-device testing and must be treated as unverified.

## Installation

- **macOS:** [Read the complete macOS installation and update guide](MACOS_INSTALLATION.md), including **System Settings → Privacy & Security → Open Anyway** and checksum verification.
- **Windows:** [Read the complete Windows installation and update guide](WINDOWS_INSTALLATION.md), including Microsoft Defender SmartScreen and checksum guidance.

## In-app updater

T-1.18 can download, verify, install, and restart into a newer beta directly from inside the app on macOS and Windows.

A beta remains usable while it is the newest official release. Publishing a newer release starts an update window for compatible older versions: **14 days by default**. The release page may announce a different period with a visible `Update grace period: N days` line. After the deadline, the update becomes mandatory. A policy the app has already observed remains cached during network outages.

## Known `.seq` limitation

Loading and restoring `.seq` files currently supports the established 146-byte TD-3 format. Some TD-3-MO SynthTribe exports use a 152-byte format. Those files are not accepted until their additional fields have been identified and handled safely. This does not prevent converting MIDI and transferring the app's supported pattern to a detected TD-3-MO.

## Feature roadmap

1. **32-step sequences** — split and flash a 32-step sequence across two TD-3 pattern banks.
2. **Broader platform and hardware testing** — expand verified Windows versions, display configurations and TD-3/TD-3-MO firmware versions, and investigate native Linux packaging.

Roadmap details may change during testing.

## Support development

**[Support MIDI to TD-3 on Ko-fi](https://ko-fi.com/timefracturetechno)** and follow **[@timefracture.techno on Instagram](https://www.instagram.com/timefracture.techno/)** for development news.

## Beta distribution terms

Copyright © 2026 timefracture. All rights reserved.

You may download and use these beta builds without charge for personal use and for commercial music production. You may not sell, mirror, redistribute, modify, or repackage the application or its installers. Source code is not included in this downloads repository.

The software is provided without warranty and is used at your own risk. T-1.18 uses the release-relative update policy described above instead of a fixed built-in calendar expiry.
