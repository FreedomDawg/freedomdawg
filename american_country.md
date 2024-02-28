---
layout: default
---

# American Country Pinball Game

This American Country Pinball table is a re-skin of AC/DC LUCI (Stern 2013) VPinWorkshop version 1.1. Original table by Stern Pinball.

I chose the AC/DC table for my Country Music mod for many reasons. I love the gameplay but sometimes I’m not in the mood for hard AC/DC music. Overall I've tried to mellow out the game with Country Music and related sound effects while keeping the intense gameplay dynamics. I replaced the comical “abusive” AC/DC voice prompts with AI generated Johnny Cash voices. The toys map well to Country Music themes: Hells Bell to Liberty Bell, train to pickup truck, cannon to gun and so on. In the minigame the metaphor is you fight for Freedom instead of against the Devil. Instead of a Jukebox, there’s a Playlist with selected songs arranged as twelve different tags that span the themes found in Country Music. As a bonus I provide instructions to replace the Playlist with your own favorite songs.


## [Download Game Files](https://vpuniverse.com/files/file/18381-american-country-vpx/) (Requires Visual Pinball to run)

![screenshot](/assets/images/American Country screenshot freedom.png)

FOR PERSONAL USE ONLY AND NOT FOR COMMERCIAL SALE OR DISTRIBUTION. 

## Requirements

* VisualPinball VPX 10.7.4 minimum
* ROM: customized version of the acd_170hc ROM
* Altcolor: serum

For 64bit VPX, ensure you have VPinMAME 3.5-573 or later (Aug 2023) https://github.com/vpinball/pinmame/releases/ 

## Downloads

https://drive.google.com/open?id=1-VoNftldPia2Saa8KMNMM_k9wLM42iLF&usp=drive_fs 

* American Country.vpx - Visual Pinball table file
* American Country full dmd.directb2s - Backglass file
* acd_170hc.zip - custom acd_170hc ROM 
* acd_170hc.cSZ - altcolor Serum colorization file
* American Country Wheel.png - Frontend wheel image file

Installation is like any other Visual Pinball game:

* Put the “American Country.vpx” and .directb2s files into your Visual Pinball\Tables\ folder
* Put the acd_170hc.zip ROM file in the Visual Pinball\VPinMAME\roms\ folder
* Put the acd_170hc.cSZ Serum file in the Visual Pinball\VPinMAME\altcolor\acd_170hc\ folder

## Custom ROM

The American Country VPX pinball game requires a custom version of the acd_170h ROM named acd_170hc. (This is NOT the same as the acd_170hc color DMD one you might find elsewhere, I’m just repurposing the file name). Legally you need to make this yourself, although I’ve provided a pre-made one for your reference in the downloads. See the CUSTOM ROM readme file for details and instructions. 

https://docs.google.com/document/d/1-N05PtEFAEqhrPOw-jrTKOcJOQ759BSJhy9ggBIJgmA/edit?usp=sharing 

## Why a Custom ROM?

Typically, VPinMAME lets you replace ROM sounds using altsound. I was not able to get this to work with this Stern ROM (and from my research it may not be possible with the current version of VPinMAME), so instead I have written my sounds directly into the ROM file. (If I am wrong and you know a way to use altsound with this ROM please reach out to me and I’ll redo this!)

Thus, I’m using the acd_170hc ROM name, which was a color variant of the actual acd_170h ROM and is recognized by VPinMAME. If you are already using the acd_170hc ROM for your AC/DC game, you’ll need to change that game back to acd_170h. The color version is pretty much obsolete anyway because there’s a new awesome Serum based altcolor colorization available for AC/DC (https://vpuniverse.com/files/file/17697-acdc-64-colors/).  

Note, since i’m changing the ROM file itself, vpmalias will not help either.

## Altcolor DMD 

The VpinMAME altcolor DMD is implemented using Serum colorization (cSZ file). See https://vpuniverse.com/forums/topic/8433-short-yet-full-serum-installation-howto 

* Requires DMDext (Freezy) 2.1 or later. 
* Otherwise you should download serum.dll and copy to vPinMAME directory https://github.com/zesinger/libserum/releases /
* To enable Altcolor, Run game in VisualPinball, press F1, check “Use external DMD dll", and check “Colorize DMD (4 colors)”

## Free Play and Other Config

Service Menu Reminder: press “0” to select/confirm, “9” = up, “8” = down, “7” = go back.
To configure the ROM for free play, use keyboard “0” > Adjustments > Standard Adjustments > #38 Free Play.
To make the knocker work, > Adjustments- >Standard Adjustments > #55 and set Q24 option to Knocker (according to ninuzzu).
You can use either the Plunger or Magna Save button in lieu of the Fire button. Set that option in the VPX Script. 

## Credits

This table is a mod of the ACDC LUCI (Stern 2013) VPW Mod table (https://vpuniverse.com/files/file/12471-acdc-luci-stern-2013-vpw-mod/.Please look there for details including physics, lighting, playfield and many other improvements that made me really want to use that version as the basis for this game instead of other ones. 

I extend many thanks to all who have worked on the precursors and components built into this table,  including: ninuzzu, Sixtoe, hauntfreaks, Fluffhead35, nfuzzy, Apophis, Tomate, Retro27, Schlabber34, javier, DJRobX, dark, tom tower, knorr, rysr, Peter J, RustyCardores, the VPDevTeam, and more! 

## Art Assets

Art assets are open source, royalty free, Creative Commons, and/or used with permission. Sources include:

Graphics
* https://www.dreamstime.com/
* https://jonmcnaughton.com/
* https://wikiclipart.com/
* https://www.flaticon.com/
* https://www.countrythangdaily.com/
* https://www.pixelstalk.net/
* Match animation based on https://giphy.com/gifs/dance-melisina-streamer-twitch-XmwsEY8pIH8iC5uvF8 


3D Models
* Pickup truck: https://www.turbosquid.com/3d-models/ram-3ds-free/491059 
* Cowboy hat:  https://sketchfab.com/3d-models/cowboy-hat-b034b666273c437497208f9d0eed3fcd
* Pistol: https://www.turbosquid.com/3d-models/3d-model-tt-pistol-lowpoly-pbr-1981269

Sounds
* https://www.producerloops.com/
* https://pixabay.com/sound-effects/

Music
* See https://docs.google.com/document/d/1-N05PtEFAEqhrPOw-jrTKOcJOQ759BSJhy9ggBIJgmA/edit?usp=sharing 

## Development Tools

Software used in the development of this project include:

* Visual Pinball
* B2S Backglass Designer
* Pinball Browser
* ColorizingDMD (Serum)
* Reaper
* Photoshop
* Camtasia
* UkeySoft Spotify Music Converter
* iMyfone VoxBox
* ChatGPT
* DALL-E

## Comparison with the AC/DC Luci Game

If you’re familiar with the AC/DC pinball game you may want to know the mappings of features and attributes between the tables. Especially if you know the rules and strategies of AC/DC, this mapping can help you make the transition to the American Country table.

** AC/DC Game : American Country Game **

Jukebox : Playlists

Train : Pickup truck

Bell : Liberty bell

Cannon : Gun

AXE lanes : Star lanes

TNT targets : Hat targets

AC/DC targets : Beer targets

ROCK targets : Boots targets

Thunder targets : Cross targets

FIRE lanes : Band instruments lanes

Jam Multiball : Country Pop Multiball

Album Multiball : Country Americana Multiball

Tour Multiball : Country Classic Multiball

Hell lower playfield : We The People lower playfield

Other features remain the same: Note arrows, 2X, 3X, VIP Passes Skill shots.

## Rules

For a full AC/DC Rule Sheet see http://bit.ly/acdcrulesheet and https://pinside.com/pinball/forum/topic/acdc-rules-condensed-version 

## Changelog
12/28/2023	Preview 1 Release

