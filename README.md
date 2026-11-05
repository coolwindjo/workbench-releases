# Workbench

Workbench by **JoSH**, an Obsidian desktop plugin for AI conversations with local notes and Sources.

This repository distributes installers and signed update assets. It does not contain the development checkout, personal Vaults, credentials or signing private keys.

## Download

[Latest release and installation files](https://github.com/coolwindjo/workbench-releases/releases/latest)

- Windows: download the `Windows-x64-Setup.exe` asset.
- macOS: download the `macOS-universal.zip` asset, extract it and open `Workbench Installer.app`.
- Read `INSTALL-README.txt` and check `SHA256SUMS.txt` in the release assets.

Close Obsidian, run the installer, accept the license and select an existing Vault. Obsidian 1.15+ and your own supported model CLI/account are required. Model subscriptions and third-party community plugins are not bundled.

## Updates

Versions before 0.16 require a one-time installer upgrade. From 0.16 onward, a newer verified stable release displays an **Update available** icon in Workbench. Click it to read release notes, accept the license and update. Finish active requests, save notes and send or copy/clear unsent prompts first. After file replacement, the current Obsidian window reloads.

Updates preserve existing notes, plugin settings and saved Sessions. The icon is hidden when the installed version is already current. The first published release is 0.16.0; its icon will appear only when a later verified version is published.

The app verifies an Ed25519-signed release feed and SHA-256 hashes. This distribution signature is separate from operating-system code signing.

## License and release status

Use requires agreement to the license included with the installer/update. Each successful installation or update grants 30 days (720 hours). Expiry blocks Workbench functions, while notes and saved Sessions remain intact. This is a local usage gate, not tamper-proof DRM.

Windows installation and update transaction tests passed. macOS package structure was checked; real Mac runtime testing is still pending. Installers are currently unsigned and the macOS app is not notarized.

GitHub's automatically generated Source code archives contain this distribution repository's documentation, not the plugin development source tree. Choose the named installer assets above.
