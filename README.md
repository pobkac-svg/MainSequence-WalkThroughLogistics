# MainSequence-WalkThroughLogistics

Walk through splitters balancers and mergers.

## Requirements

Main Sequence, single-player only. Requires [MSCore 0.8.13](https://github.com/xxalex3xx97/MSCore/releases/tag/v0.8.13), a compatible UE4SS installation and [MainSequence-Framework 0.3.4](https://github.com/pobkac-svg/MainSequence-Framework). Tested with UE4SS 4.0.0 and the user's current installed game update; other builds and multiplayer are not verified.

## Installation and updates

Install Framework first, then add `pobkac-svg/MainSequence-WalkThroughLogistics` in MSCore Manager. Save and fully restart after installation or updates. Do not enable the old standalone copy alongside this addon. The release ZIP and checksummed manifest use the MSCore Manager format.

## Use

Walk through splitters, balancers and mergers as you do through belts. No key binding. Custom merger assets are supplied separately by Belt Merger.

## Removal and troubleshooting

Close the game before removing this addon through Manager. Removing an addon stops its features; it does not undo completed construction, recipes or grants. Keep native saves, Designs and underground companion files. Logs: `ue4ss/UE4SS.log` and `Mods/MSCore/selfcheck.log`.

## Compatibility and verification

Version 0.3.1: existing gameplay confirmed by the user after MSCore migration. Manager testing was confirmed by the user; Framework and Recipe Clipboard public downloads were additionally tested through Manager. No extracted game data, user saves or private development history are included here.

## Credits and licence

Our code is MIT-licensed; see LICENSE. Developed with OpenAI Codex. MSCore by xxalex3xx97 and UE4SS are external dependencies under their own terms. This licence excludes game assets and third-party components. Unofficial; not affiliated with the game developer. This repository holds release documentation; packaged runtime downloads are attached to releases.

## Manager dependency metadata correction

Release 0.3.1 fixes matching `requires` fields in the download manifest and installed `mscore.mod`. Gameplay is unchanged. Requires the corrected Framework 0.3.4.
