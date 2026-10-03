# talentpilot-releases

This repository only holds **build artifacts** for the TalentPilot mobile app. It contains no source code.

- **Releases** – web bundle zips (`bundle-<version>.zip`) and Android APKs (`talentpilot-<versionName>-<versionCode>.apk`).
- **`manifest.json`** – served via GitHub Pages at <https://njkr.github.io/talentpilot-releases/manifest.json>. The app reads it to find out whether a newer web bundle or APK is available.

Everything here is written automatically by the build workflow of the (private) app repository. Do not edit by hand, except to roll back: point `manifest.json` at a previous release (see the app repo's `docs/ANDROID_BUILD.md`).
