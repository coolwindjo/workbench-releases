Workbench 0.19.14 | JoSH

WINDOWS: Run Workbench-0.19.14-Windows-x64-Setup.exe.
MACOS: Extract Workbench-0.19.14-macOS-universal.zip and open Workbench Installer.app.

Close Obsidian first. Review the license, select an existing Vault, then install.
The installer preserves settings and notes, backs up an existing installation,
and adds Workbench to the community-plugin list only when selected.
Restricted mode is never changed automatically. Restart Obsidian afterwards.

IN-APP UPDATES: After this one-time installer bootstrap, Workbench checks its
signed stable GitHub release feed at startup and every minute while open, if
automatic checks are enabled. A newer verified version shows an Update available
icon. Click it to update and renew your existing license agreement. The current
Obsidian window reloads after file replacement.
Finish active requests, save notes and send or copy/clear unsent prompts first.
The feed must be published before remote checks work. Older 0.15 installations
require this installer once because they do not contain the update checker.

License: 30 days (720 hours) from publisher-approved activation during setup/update.
Enter the publisher-issued key in Workbench license settings. Reinstalling alone
does not renew. Whitelisted customers may renew without a new app version. Expiry blocks Workbench functions, not your notes.
An offline receipt and local last-use record enforce normal expiry/clock checks;
this is not tamper-proof DRM. Activation sends a license key, version and terms hash
to the publisher. No Vault contents, paths, device IDs or prompts are sent. No automatic charges.

Prerequisites: Obsidian 1.15+, a supported official model CLI and your own login.
On a new install, Git history and the local Ollama classifier are off; Luna can
perform intent refinement directly. Enable optional integrations in settings.
Codex: https://learn.chatgpt.com/docs/cli/
Antigravity: https://antigravity.google/download

This build is unsigned. No certificate trust or security settings are changed.
Windows installer and plugin behavior were tested on Windows; the macOS app
bundle was structurally checked but still needs a real Mac acceptance test.
No Gatekeeper/SmartScreen bypass commands are included. Developer ID signing,
Apple notarization and Windows signing require the publisher's certificates.

Backups: <Vault>/.obsidian/workbench-install-backups/<installation-id>/
To uninstall, disable Workbench and use Obsidian's normal plugin removal UI.
Notes and local Sessions are separate from the plugin folder and are retained.
