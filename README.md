# Workbench | Visible Context & AI Agents

**See the context. Direct the AI. Own the outcome.**

**보이는 맥락과 AI, 그 이상의 효율**

Bring your materials into view. Choose your AI and tools. Review the results as you work.

Workbench by **JoSH** brings your files, AI conversations and results together in Obsidian. Keep the context in sight, guide the work and inspect the outcome in the same workspace.

자료를 펼쳐 놓고, AI와 도구를 골라, 결과를 직접 확인하며 일하는 작업대.

Workbench는 Obsidian의 파일 트리와 문서 뷰어를 중심으로 자료·AI 대화·작업 결과를 한곳에서 이어 줍니다. **Workbench에서 자료를 열고 AI와 작업하세요.**

This repository distributes installers and signed update assets. It does not contain the development checkout, personal Vaults, credentials or signing private keys.

## Download

[Latest release and installation files](https://github.com/coolwindjo/workbench-releases/releases/latest)

- Windows: download the `Windows-x64-Setup.exe` asset.
- macOS: download the `macOS-universal.zip` asset, extract it and open `Workbench Installer.app`.
- Read `INSTALL-README.txt` and check `SHA256SUMS.txt` in the release assets.

Close Obsidian, run the installer, accept the license and select an existing Vault. Obsidian 1.15+ and your own supported model CLI/account are required. Model subscriptions and third-party community plugins are not bundled.

## Updates

Versions before 0.16 require a one-time installer upgrade. From 0.16 onward, a newer verified stable release displays an **Update available** icon in Workbench. Click it to read release notes and start the update. The license is accepted at first installation; starting an update renews that agreement and the use period. Finish active requests, save notes and send or copy/clear unsent prompts first. After file replacement, the current Obsidian window reloads.

Updates preserve existing notes, plugin settings and saved Sessions. The icon is hidden when the installed version is already current.

The app verifies an Ed25519-signed release feed and SHA-256 hashes. This distribution signature is separate from operating-system code signing.

## License and release status

Use requires agreement to the license included with the installer/update. Each successful installation or update grants 30 days (720 hours). Expiry blocks Workbench functions, while notes and saved Sessions remain intact. This is a local usage gate, not tamper-proof DRM.

Windows installation and update transaction tests passed. macOS package structure was checked; real Mac runtime testing is still pending. Installers are currently unsigned and the macOS app is not notarized.

GitHub's automatically generated Source code archives contain this distribution repository's documentation, not the plugin development source tree. Choose the named installer assets above.
