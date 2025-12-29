# Alisa Vita

<p align="center"><img src="./screenshots/game.png"></p>

This is a port of Alisa: Developer's Cut for PSVita.

Alisa is a indie survival horror game heavily inspired by the classics of this genre like the original Resident Evil.

# How to Install

- Buy [Alisa: Director's Cut from Steam](https://store.steampowered.com/app/1335530/Alisa/) and install it.
- Download the datafiles.zip and alisa.vpk from the Release page.
- Install alisa.vpk on your PSVita.
- Extract on your PC datafiles.zip in a folder of your preference.
- From the Steam game datafiles, copy all files (excluding directories) from `Alisa_Data` folder except for `app.info` and `output_log.txt` (it should total at 289 files) to the `alisa` folder in the datafiles folder.
- Run `patch_files.bat`.
- Extract all the files, except for `archive.psarc`, inside the `alisa` folder inside the `data.zip` generated file into `ux0:app/ALSA500001/Media`.
- Extract `archive.psarc` inside the `alisa` folder inside the `data.zip` generated file into `ux0:app/ALSA500001`.
- **Optional**: For trophies to be unlockable, install [NoTrpDRM](https://github.com/Rinnegatamante/NoTrpDrm).

# Credits

- PatnosD: For fixing the vast majority of animations in the game and for giving additional help to fix some minor issues.
- hatoving: For helping with the initial bootstraping of the project and for the Livearea assets.
- withLogic: For additional help testing the port.
