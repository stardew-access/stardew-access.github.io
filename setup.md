---
title: Setup
permalink: /setup/
---

# Setup

This is the setup guide for both smapi and stardew access. Will be adding steps for GoG and Microsoft soon alongwith steps to download it from nexus.

## Other Pages

- [Mod Details](/mod-details)
- [Getting Started](/getting-started)
- [Home](/)
- [Useful Coords](/useful-coords)

## Table of Contents

1. [Quick Links](#quick-links)
1. [Requirements](#requirements)
1. [SMAPI Installation Guide](#smapi-installation-guide)
1. [Mod Installation](#mod-installation)
1. [Instructions to Set up the Glue Your Furniture Down mod](#instructions-to-set-up-the-glue-your-furniture-down-mod)

## Quick Links

- [Source Code at GitHub](https://github.com/stardew-access/stardew-access)
- [Stardew Valley Forum](https://forums.stardewvalley.net/resources/stardew-access.88/)
- [Nexus Mods](https://www.nexusmods.com/stardewvalley/mods/10319)

## Requirements

1. SMAPI - [smapi installation guide](#smapi-installation-guide)

Here are some recommend mods but they can be kinda required:-
1. [Chat Commands](https://www.nexusmods.com/stardewvalley/mods/2092) - This mod let's us use the commands using the game's chat menu, which is opened by `T` key. You have to prepend each command with `/`. Alternatively, you can press `/` and it will open the command menu and then you won't have to prepend commands with `/`.
1. [Accessible Tiles](https://grumpycrouton.com/other/AccessibleTiles.zip) - Let's us move tile-by-tile using the arrow keys and d-pad buttons. This mod is developed by GrumpyCrouton, join the discord server to get updates for this mod as well.
1. [Auto Travel](https://www.nexusmods.com/stardewvalley/mods/10693) - Let's us mark points on map and make the player auto travel to it using a menu or commands. Also developed by GrumpyCrouton.

## SMAPI Installation Guide

1. Run Stardew Valley at least once before following the steps ahead to generate necessary files.
1. Download the [latest version](https://smapi.io/)
1. Extract the zip file and run the ` Windows.bat ` file.
1. Follow the instructions and normally it will detect the game's folder automatically.
1. If you don't want the achievements and all, you can skip the following steps and launch the `StardewModdingAPI.exe` in the game's folder.
1. Follow the steps to setup steam achievements:-
    - Go to your library and right click on stardew valley and open `properties` from the drop down menu.
    - Navigate to `Launch Options` in the `General` tab
    - Now if you have installed Stardew Valley in the default steam downloads then copy and paste the following text into the Launch Options text box.

        >"C:\Program Files (x86)\Steam\steamapps\common\Stardew Valley\StardewModdingAPI.exe" %command%
    
    - Now for those who have installed the game in some other folder the format of the text you have to copy and paste should be:

        >"\<SVPath\>\StardewModdingAPI.exe" %command%
    
        - Replace \<SVPath\>\ with the path of the Stardew Valley folder.
        - Note that `\<SVPath\>\StardewModdingAPI.exe` is surrounded by double-quotes.
        - This text is also shown in the SMAPI installer terminal window after the installation process is completed
        
*(Installation for GOG Galaxy and Xbox app will be added soon. For now you can refer to [this guide](https://stardewvalleywiki.com/Modding:Installing_SMAPI_on_Windows))*

## Stardew Accessibility Mod Installation

1. Download the [latest mod version](https://github.com/stardew-access/stardew-access/releases/latest/download/stardew-access.zip)
1. Extract the zip.
1. Move the `stardew-access` folder into the Mods folder in the `Stardew Valley` game folder. Your mod is now installed.

## Instructions to Set up the Glue Your Furniture Down mod

Once set up, this mod prevents your character from accidentally picking up the bed, fireplace, rugs and table in your house.  
We suggest you install it, because placing the bed down again is a little hard, and you will need the bed at the end of every day.

Steps:-
1. Download the [Glue Your Furniture Down Mod](https://www.nexusmods.com/stardewvalley/mods/10374)  
*(Note: You need an account to download the mods, and you can also follow the updates if you want.)*
1. To download, once you have an account, click on the link called manual, then look for the download button.  
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
