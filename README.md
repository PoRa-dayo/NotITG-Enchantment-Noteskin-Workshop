WORK IN PROGRESS

A NotITG port of [HURG's Noteskin-Workshop-Enchantment-V2 project for ITGMania](https://github.com/HURG-IIDX/Noteskin-Workshop-Enchantment-V2/tree/main), now fully 3D modeled.

Check the 2D version [here](https://github.com/PoRa-dayo/NotITG-Enchantment-2D-Noteskin-Workshop).

Welcome to the NotITG noteskin workshop for Enchantment! This is a fully customizable "build your own" noteskin suite based on the "enchantment" noteskin included with ITGmania. Just about every aspect of the noteskin can be customized. As this is meant to be fully compatible with NotITG, all arrows and mines now have 3D models! All customization options have preview images that can be browsed in the "Previews" folder.

(Scroll down to the Overview section for an overview of the features in this workshop, as well as some previews)

# Installation
- Install the noteskin by copying the 4 folders inside Enchantment - NotITG Port, and inside your NotITG game folder, paste them in NoteSkins/dance. These contain the base default variants of the Enchantment noteskin.
(insert file here)

- In NotITG, when you select a chart, right before the chart is played, when "PRESS [START] TO CHOOSE MODS" show up, do that to get the option to select your noteskin.
- "enchantment" and "enchantment-custom" folders are the noteskins with 3d models for consistent compatibility throughout NotITG modcharts. It is recommended to play with these noteskins instead of the 2d ones.
- The corresponding 2d folders are the original 2d version ported directly over. ***The 3d folders will use sprites from their corresponding 2d folders, so both have to be there.***

*You can change your default settings for NotITG by going to the NotITG game folder, and open and edit Data/GamePrefs.ini. Changing the default noteskin will let you apply that noteskin to all players instead of just P1 and P2.*

# Customization
*You will only be changing "enchantment-custom" and "enchantment-custom-2d", as I plan to keep "enchantment" and "enchantment-2d" as consistent folders for modcharts to reference if they want.*

- Head on to the Customization folder and build your own customized noteskin. Keep opening the noteskin variant folders that you prefer until you eventually see the "enchantment-custom" and/or "enchantment-custom-2d" folders.
- Copy those "enchantment-custom" and/or "enchantment-custom-2d" folders.
- In the NotITG game folder, go to NoteSkins/dance folder, then paste the folders and replace files, then restart the game to apply the variant.

(insert file here)



- If you like what you have built in the enchantment-custom folders, you can duplicate those folders and rename them to whatever you want! Though do take note that ***the 3d folder will use sprites from its corresponding 2d folder***. So be sure to duplicate both the 3d and 2d folders, and remember to change the 2d folder that the 3d folder takes sprites from. Just open the metrics.ini file inside the 3d folder, and change the folder name next to FallbackNoteSkin= to that of the 2d folder.



(insert file here)


# Overview
This is a port of the Enchantment V2 workshop by HURG. Compared to the original Enchantment, Enchantment V2 features a simpler ornate pattern that looks nicer with smaller arrow sizes, which is more fitting for modcharts, and a lot more customization options. The original Enchantment, made by [EvocaitArt](https://x.com/EvocaitArt), is also ported and is available in this workshop as "Classic" variants.

## Arrows
There are a lot of arrow customization options. (over 400!)

Firstly, the arrow variants are split into two main groups: "Ornate", which includes the floral pattern similar to the original "enchantment" noteskin; and "Plain", which doesn't have the floral pattern.

Secondly, there are color sets for ITG, Dev, DDR note, DDR Vivid, DDR Rainbow, RGB, and other color schemes seen on other various noteskins. There are also TD (Triplet Denomination) versions of some noteskins, such as TD ITG, that have different colors for 24ths and 48ths.

And lastly, each color set can have some of the following arrow shapes:
- Normal
- Dark (Ornate) / Simple (Plain)
- Gold
- Silver
- Cel Vibrant
- Cel
- Shadow
- Contrast
- Contrast Vibrant
- Void

Below is the "Ornate" arrow shape variations of the ITG color scheme, in the order listed above:
(insert file here)

And here is the "Plain" variations with the floral patterns removed for a more simple look:
(insert file here)

## Explosions
Tap explosions can be customized to different match different judgement color sets. By default it comes with the Ornate "ITG" Glow set, but there are options for color sets like Rainbowmatic and Waterfall and a few others. There is also an "all white" option if you prefer your tap explosions to be color neutral. Tap explosions come in 3 variants per color set: Spark (X shaped like a DDR tap explosion), Glow (similar to the default ITG Cel/Metal noteskin tap explosions) and Minimal (similar to glow but with a smaller area). There are Ornate and Plain versions of every set. You can also disable tap explosions entirely with the "no explosions" customization option. Here is a preview of some of the tap explosion options:

(insert file here)

Hold explosions can be color customized to many different color options and also come in the same 3 variations as tap explosions (Spark, Glow, and Minimal. There are Plain and Ornate versions of every option. By default the skin uses the Ornate "RGB" glow color option. You can also disable hold explosions entirely with the "no explosions" customization option. Here is a preview image of some of the hold explosion options:

(insert file here)

## Holds and Rolls
Holds and rolls (active and inactive) can be color customized. Every color option has four types for holds and rolls, and any of the 4 types can be set as active or inactive. Feel free to mix and match different options! Here is a preview image of some of the hold and roll options:

(insert file here)

## Mines
Mines can be color customized, and for every color option there are three types, each with 2-4 variations. Using the "default" color as an example:

(insert file here)

## Receptors
Receptors can be color customized. There are three arttributes for each color, giving a total of eight types. Using the "Vapor" color as an example:

(insert file here)



There are "Classic" and "Frame" types:

(insert file here)

## Arrow Border (3D only)
NotITG is a game focused on visuals, so a lot of times there will be loads of things happening in the background, killing the readability of lots of noteskins. As the Enchantment noteskin definitely isn't known for having contrasting borders, there is now an option to add an additional border around your arrows, allowing for good readability across NotITG modcharts. It apparently isn't possible to do this sort of thing on 2D noteskins though, so this feature can only be applied to the 3D noteskin.

(insert file here)

## Inaccuracies
I have tried to port most arrows and mines into 3D with the highest accuracy possible by recreating the animations based on what HURG told me. But of course, there are still some minor inaccuracies here and there compared to the 2D version:
- Most of the gradient sheets are recreated by myself, only a few of them are actually obtained from HURG because it'd take a really long time for HURG to export all those gradients, so the colors might be a bit inaccurate.
- Because some shines in the original animations used Overlay blend mode in Photoshop, which cannot be recreated with simple color overlay, all the shine effects present in some variants are inaccurate. Regardless, I've tried my best to find the right colors to make the shine visuals as closest to the original as possible.
- Hold and roll tails end up being longer than usual and disappear sooner than they're supposed to. In the ITGMania version a property was changed to fix this issue, but that'd break during downscroll, like what happened with the DDR noteskin.
- Lifts and FA-mode-related things are removed, since you know, they don't exist in NotITG.

## Special Thanks
- [EvocaitArt](https://x.com/EvocaitArt) - original Enchantment noteskin creator
- [HURG](https://github.com/HURG-IIDX) - creator of the Enchantment V2 noteskin workshop and a bunch of other noteskins
- MechMaelstrom - for guiding me on how to do all these noteskin things in NotITG, as well as for playtesting and feedback.
- Ky_Dash - for playtesting and giving feedback on the noteskin, and answering a bunch of questions I have about the game.
- Nhan, NotITGFan61 - for playtesting and giving feedback on the noteskin.






