# DroidShell Privacy Policy

Last updated: September 22, 2026

DroidShell is a developer tool for connecting directly to Android devices selected by the user. This policy applies to the DroidShell apps for Apple platforms.

## Data collection

DroidShell does not operate a developer-controlled backend and does not collect, transmit, sell, or share personal data with the developer. The app does not include advertising, analytics, tracking, or account systems.

## Local device communication

When you pair with or connect to an Android device, DroidShell communicates directly with that device over the local network using the Android Debug Bridge protocol. Commands, terminal output, logcat output, installed-app information, and screen-mirroring data are exchanged only with the Android device you select and are processed locally on your Apple device.

Your network provider, operating-system vendor, or the administrator of the selected Android device may process network or device activity independently of DroidShell.

## Data stored on your device

DroidShell may store the following information locally:

- Saved Android device names, addresses, ports, and connection preferences
- Command history and custom command snippets
- Appearance and app preferences
- A cryptographic ADB identity in the Apple Keychain so paired Android devices can recognize your Apple device

Pairing codes are used for the pairing operation and are not intentionally stored by DroidShell. You can keep an individual terminal command out of command history by prefixing it with a space.

Saved devices, command history, and custom snippets can be removed in the app. App-container data can also be removed by deleting the app. Keychain items may persist after app deletion and can be removed with Apple's Keychain management tools.

## Exports, clipboard, and files

DroidShell copies content to the clipboard or creates an export file only after you request that action. Exported content is then handled by the destination and by the operating system according to your choice. Temporary logcat export files are removed by DroidShell after the sharing flow finishes or is dismissed.

## Third-party software

DroidShell includes open-source components used to implement local ADB connectivity and screen mirroring. These components do not add developer-operated analytics or advertising services. License and attribution information is available in this repository.

## Children's privacy

DroidShell is a technical administration tool and is not directed to children. Because the developer does not collect personal data through the app, the developer does not knowingly collect personal data from children through DroidShell.

## Changes

This policy may be updated when DroidShell's functionality or data handling changes. The date at the top identifies the latest version.

## Contact

For privacy questions, contact:

info@emudev.de
