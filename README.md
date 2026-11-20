# MainSequence-RecipeClipboard

Copy recipes between compatible machines without opening their configuration screens.

## Requirements

Main Sequence, single-player; MSCore 0.8.13 and a compatible UE4SS installation. Requires MainSequence-Framework 0.3.4.

## Install and update

Add `pobkac-svg/MainSequence-RecipeClipboard` in MSCore Manager. Save and fully restart after installation or updates. Do not enable the old standalone mods alongside these addons. Keep saves, Designs and underground companion files.

## Controls

Aim at a configured machine with menus/build/disassembly closed. Ctrl+C copies its recipe; Ctrl+V pastes to a compatible machine. Feedback banners report the result.

## Troubleshooting and removal

Check `ue4ss/UE4SS.log` and `Mods/MSCore/selfcheck.log`. Close the game before Manager removal. Removing Recipe Clipboard does not undo recipes already assigned to machines.

## Release status

Version 0.2.1: gameplay and Manager testing confirmed by the user on 20 November 2026. Release downloads include the runtime ZIP and its checksummed MSCore manifest. Tested with the existing UE4SS 4.0.0 installation and the current installed game update; other builds are not verified.

## Credits and terms

Developed with OpenAI Codex. Uses MSCore by xxalex3xx97 and UE4SS as external dependencies. Unofficial; not affiliated with the game developer. This repository contains release documentation, with runtime files supplied as release downloads. Development source, extracted game data and saves are excluded. No third-party licence is granted; our own code is licensed under MIT (see LICENSE). Game assets and dependencies are excluded from that grant.

## Manager dependency metadata correction

Release 0.2.1 fixes matching `requires` fields in the download manifest and installed `mscore.mod`. Gameplay is unchanged. Requires the corrected Framework 0.3.4.
