# Install or update MIDI to TD-3 on macOS

Only download MIDI to TD-3 from this official public repository:

<https://github.com/timefracture/midi-to-td3-downloads/releases>

## Why macOS asks for manual approval

The current MIDI to TD-3 beta is independently distributed and is not yet signed and notarized through Apple's paid Developer Program. When a browser downloads the app, macOS Gatekeeper therefore cannot verify the developer or check the app against Apple's notarization service.

This warning does **not** mean that macOS detected malware. It means Apple has not notarized this build. Manual approval weakens an important macOS safeguard, so only continue when the DMG came from this official repository and its SHA-256 checksum matches the value shown on the release page.

Apple explains this process in [Apple can't check app for malicious software](https://support.apple.com/guide/mac-help/apple-cant-check-app-for-malicious-software-mchleab3a043/mac).

## First installation

1. Download the newest `MIDI.to.TD-3_*_universal.dmg` from the official [Releases page](https://github.com/timefracture/midi-to-td3-downloads/releases).
2. Optional but recommended: compare the DMG's SHA-256 checksum with the checksum printed on its release page.
3. Open the DMG and drag **MIDI to TD-3** into **Applications**.
4. Open **MIDI to TD-3** from the Applications folder.
5. If macOS says Apple could not verify that the app is free of malware, close that message.
6. Open **Apple menu → System Settings → Privacy & Security**.
7. Scroll to **Security** and click **Open Anyway** beside the MIDI to TD-3 message.
8. Authenticate with your Mac password or Touch ID, then confirm **Open**.

The **Open Anyway** option normally appears only after you have tried to open the installed app and remains available for about one hour. After approval, that particular build opens normally.

## Major upgrade: in-app updates

The current beta can install updates itself. Normal beta updates no longer require manually downloading another DMG and replacing the application:

1. When **UPDATE T-X.Y** appears at the top of the app, click it.
2. Review the version and release notes, then choose **INSTALL & RESTART**.
3. Keep the app open while it downloads, verifies, and installs the update. It restarts automatically.

While a beta is current it has no fixed expiry. When a newer official release is published, older compatible versions have 14 days to update by default. The release description may announce a different grace period. After the displayed deadline, the update screen cannot be dismissed and the app remains locked until a newer signed version is installed. A deadline the app has already seen remains cached during network outages.

If automatic installation fails, use **MANUAL DOWNLOAD**, quit the app, open the downloaded DMG, and drag **MIDI to TD-3** into **Applications**. When Finder asks, choose **Replace**. A manually downloaded replacement may require **Open Anyway** again.

Replacing the application does not delete MIDI files, saved `.seq` files, SynthTribe backups, or patterns stored on a connected TD-3. Nevertheless, make a complete SynthTribe backup before using experimental direct pattern transfer.

## If Open Anyway is not visible

- Confirm that you dragged the app to **Applications** instead of running it from the DMG.
- Try to open the copy in **Applications** once, then return immediately to **System Settings → Privacy & Security**.
- Confirm that the blocked app named by macOS is **MIDI to TD-3**.
- Download a fresh copy only from this official repository if the file or source is uncertain.

Do not use Terminal commands or third-party tools that remove quarantine protections globally.

## Support development

If MIDI to TD-3 is useful to you, please consider [supporting continued development on Ko-fi](https://ko-fi.com/timefracturetechno). Follow [@timefracture.techno on Instagram](https://www.instagram.com/timefracture.techno/) for release news and Windows 11 development updates.
