# Juniper's Knot (PS Vita port)
A Juniper's Knot port for Playstation Vita console leveraging [Ren'Py Vita](https://github.com/SonicMastr/renpy-vita) by [SonicMastr](https://github.com/SonicMastr) which in turn is a port of [Ren'Py engine](https://www.renpy.org). The game itself is a short visual novel made back in 2012 by [Dischan](https://dischan.co). If you want more stats and info you can refer to [its entry](https://vndb.org/v9986) on VNDB. There a couple of new additions apart from just the game port (see Changelog for more info).

## Requirements
* Modded PS Vita (very easy to search for loading CFW online)
* [VitaShell](https://github.com/TheOfficialFloW/VitaShell) or any other method of navigating Vita's internal memory

## Installation 
### First Time
1. Go into **Releases** section of this repository and download the _.vpk_ file
2. Transfer the file into your Vita (ie. under _ux0:VPK_ or any other folder you created) and install

The installation can take a up to 2 mins, the first startup of the game should be 1,5 mins. All of this is expected behaviour.

### Updating to New Release
1. Go into **Releases** section of this repository and download the latest _**archives.rpa**_ file
2. Go into **_ux0:app/JNPRSK099/game_** on your Vita and replace existing _**archives.rpa**_ with the downloaded one

### Getting the DLC "Thank you" message
1. Buy the DLC to support the devs (should be just ~1 USD on Steam)
2. Go into the Juniper's Knot directory on your PC - right-click the game in your library _Manage->Browse local files_. In the _game_ there should be an _img_ folder - copy that under the same directory on your Vita (ie. _ux0:app/JNPRSK099/game_). The image will now show up in Extras section's gallery once you finish the game
3. Feel proud you supported the people who made the game

## Current Issues
* Occassional short lags when Ren'Py is loading new assests. Shouldn't be too much of a bother but it is still noticeable
* Small GUI glitch under specific circumstances showing "toggle mute" while scrolling through main menu
* For Polish translation there might be an error with displaying credits (language mismatch at one point)
  
## Changelog
### Initial Release - v00.99
* Edited script to remove code compatability errors preventing the game from booting up under Ren'Py Vita
* Removed ability to change resolution
* Added entirely new possibility of language selection upon first bootup. Please note only Polish and Turkish have the menus translated as the game is heavily image dependant and first translations lacked in that area. **Language selection is one-time only for now.** You have to reset persistent data in orded to choose it again. Not advised if you made other settings setup or cleared the game
* Added entirely new help screen
* Edited credits section
* Remapped certain keys to better adjust to the Vita


