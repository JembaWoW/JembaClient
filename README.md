# JembaClient
## A collection of my modded WoW.exe, client mods and patches.

Includes [SuperWoW](https://github.com/balakethelock/SuperWoW/releases/) and the [SuperAPI](https://github.com/balakethelock/SuperAPI/), [VanillaFixes](https://github.com/hannesmann/vanillafixes/releases/) and a manually set up [Vanilla Tweaks](https://github.com/brndd/vanilla-tweaks/releases).

# ⚠️ **Run the game via VanillaFixes and not WoW** ⚠️

# ⚠️ **The repo is unlikely to be maintained. SuperWoW will most likely receive future updates which you'll need to update manually yourself.** ⚠️
I've tried to include as many links to my sources as possible.

The Vanilla Tweaks settings that I used:
```
./vanilla-tweaks --nameplatedistance 20 --no-quickloot --soundchannels 32 WoW.exe -o WoW.exe
```

* **--nameplatedistance 20** Vanilla nameplate distances, if you want a bigger distance, let me know and I'll custom set it for you  
* **--no-quickloot** No Vanilla Tweaks auto loot since SuperWoW does it better  
* **--soundchannels 32** Reduced sound from Tweaks' default of 64 down to 32. There's a known issue where if too many sounds play at once you'll crash to desktop. So I play it safe.

Also included are 3 custom patches in the Data folder.

**patch-9** is a [SuperWoW patch](https://github.com/balakethelock/SuperWoW/releases/tag/Patch) for changing how the circle looks on the ground when you target a mob. In the attatched image is style "3", which adds a little arrow showing which direction the head of the mob is facing.
https://github.com/balakethelock/SuperWoW/wiki/Changelog#14042024--110
(Change between the 4 styles via SuperAPI's minimap button)

**patch-M** (Optional) - A merged patch, containing a bunch of smaller patches that I love.
* [Pretty night skies](https://forum.turtle-wow.org/viewtopic.php?p=70273)
* [Improved 2FA login](https://github.com/Lexiebean/Turtle-WoW-Improved-2FA)
* [Autologin](https://github.com/Haaxor1689/vanilla-autologin) (Note, this saves your passwords in plain text within your config.wtf file)
* Inverted Flask of Wisdom icon colours (Never mistake it for a Greater Nature Protection Potion again 😭)
* [Turns (most) herbs pink for easy finding.](https://github.com/seacrabsam/patch-herb)
* I think there's also some improved water textures.

**patch-W** (Optional) - Contains more improved water textures, compatible with patch-M.
This came from project-epoch, I think the patch files were on their discord. I can't find a source link.
