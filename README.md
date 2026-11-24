# A Dragon's Ledger

[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%2F%2011%20(x64)-blue)](#downloads--verification)
[![Release](https://img.shields.io/badge/Release-v1.0.1-d4a853)](https://github.com/Oynex/A-Dragon-s-Ledger/releases/latest)
[![itch.io](https://img.shields.io/badge/itch.io-Available%20Free-fa5c5c)](https://oynex.itch.io/a-dragons-ledger)
[![License](https://img.shields.io/badge/Price-Free%20%26%20Offline--First-34d399)](#)

**An offline-first Markdown campaign manager and spoiler-safe lore distribution tool for tabletop RPGs.**

- **Website & Full User Guide:** [dragonsledger.com](https://dragonsledger.com)
- **itch.io Project Page:** [oynex.itch.io/a-dragons-ledger](https://oynex.itch.io/a-dragons-ledger)

---

## Features

- **100% Local Plain-Text Storage:** Your entire campaign lives in a regular folder on your hard drive as standard `.md` files with YAML frontmatter and JSON map definitions. No proprietary database, no accounts required to write, and full compatibility with Obsidian or VS Code.
- **Lossless Map Explorer:** Pan and zoom continent and dungeon maps at their native resolution without image compression. Drop pins linked to any NPC, location, or event, filter categories with a toggleable legend, and click any marker to view its notes in a slide-over drawer.
- **2-Way `[[WikiLinks]]`, Split Panes & Peek Drawer:** Type `[[` anywhere to link characters, towns, factions, or quests. Open notes side-by-side in split panes or inspect linked articles in a slide-over Peek Drawer without losing your place.
- **Tabletop Writing Blocks & Clocks:** Format boxed narration text with `> [!read-aloud]` callouts for quick reading at the table, and track villain schemes or faction tension with interactive progress clocks.
- **2D Relationship Graph:** Visualize connections across NPCs, factions, and locations in an interactive force-directed graph with category filters.
- **1-Click GitHub Backup & Spoiler-Free Player Sync:** Sign in once via GitHub Device Flow to back up your full DM vault to a private repository, then publish a sanitized snapshot (excluding non-player-safe categories and pins) to a separate public player repository accessible via a single `adl-invite://` code—no GitHub account required for players.

---

## Downloads & Verification (`v1.0.1`)

Both editions are feature-complete and work completely offline. You can download directly below or via the [itch.io page](https://oynex.itch.io/a-dragons-ledger).

| Edition | Download | Size | VirusTotal |
| :--- | :--- | :--- | :--- |
| **Windows Installer** *(Recommended)* | [`a-dragons-ledger-setup.exe`](https://github.com/Oynex/A-Dragon-s-Ledger/releases/latest/download/a-dragons-ledger-setup.exe) | ~133 MB | [View Scan Report](https://www.virustotal.com/gui/file/ecd1e6658537b334b3ba8e37d8d9080af9f934238c5c41d57b25877ae2d3cdc2) |
| **Portable Edition** *(Zero Install)* | [`a-dragons-ledger-portable.exe`](https://github.com/Oynex/A-Dragon-s-Ledger/releases/latest/download/a-dragons-ledger-portable.exe) | ~119 MB | [View Scan Report](https://www.virustotal.com/gui/file/d95decf1db25ff0bc7573ea0e7e967a88a1f8496d281358f9b7a2ab5807c172a) |

### SHA-256 Checksums

- **`a-dragons-ledger-setup.exe`**
  ```text
  ecd1e6658537b334b3ba8e37d8d9080af9f934238c5c41d57b25877ae2d3cdc2
  ```
- **`a-dragons-ledger-portable.exe`**
  ```text
  d95decf1db25ff0bc7573ea0e7e967a88a1f8496d281358f9b7a2ab5807c172a
  ```

You can verify the downloaded file locally in Windows PowerShell:
```powershell
Get-FileHash .\a-dragons-ledger-setup.exe -Algorithm SHA256
```

> **Windows SmartScreen Note:** Because this is a free indie hobby release without a paid Windows code-signing certificate, Windows Defender SmartScreen may display *"Windows protected your PC"* on first launch. Click **More info** → **Run anyway** to run the app.

---

## Quickstart

### For Dungeon Masters
1. Launch **A Dragon's Ledger** and choose **Create New Campaign** (or open an existing folder).
2. Create articles across categories (NPCs, Places, Factions, Quests, Developments, Sessions) and link entries using `[[`.
3. Hover over any category in the sidebar and click the edit icon to toggle **Player Safe** on or off.
4. Open **Cloud Sync** in the top header to sign in with GitHub, back up your private vault, and generate a spoiler-free `adl-invite://` link for your table.

### For Players
1. Launch **A Dragon's Ledger** and click **Join Campaign with Invite Code**.
2. Paste the `adl-invite://...` code sent by your DM and choose a local folder for your copy.
3. Browse unlocked lore and maps in read-only mode. After sessions, click **Update Campaign** in the top bar to pull newly revealed notes.

---

## Bug Reports & Feedback

This repository serves as the public release distribution and issue tracker for **A Dragon's Ledger**.

- Found a bug or layout issue? Open an **[Issue](https://github.com/Oynex/A-Dragon-s-Ledger/issues)** with your Windows version and steps to reproduce.
- Have a question or feature suggestion? Start a thread in **[Discussions](https://github.com/Oynex/A-Dragon-s-Ledger/discussions)** (or open an issue).
