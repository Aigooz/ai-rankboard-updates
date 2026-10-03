Update channel for AI Rankboard.

- app-update.json: Android/iOS update manifest
- app-release.apk: signed release APK

The Android app checks the manifest URL and downloads the APK after SHA-256 verification.
The iOS app checks the manifest for an update notice and opens the signed install source; iOS cannot silently install an arbitrary IPA.
