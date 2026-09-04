# Install or update MIDI to TD-3 on Windows

Only download MIDI to TD-3 from the official public repository:

<https://github.com/timefracture/midi-to-td3-downloads/releases>

## Compatibility

- **Windows 11 x64:** tested with installation, MIDI conversion, and direct TD-3 USB transfer.
- **Windows 10 x64:** may run, but is currently untested.
- **Windows ARM64, 32-bit Windows, and Windows 7/8:** unsupported.

## Experimental hardware warning

MIDI to TD-3 is unofficial experimental software and is not made, approved, or supported by Behringer. Its direct USB transfer uses a reverse-engineered, undocumented SynthTribe pattern protocol.

Before transferring anything, make and verify a complete TD-3 or TD-3-MO backup with SynthTribe. A software defect, interrupted connection, firmware difference, or unexpected device response could corrupt or erase one pattern, multiple patterns, or all pattern banks. In the worst case, the device could stop responding or become unusable. The software is provided “as is” and is used entirely at your own risk.

## Installation

1. Download the newest `MIDI.to.TD-3_*_x64-setup.exe` from the official [Releases page](https://github.com/timefracture/midi-to-td3-downloads/releases).
2. Compare the installer's SHA-256 checksum with the checksum printed on its release page.
3. Run the installer.
4. If Microsoft Defender SmartScreen appears, confirm that the filename and source are correct, choose **More info**, and then choose **Run anyway** only if you trust this official download.
5. Open **MIDI to TD-3** from the Start menu.

The SmartScreen warning can appear because this independent beta does not yet have a commercial Windows Authenticode certificate or established download reputation. It does not by itself mean Windows detected malware, but bypassing it weakens an important protection. Do not approve copies from mirrors, direct messages, or unofficial download sites.

## Direct TD-3 transfer

1. Use SynthTribe first to make and verify a complete backup.
2. Close SynthTribe and other MIDI applications so they do not compete for the TD-3 ports.
3. Connect the TD-3 or TD-3-MO directly by USB.
4. Confirm that MIDI to TD-3 displays the detected model and firmware version.
5. Select the exact group, A/B section, and pattern number before writing.
6. Wait until the app reports that the pattern was written and verified.

The optional in-app destination backup saves only the selected slot. It is useful additional protection but is not a replacement for a complete SynthTribe backup.

## In-app updates

When **UPDATE T-X.Y** appears, open it and select **INSTALL & RESTART**. The app downloads the official installer, verifies it with timefracture's embedded public update key, installs it, and restarts.

If automatic installation fails, use **MANUAL DOWNLOAD**, close the app, and run the current installer from the official Releases page.

## Known `.seq` limitation

Loading and restoring `.seq` files currently supports the established 146-byte TD-3 format. Some TD-3-MO SynthTribe exports use 152 bytes and are not yet accepted. MIDI conversion and direct transfer of the app's supported pattern remain available for a detected TD-3-MO.

## Support development

If MIDI to TD-3 is useful to you, please consider [supporting continued development on Ko-fi](https://ko-fi.com/timefracturetechno). Follow [@timefracture.techno on Instagram](https://www.instagram.com/timefracture.techno/) for release news.
