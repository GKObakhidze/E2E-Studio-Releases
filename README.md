# E2E Studio releases

This repository holds the releases of E2E Studio and its official plugins.

- **App releases** (`v1.2.3`): installers for macOS and Windows, plus `update.json` and its signature `update.json.sig`. E2E Studio checks for updates here without a GitHub account. It installs a version only when `update.json` is signed with the E2E Studio key and each installer matches the checksum listed there.
- **Plugin releases** (`plugins-v1.2.3`): jars for the in-app Plugin Store. They are published as prereleases, so they never become the latest app release.

Releases are published by the E2E Studio team; this repository contains no source code.
