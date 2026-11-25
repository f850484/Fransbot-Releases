# Fransbot: Rearmed

**An experimental AI opponent for OpenRA Red Alert.**

Fransbot is an AI opponent designed to provide a challenging, believable and entertaining skirmish experience without cheating.

Instead of relying on scripted attack waves, Fransbot uses strategic objectives, independent commanders and battlefield information to decide how to expand, defend and attack.

You can also play alongside Fransbot. Place a Beacon to ask allied bots to secure an area, raid an enemy building or send supplies to one of your buildings.

Choose between ten AI personalities in the lobby: Balanced, Raid, Fort, Air, Crawler, Duel, Horde, Fleet, Tech and Civil.

FransReplay lets you seek through a replay or continue playing from it. You can also take over an AI player in supported local replays and saves.

## Download

**Current version: Release Candidate 7 (RC7)**

[Download RC7 for Windows (ZIP)](https://github.com/f850484/Fransbot-Releases/releases/download/v1.32.0-rc.7/Fransbot-1.32.0-rc.7-Windows-ReadyToRun.zip)

[RC7 release notes, source code and checksums](https://github.com/f850484/Fransbot-Releases/releases/tag/v1.32.0-rc.7)

[Previous release (RC6)](https://github.com/f850484/Fransbot-Releases/releases/tag/v1.32.0-rc.6)

## Requirements

- Windows x64
- OpenRA Red Alert – Playtest 20261026
- Red Alert game content (installed separately)
- Standard OpenRA rules, or optional Balance Iteration 5.9

## Installation

1. Install the supported [OpenRA playtest](https://github.com/OpenRA/OpenRA/releases/tag/playtest-20261026) and set up Red Alert content.
2. Download the Fransbot Windows ZIP from Releases.
3. Extract the ZIP into a folder.
4. Run `Play-Fransbot.bat`.
5. Start a skirmish and choose Native OpenRA or Balance Iteration in the Fransbot menu.

Balance Iteration 5.9 is optional. To use it, run `Install-BI.bat` first, then select BI before entering the skirmish lobby. You can play BI games on generated maps too. Both rulesets offer all ten Fransbot personalities.

## FransReplay

Use Replay to watch a recording, or FransReplay to seek through it and continue playing as the original human player. To take over an AI player in a supported local replay or save, start `Take-Over.bat` first. Use `Play-Fransbot.bat` for multiplayer.

## Development status

Fransbot is still experimental. Bugs, strange decisions, performance issues and unexpected behavior are possible.

Short two-player LAN sessions have been tested. Long matches and online multiplayer have not yet been fully tested. Some AI personalities still need fine-tuning.

## Feedback and bug reports

Feedback is always welcome!

Please use [GitHub Issues](https://github.com/f850484/Fransbot-Releases/issues) to report problems. A description of what happened, your map and settings, and a replay or log if available are all helpful.

## About this repository

This public repository hosts Fransbot releases and feedback. Development happens in a private repository, and matching source code is included with each release.

Fransbot is an independent community project, not an official OpenRA release.
