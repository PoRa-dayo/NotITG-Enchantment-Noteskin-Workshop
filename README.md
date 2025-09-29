WORK IN PROGRESS

A NotITG port of [HURG's Noteskin-Workshop-Enchantment-V2 project for ITGMania](https://github.com/HURG-IIDX/Noteskin-Workshop-Enchantment-V2/tree/main).
# Testing
These 7 variants have unique meshes, others just reuse one of these. Prioritize testing these 7:
- Bright Cel Vibrant
- Bright Gold
- Bright Shadow
- Bright Void
- Default
- Default Animated (same mesh as Default just different UV)
- DDR Note Contrast Vibrant

# Installation
- Install the noteskin by copying the 4 folders inside Enchantment - NotITG Port, and inside your NotITG game folder, paste them in NoteSkins/dance. These contain the base default variants of the Enchantment noteskin.
<img width="559" height="210" alt="explorer_dZ7x8pwd3A" src="https://github.com/user-attachments/assets/07a161e8-881d-4ab8-a8c2-2940b506e64a" />

- In NotITG, when you select a chart, right before the chart is played, when "PRESS [START] TO CHOOSE MODS" show up, do that to get the option to select your noteskin.
- "enchantment" and "enchantment-custom" folders are the noteskins with 3d models for consistent compatibility throughout NotITG modcharts. It is recommended to play with these noteskins instead of the 2d ones.
- The corresponding 2d folders are the original 2d version ported directly over. ***The 3d folders will use sprites from their corresponding 2d folders, so both have to be there.***
- You can change your default settings for NotITG by going to the NotITG game folder, and open and edit Data/GamePrefs.ini.

# Customization
- You will only be changing "enchantment-custom" and "enchantment-custom-2d", as I plan to keep "enchantment" and "enchantment-2d" as consistent folders for modcharts to reference if they want.
- Head on to the Customization folder and build your own customized noteskin. Keep opening the noteskin variant folders that you prefer until you eventually see the "enchantment-custom" and/or "enchantment-custom-2d" folders.
- Copy the "enchantment-custom" and/or "enchantment-custom-2d" folders, then paste and replace files inside the NoteSkins/dance folder, then restart the game to apply the variant.

https://github.com/user-attachments/assets/9a687f11-449d-4427-a3dd-2f0fb5fd7b50



- If you like what you have built in the enchantment-custom folders, you can duplicate those folders and rename them to whatever you want! Though do take note that ***the 3d folder will use sprites from its corresponding 2d folder***. So be sure to duplicate both the 3d and 2d folders, and remember to change the 2d folder that the 3d folder takes sprites from. Just open the metrics.ini file inside the 3d folder, and change the folder name next to FallbackNoteSkin= to that of the 2d folder.



https://github.com/user-attachments/assets/f12afc41-452e-48be-a8de-06d0e20fcb28








