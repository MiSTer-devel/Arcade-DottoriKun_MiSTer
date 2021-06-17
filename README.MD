# Dottori-Kun for [MiSTer](https://github.com/MiSTer-devel/Main_MiSTer/wiki)

Based on DottoriLog by Furrtek: https://github.com/furrtek/DottoriLog

Which was based on information from Chris Covell: http://www.chrismcovell.com/dottorikun.html

Uses the TV80 Z80 core by Guy Hutchison: https://github.com/hutch31/tv80

Port to MiSTer and minor alterations by JimmyStones: https://github.com/JimmyStones/

## Releases
Dottori-Kun (old) - Original ROM, coin input cycles the colour scheme

Dottori-Kun (new) - Revised ROM, coin input enters test menu (start to cycle option, coin to select)

Dottori-Man Jr. - ROM hack by Chris Covell, coin input enters test menu (arrows to change option, fire to select)

## ROM Files Instructions

**ROMs are not included!** In order to use this arcade core, you will need to provide the correct ROM file yourself.

To simplify the process .mra files are provided in the releases folder, that specify the required ROMs with their checksums. The ROMs .zip filename refers to the
corresponding file from the MAME project.

Please refer to https://github.com/MiSTer-devel/Main_MiSTer/wiki/Arcade-Roms for information on how to setup and use the environment.

Quick reference for folders and file placement:

```
/_Arcade/<game name>.mra
/_Arcade/cores/<game rbf>.rbf
/games/mame/<mame rom>.zip
/games/hbmame/<hbmame rom>.zip
```