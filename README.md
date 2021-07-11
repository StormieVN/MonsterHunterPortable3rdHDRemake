# Stormie's Monster Hunter Portable 3rd (MHP3rd) HD Remake Texture Pack
This fork consists of my personal changes/additions to the original upscale project, while still keeping its spirit. The main purpose here is to try to revive the project by rallying some more people to help continuing and finishing it. Or at least do as much as we can.

By default, most texture size will be around **1024x1024** max, while some others will be at a lower res (*vanilla is 64x64*). Upon testing, this is the resolution that I personally think is the best for both quality and performance reason. 4K resolution won't be an option due to how PPSSPP handles .PNG files, causing lots of performance drops (though I might reconsider this in the future).

*This change can always be excluded / reverted if you prefer to keep some of the higher-res textures.*

## Changes that this pack currently brings:
1. Add-ons:
	- Monster Hunter World's icon pack, replacing majority of item icons and several UI icons. (Progression: *90% item icons | 40% status icons | 100% button icons | 20% User Interface icons*)
	- 5 Blademaster armor set fully upscaled: Mosgharl, Aelucanth, Agnaktor, Yamato and Vangis.
	- 2 Hammers: Iron Striker & Jupiter's Sphere (*Duramboros' Hammer*).
	- 2 Poogie outfits: Hog in a Frog & Memorial Stripes.
	- New and proper Portable 3rd loading screen (provided by Josli), replacing the old Freedom Unite's screen from the original pack.
	- Fire texture upscaled from scratch, providing a smoother and more detailed looks to the flames.
	- Slightly upscaled the skybox of "*Island Day*" map, though this might get reworked again in the future.

2. Bug fixes:
	- Fixed the odd light glow that can be seen in *Guild Hall's lanterns/Personal home oven's light*. New version should be smoother and lighter in file-size.
	- Fixed weird shadow in *Personal home*, turning it from white into a smooth dark gradient, which also eliminates the blocky pixelated shadow in vanilla.
	- Fixed some of the hashes so that the game would properly load in the upscaled textures (some monsters didn't get their upscaled texture applied). However, due to the nature of hashes and updates, some textures might still be ignored and require further checking.
	- Optimized both the resolution and size of original files.

3. Optional files:
	- Xbox One layout for controller buttons. (**Default: Dualshock 4 layout**)
	- Sharpness bar with flat style (*MHW*) or chipped style (*MHP3rd*) at Orange/Red sharpness. (**Default: chipped style**)
	- Loading screen with / without decorative frames. (**Default: with frames**)
	- Quest icon with plain / decorative style. (**Default: plain style**)
	- Optional high performance pack for weak PC / phone users. Files are smaller and lighter while still retaining most of its detail (Texture size will be around **256x256** and lower).

As usual, if you do not like any aspect of the texture pack, you can manually disable them specifically. The game will revert them back to vanilla textures.

## Requirements:
- PPSSPP 1.11.3 or later. Alternatively, a PPSSPP version with **texture replacement function** is the minimum requirement.
- Playable Monster Hunter Portable 3rd HD (NPJB40001)
- Optional: V5.0 translation patch
Note, the textures were made using the V5.0 Translation patch applied. Your mileage may vary if you do not apply said patch before trying to run these textures.

## Installation (as of PPSSPP version 1.11.3):
**Before installing my pack, make sure to back up any texture modification you've done (or move/rename the _"NPJB40001"_ folder), since this will replace a lot of files.**

### Fresh installation:
1. Locate PPSSPP Settings - Tools - Developer tools - Enable "*Replace textures*"
2. Extract/copy "*TEXTURES*" folder you got from the .zip into:
```
\memstick\PSP\
```
Select "Yes" if you were prompted to replace files.

3. Launch MHP3rd and enjoy!

### Installing optional files (xbox buttons, sharpness bar, etc):
1. Extract/copy "*TEXTURES*" folder from the Optional pack of your choosing into:
```
\memstick\PSP\
```
2. Select "Yes" when prompted to replace files.
3. Launch MHP3rd and check if it works. If the game is running then you'll need to reload the game for the changes to appear.

## Trailer:


## Screenshots:
![Vangis/Deviljho comparison](https://github.com/StormieVN/MonsterHunterPortable3rdHDRemake/blob/screenshots/Compare_Belt_Vangis.jpg "Vangis / Deviljho")

![Glow fix comparison](https://github.com/StormieVN/MonsterHunterPortable3rdHDRemake/blob/screenshots/Compare_Glow.jpg)

![Yamato comparison](https://github.com/StormieVN/MonsterHunterPortable3rdHDRemake/blob/screenshots/Compare_Head_Yamato.jpg "Yamato helmet")

![Icons comparison](https://github.com/StormieVN/MonsterHunterPortable3rdHDRemake/blob/screenshots/Compare_Icon2.jpg "Drinks and weapon icon")

## To-do list:
- [ ] Fix the wrong fishing location on minimap in the Flooded Forest map.
- [ ] Upscale / Redraw specific P3rd item icons like Bamboo shoots.
- [ ] Rework Mosgharl & Aelucanth armor textures, making it on par with the rest. They were the first two that I started working on, so the experience wasn't fully there.

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