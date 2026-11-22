# MainSequence-WalkThroughLogistics

Walk through splitters balancers and mergers.

## Requirements

Main Sequence, single-player only. Requires [MSCore 0.8.13](https://github.com/xxalex3xx97/MSCore/releases/tag/v0.8.13), a compatible UE4SS installation and [MainSequence-Framework 0.3.6](https://github.com/pobkac-svg/MainSequence-Framework). Tested with UE4SS 4.0.0 and the user's current installed game update; other builds and multiplayer are not verified.

## Installation and updates

Install Framework first, then add `pobkac-svg/MainSequence-WalkThroughLogistics` in MSCore Manager. Save and fully restart after installation or updates. Do not enable the old standalone copy alongside this addon. The release ZIP and checksummed manifest use the MSCore Manager format.

## Use

Walk through splitters, balancers and mergers as you do through belts. No key binding. Custom merger assets are supplied separately by Belt Merger.

## Removal and troubleshooting

Close the game before removing this addon through Manager. Removing an addon stops its features; it does not undo completed construction, recipes or grants. Keep native saves, Designs and underground companion files. Logs: `ue4ss/UE4SS.log` and `Mods/MSCore/selfcheck.log`.

## Compatibility and verification

Version 0.3.2: the user confirmed the clean combined build on 22 November 2026. Fifteen relevant automated suites passed. Tested with UE4SS 4.0.0; other loader versions remain unverified. No game assets, saves or private crash data are included. Severe large-save FPS drops remain a separate investigation.

## Credits and licence

Our code is MIT-licensed; see LICENSE. Developed with OpenAI Codex. MSCore by xxalex3xx97 and UE4SS are external dependencies under their own terms. This licence excludes game assets and third-party components. Unofficial; not affiliated with the game developer. This repository holds release documentation; packaged runtime downloads are attached to releases.

## Manager dependency metadata correction

Release 0.3.1 fixes matching `requires` fields in the download manifest and installed `mscore.mod`. Gameplay is unchanged. Requires the corrected Framework 0.3.4.

## 0.3.2 update

- Replace native collider ForEach loops with guarded indexed reads and in-place writes, including save-time restoration.
- Preserve array order, original bounds, walk-through behaviour and save/reload restoration.
- Require Framework 0.3.6.

Save, fully close the game and update Framework first, then the installed feature addons. Fully restart after updating.
