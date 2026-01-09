# Alisa Vita

<p align="center"><img src="./screenshots/game.png"></p>

This is a port of Alisa: Developer's Cut for PSVita.

Alisa is a indie survival horror game heavily inspired by the classics of this genre like the original Resident Evil.

# Note
- This patch works exclusively with the latest version of the game at the time of writing this README. If the game received a new update, the depot you want is: `download_depot 1335530 1335531 3838329713333394627`
- The "Special" button is mapped on L Trigger.

# Known issues

- On new runs, sometimes the backpack on Alisa won't disappear after the prologue.
- The grab animation during the final boss is a bit glitchy (only visual).
- There are some minor issues with lighting across the game.

# Changelog
## v.1.2
- Added a new option (Easy AI) to have less aggressive enemies through the game.
- Made so that the CRT filter is disabled by default.
- Reduced the vignette effect of the CRT filter so that it makes texts more readable.
- Restored custom languages support: now it's possible to create custom translations of the game.
- Reworked mirror reflections so that now are the same as vanilla game rather than an approximation of the same effect.

## v.1.1
- Fixed a bug in pathfinding code that was causing AI to be less aggressive than expected.
- Fixed a bug causing the shop menu to be slightly off scaled.
- Restored "Render" feature: now setting it to 2x will correctly make the game look sharper due to higher internal resolution.
- Fixed a bug causing a few meshes to be rendered full purple.
- Fixed the V-Sync button in the Settings menu to be rendered with bilinear filtering erroneously.
- Fixed the unselected V-Sync button to not render in the Settings menu inside the Pause menu.
- Fixed a bug causing the video prior the main menu to not show anymore after clearing a run until the game was rebooted.
- Fixed the main menu fade effect to show a widescreen stretched image instead of a properly 4:3 centered one.
- Added a new option in the Settings menu to enable a post-processing CRT filter in the game.

## v.1.0
- Initial release.

# How to Install

- Buy [Alisa: Director's Cut from Steam](https://store.steampowered.com/app/1335530/Alisa/) and install it.
- Download the `datafiles.zip` and `alisa.vpk` from the Release page.
- Install `alisa.vpk` on your PSVita.
- Extract on your PC `datafiles.zip` in a folder of your preference.
- From the Steam game datafiles, copy all files (excluding directories) from `Alisa_Data` folder except for `app.info` and `output_log.txt` (it should total at 289 files) to the `alisa` folder in the datafiles folder.
- Run `patch_files.bat`.
- Extract all the files, except for `archive.psarc`, inside the `alisa` folder inside the `data.zip` generated file into `ux0:app/ALSA50001/Media`.
- Extract `archive.psarc` inside the `alisa` folder inside the `data.zip` generated file into `ux0:app/ALSA50001`.
- **Optional**: For trophies to be unlockable, install [NoTrpDRM](https://github.com/Rinnegatamante/NoTrpDrm).

# Credits

- **PatnosD**: For fixing the vast majority of animations in the game and for giving additional help to fix some minor issues.
- **hatoving**: For helping with the initial bootstraping of the project and for the Livearea assets.
- **withLogic**: For additional help testing the port and for some custom buttons sprites.
