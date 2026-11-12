# Fransbot: Rearmed

An experimental AI opponent for OpenRA Red Alert, using strategic objectives and independent commanders without hidden battlefield information.

## Download RC6

**Current version: 1.32.0-rc.6**

- [Windows x64 ReadyToRun ZIP](https://github.com/f850484/Fransbot-Releases/releases/download/v1.32.0-rc.6/Fransbot-1.32.0-rc.6-Windows-ReadyToRun.zip)
- [Matching GPL source ZIP](https://github.com/f850484/Fransbot-Releases/releases/download/v1.32.0-rc.6/Fransbot-1.32.0-rc.6-SOURCE.zip)
- [SHA256 checksums](https://github.com/f850484/Fransbot-Releases/releases/download/v1.32.0-rc.6/SHA256SUMS.txt)
- [Release notes and previous releases](https://github.com/f850484/Fransbot-Releases/releases)

## Requirements and installation

1. Install [official OpenRA Playtest 20261026 for Windows x64](https://github.com/OpenRA/OpenRA/releases/download/playtest-20261026/OpenRA-playtest-20261026-x64.exe).
2. Set up Red Alert content through OpenRA using legally obtained game content.
3. Extract the complete Fransbot ZIP into a new folder and run **Play-Fransbot.bat**. **OFF.bat** is equivalent; **LIGHT.bat** collects bounded diagnostic logs without a visible debug overlay.
4. Open **Singleplayer > Skirmish** and choose **Native OpenRA** or **Balance Iteration 5.9**. Both use the same Fransbot AI and lobby.

The OpenRA engine and Red Alert content are required separately and are not included. No Visual Studio, Python installation, development SDK or Codex is required.

## Optional Balance Iteration 5.9

Native rules work immediately without BI. To install BI, close the game and explicitly run **Install-BI.bat**. It asks for confirmation before fetching the nine pinned text files directly from the official [Balance Iteration repository](https://github.com/tttppp/ora-balance-iteration), checks their hashes against revision `f787bf73b30c142b282233002a300fc8d4509e03`, and validates the profile before activation. Installed BI then works offline.

This release does not redistribute upstream BI YAML, artwork or audio. Stock Red Alert assets supply the documented visual/audio substitutions. Older maps with incompatible embedded BI rules are rejected; ordinary and generated maps use the selected profile, with explicit map rules taking precedence.

## What changed

RC6 includes the approved naval RAID and Ground RECON performance improvements, quieter OFF/LIGHT presentation, and smoother map navigation. Necessary loading when changing rule profiles remains. Ground SECURE uses 3x known threat; routine MCV land expansion is Balanced with a 40-cell preferred hop. Existing retreat, transport, defense and Allied Beacon protections are retained.

## Status and feedback

This is an experimental pre-release. Native fixtures and bounded two-client synchronization tests do not establish every long-match, multiplayer or custom-map outcome. Keep replays and diagnostic logs when [reporting a problem](https://github.com/f850484/Fransbot-Releases/issues), and include the engine version, rule profile, map and match settings.

This public repository hosts releases, documentation and feedback. The development repository remains private. Each release supplies its matching GPL-3.0-or-later corresponding source and license notices.

Fransbot is an independent community project, not an official OpenRA release.
