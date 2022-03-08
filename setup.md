---
title: Setup
permalink: /setup/
---

# Setup

This is the setup guide for both smapi and stardew access. Will be adding steps for GoG soon.

## Other Pages

- [Mod Details](/mod-details)
- [Getting Started](/getting-started)
- [Home](/)
- [Useful Coords](/useful-coords)

## Table of Contents

1. [Quick Links](#quick-links)
1. [Requirements](#requirements)
1. [Recommended Mods](#recommended-mods)
1. [Additional Mods](#additional-mods)
1. [Installing SMAPI for Steam](#installing-smapi-for-steam)
1. [Installing SMAPI for Gamepass](#installing-smapi-for-gamepass)
1. [Mod Installation](#mod-installation)
1. [Instructions to Set up the Glue Your Furniture Down mod](#instructions-to-set-up-the-glue-your-furniture-down-mod)

## Quick Links

- [Source Code at GitHub](https://github.com/stardew-access/stardew-access)
- [Download Latest Version](https://github.com/stardew-access/stardew-access/releases/latest/download/stardew-access.zip)

## Requirements

1. SMAPI - [smapi installation guide](#smapi-installation-guide)

## Additional Mods

Here are some recommended mods that are not apart of Stardew Access that can improve your play experience:


1. [Glue Down Furniture mod](https://www.nexusmods.com/stardewvalley/mods/10374): Prevents you from picking up your furniture. We highly recommend installing.
1. [Chat Commands](https://www.nexusmods.com/stardewvalley/mods/2092): This mod let's us use the commands using the game's chat menu, which is opened by "T" key. You have to prepend each command with "/". Alternatively, you can press "/" and it will open the command menu and then you won't have to prepend commands with "/".
1. [Accessible Tiles](https://grumpycrouton.com/other/AccessibleTiles.zip): Allows us to move tile-by-tile using the arrow keys and d-pad buttons on a controller. This mod is developed by GrumpyCrouton, join the Stardew Access discord server to get updates for this mod as well.
1. [Auto Travel](https://www.nexusmods.com/stardewvalley/mods/10693): Allows us to mark points on map and make the player auto travel to it using a menu or commands. Also developed by GrumpyCrouton.

## Installing SMAPI for Steam

1. Run Stardew Valley at least once before following the steps ahead to generate necessary files.
1. Download the [latest version](https://smapi.io/)
1. Extract the zip file and run the "Windows.bat" file.
1. Follow the instructions and normally it will detect the game's folder automatically.
1. If you don't want the achievements and all, you can skip the following steps and launch the `StardewModdingAPI.exe` in the game's folder.
1. Follow the steps to setup steam achievements:-
    - Go to your library and right click on stardew valley and open "properties" from the drop down menu.
    - Navigate to `Launch Options` in the `General` tab
    - Now if you have installed Stardew Valley in the default steam downloads then copy and paste the following text into the Launch Options text box.

        >"C:\Program Files (x86)\Steam\steamapps\common\Stardew Valley\StardewModdingAPI.exe" %command%
    
    - For those who have installed the game in some other folder the format of the text you have to copy and paste should be:

        >"\<SVPath\>\StardewModdingAPI.exe" %command%
    
        - Replace \<SVPath\>\ with the path of the Stardew Valley folder.
        - Note that `\<SVPath\>\StardewModdingAPI.exe` is surrounded by double-quotes.
        - This text is also shown in the SMAPI installer terminal window after the installation process is completed
        
## Installing Smapi for Gamepass

1. Run Stardew Valley at least once before following the steps ahead to generate necessary files.
1. Download the [latest version](https://smapi.io/)
1. Extract the zip file and run the "Windows.bat" file.
1. Follow the instructions and normally it will detect the game's folder automatically.
1. Navigate to Stardew Valley on Gamepass and select it, then tab over to the "more actions for Stardew Valley" button.
1. Select "enable mods", then navigate to the "more actions for Stardew Valley" button again, select it, and select the "open mods folder" button.
1. Navigate to "StardewValley.exe" and rename it to StardewValleyOld.exe"., then rename "StardewModdingAPI.exe" to "StardewValley.Exe".
Now, whenever you launch Stardew Valley through Gamepass, your mods will automatically be loaded.

## Mod Installation

1. Download the [latest mod version](https://github.com/stardew-access/stardew-access/releases/latest/download/stardew-access.zip)
1. Extract the zip.
1. Move the `stardew-access` folder into the Mods folder in the `Stardew Valley` game folder. Your mod is now installed.

## Instructions to Set up the Glue Your Furniture Down mod

Once set up, this mod prevents your character from accidentally picking up the bed, fireplace, rugs and table in your house.  
We suggest you install it, because placing the bed down again is a little hard, and you will need the bed at the end of every day.

Steps:-
1. Download the [Glue Your Furniture Down Mod](https://www.nexusmods.com/stardewvalley/mods/10374)  
*(Note: You need an account to download the mods, and you can also follow the updates if you want.)*
1. To download, perform a search for "manual" and click the link, then perform a search for "slow" and click the link.
1. Once downloaded, unzip the folder,  
1. Copy the GlueFurnitureDown folder and paste it in the mods folder.  
1. Don't paste it in the accessibility mod folder, but in the mods folder.  
1. Run the game so a file called config.JSON file could be generated.  
1. Close the game.  
1. Open that file with notepad.  
1. You will see text like this:  
  "CanPickUpBed": true,  
  "CanPickUpChair": true,  
  "CanPickUpTable": true,  
  And so on. 
1. What you have to do is edit the file. If you don't want to pick up your bed and believe me you don't, change the word true with false. Don't delete anything else, just that word and replace it with false.  
1. Do the same to all the things that you don't want to pick up.  
1. Save the file and congrats, no more picking up your furniture accidentally.  
