# Orchard development downloads

Download the current **[Apple development prerelease](https://github.com/moztopia/orchard-releases/releases/tag/apple)**, or [browse releases](https://github.com/moztopia/orchard-releases/releases).

Read the release notes before downloading the APK from **Assets**. GitHub's automatic source ZIP/tar downloads are metadata archives, not the application.

These are development builds for disposable test accounts. The APK uses a development signing identity and the developer test backend; it is not a production or app-store release. Backend availability depends on the existing developer services and tunnel. Publication does not deploy a server or establish device/sign-in acceptance.

Each cut records its exact source version/commit, Android build/package, signing-certificate fingerprint, SHA-256 checksum, backend and known limitations. **Apple** is the human-selected rolling release name; a successful later cut replaces that slot's payload after verification. Numeric application-source tags remain immutable.

Install a downloaded APK using Android's normal prompts. Updates need the same package/signing identity and a compatible build number. Do not uninstall or clear app data merely to bypass an update error; report it first.

This repository contains public download guidance and release assets only. Application source, credentials, signing keys, private user data and raw logs stay out of it. Report download or installation problems in this repository's Issues, without passwords, codes or personal data.
