# Run It — Releases

Public release artifacts for **Run It**, a fast-paced capture-the-flag game by JaysRealmGames.

**Play it:** https://jaysrealmgames.itch.io/run-it

| File | Purpose |
| --- | --- |
| `RunIt-Windows-Setup.exe` | Stable filename for the latest Windows installer |
| `RunIt-Windows-Prototype.zip` | Portable Windows build |
| `update.json` | Update manifest read by the in-game updater |
| `RunIt-macOS.zip` | Stable filename for the latest macOS app |
| `update-macos.json` | macOS update manifest read by the in-game updater |

Releases are published automatically by the game's build pipeline; pushes to this
repo publish the stable filenames as GitHub Release assets and deploy the Windows
installer and macOS app to their itch.io channels. Version numbers live in the
release tag and update manifests, never in the downloadable filenames.
