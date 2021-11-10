# Stormie's Monster Hunter Portable 3rd (MHP3rd) HD Remake Texture Pack
This fork consists of my personal changes/additions to the original upscale project, while still keeping its spirit. The main purpose here is to try to revive the project by rallying some more people to help continuing and finishing it. Or at least do as much as we can.

By default, most texture size will be around **1024x1024** max, while some others will be at a lower res (*vanilla is 64x64*). Upon testing, this is the resolution that I personally think is the best for both quality and performance reason. 4K resolution won't be an option due to how PPSSPP handles .PNG files, causing lots of performance drops (though I might reconsider this in the future). Rectangular textures can have their width/height go up to **2048** however.

*This change can always be excluded / reverted if you prefer to keep some of the higher-res textures.*

## Screenshots:
<img src="https://github.com/StormieVN/MonsterHunterPortable3rdHDRemake/blob/screenshots/Compare_Belt_Vangis.jpg" height="270"><img src="https://github.com/StormieVN/MonsterHunterPortable3rdHDRemake/blob/screenshots/Compare_Glow.jpg" height="270"><img src="https://github.com/StormieVN/MonsterHunterPortable3rdHDRemake/blob/screenshots/Compare_Head_Yamato.jpg" height="270"><img src="https://github.com/StormieVN/MonsterHunterPortable3rdHDRemake/blob/screenshots/Compare_Icon2.jpg" height="270"><img src="https://github.com/StormieVN/MonsterHunterPortable3rdHDRemake/blob/screenshots/MHP3rd_Compare_Optionals.jpg" height="270">

## Trailer:
[![Youtube Trailer](https://github.com/StormieVN/MonsterHunterPortable3rdHDRemake/blob/screenshots/MHP3rd_Thumbnail_Play.jpg)](https://www.youtube.com/watch?v=RoOyvYqh7pc)

## Changes that this pack currently brings:
1. Add-ons:
	- Monster Hunter World's icon pack, replacing majority of item icons and several UI icons. (Progression: *90% item icons | 40% status icons | 100% button icons | 20% User Interface icons*)
	- 5 Male Blademaster armor set fully upscaled: Mosgharl, Aelucanth, Agnaktor, Yamato and Vangis.
	- 2 Hammers: Iron Striker & Jupiter's Sphere (*Duramboros' Hammer*).
	- 2 Poogie outfits: Hog in a Frog & Memorial Stripes.
	- New and proper Portable 3rd loading screen (provided by Josli), replacing the old Freedom Unite's screen from the original pack.
	- Fire texture upscaled from scratch, providing a smoother and more detailed looks to the flames.
	- Slightly upscaled the skybox of "*Island Day*" map, though this might get reworked again in the future.

2. Bug fixes:
	- Fixed the odd light glow that can be seen in *Guild Hall's lanterns/Personal home oven's light*. New version should be smoother and lighter in file-size.
	- Fixed weird shadow in *Personal home*, turning it from white into a smooth dark gradient, which also eliminates the blocky pixelated shadow in vanilla.
	- Fixed some of the hashes so that the game would properly load in the upscaled textures (some monsters didn't get their upscaled texture applied). However, due to the nature of hashes and updates, some textures might still be ignored and require further checking.
	- Reverted the text background back to vanilla since the upscaled one didn't have alpha channel / not transparent.
	- Optimized both the resolution and size of original files.

3. Optional files:
	- Xbox One layout for controller buttons. (**Default: Dualshock 4 layout**)
	- Sharpness bar with flat style (*MHW*) or chipped style (*MHP3rd*) at Orange/Red sharpness. (**Default: chipped style**)
	- Loading screen with / without decorative frames. (**Default: with frames**)
	- Quest icon with plain / decorative style. (**Default: plain style**)
	- Optional lightweight pack for weak PC / phone users. Files are smaller and lighter while still retaining most of its detail. Most texture files will be around **256x256** and lower, while background and landscapes are **512x512**.

As usual, if you do not like any aspect of the texture pack, you can manually disable them specifically. The game will revert them back to vanilla textures. All of my personal changes are located in "`\TEXTURES\NPJB40001\STORMIE`", in case you need to find them.

## Requirements:
- PPSSPP 1.11.3 or later. Alternatively, a PPSSPP version with **texture replacement function** is the minimum requirement.
- Playable Monster Hunter Portable 3rd HD (NPJB40001)
- Optional: V5.0 translation patch
Note, the textures were made using the V5.0 Translation patch applied. Your mileage may vary if you do not apply said patch before trying to run these textures.

## Download:
- Navigate to the Release section on the top right side of the page or [***Click Here***](https://github.com/StormieVN/MonsterHunterPortable3rdHDRemake/releases).
- Google Drive links for people who doesn't like using GitHub for some reason:
	- [Stormie's HD pack v1.0.0](https://drive.google.com/file/d/1XfwSUNyhlhckC7CjQiuDwUwJDi-fhBuS/view?usp=sharing)
	- [Stormie's Optional pack v1.0.0](https://drive.google.com/file/d/1JqFD4h7KGL8wlBO5zyjbXfQR-9ZQK289/view?usp=sharing)
	- [Lightweight pack for Phones/Weak PC v1.0.0](https://drive.google.com/file/d/10oAvDK4xzSvcx6ZT7-zHZabHt_oq_Rw4/view?usp=sharing)

## Installation (as of PPSSPP version 1.11.3):
**Before installing my pack, make sure to back up any texture modification you've done (or move/rename the _"NPJB40001"_ folder), since this will replace a lot of files.**

### Fresh installation:
1. Extract/copy "*TEXTURES*" folder you got from the .zip into:
```
\memstick\PSP\
```
Select "Yes" if you were prompted to replace files.

For Android users, the folder structure is a bit different, by default it should be in:
```
Internal Storage\PSP\
```
2. Open PPSSPP.
3. Go to PPSSPP Settings - Tools - Developer tools - Enable "*Replace textures*"
4. Launch MHP3rd and enjoy!

### Installing optional files (xbox buttons, sharpness bar, etc):
1. Extract/copy "*TEXTURES*" folder from the Optional pack of your choosing into:
```
\memstick\PSP\
```
replacing the existing "*TEXTURES*" folder. For Android users, the path is the same as from **"Fresh installation"**.

2. Select "Yes" when prompted to replace files.
3. Launch MHP3rd and check if it works. If the game is running then you'll need to reload the game for the changes to appear.

**Lightweight pack for Phones/Weak PC will have the Optional files included in the pack by default.**

## Additional contributions:
If you're interested in contributing towards the project, feel free to join in and submit your own upscaled textures, ideas, suggestions, etc.
However, there are some caveats:
- I'll focus on upscaling male Blademaster armors first, with a big focus on armor sets with full-face helmets/masks.
- Since I prefer to upscale armors/weapons that I obtained in the game, it might take some time for me to farm for mats and craft it first. This helps me with motivation as I work on upscaling it (just a personal thing).
So if you have a set or weapon in mind that might take me too long to get it, you can send me your save file with you wearing it.
- It might take a lot of time for small changes to come out due to me being new/slow/lazy/having it rough irl. For that I'm sorry and I hope you guys will be patient with me.

## Credits:
- David-vz, Ice-w1nd, po456asd, ruckusquantum and others who contributed toward the original MHP3rd HD Remake project.
This small project of mine wouldn't exist without their foundation.
- Josli from HunterVerse Discord server for providing me the high res loading screen.
- n00mkrad, Joey and others who worked on Cupscale & its forks, along with the people who runs GameUpscale discord server and the wiki.
- Archerpolation, nmkd, DinJerr, BlueAmulet, Alsa, Mutin Choler and others for making their AI upscaling models.
