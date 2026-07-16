# Run It — Releases

Public release artifacts for **Run It**, a fast-paced capture-the-flag game by JaysRealmGames.

**Play it:** https://jaysrealmgames.itch.io/run-it

| File | Purpose |
| --- | --- |
| `RunIt-Windows-Setup-v*.exe` | Windows installer (latest version only) |
| `RunIt-Windows-Prototype.zip` | Portable Windows build |
| `update.json` | Update manifest read by the in-game updater |
| `RunIt-macOS-v*.zip` | Universal macOS app for Apple silicon and Intel |
| `RunIt-macOS.zip` | Stable filename for the latest macOS app |
| `update-macos.json` | macOS update manifest read by the in-game updater |

Releases are published automatically by the game's build pipeline; pushes to this
repo deploy the Windows installer and macOS app to their itch.io channels. Older
versioned downloads are available in this repo's git history.
