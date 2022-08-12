---
title: Mod Setup
permalink: /mod-setup/
---

# Mod Setup <!-- omit in toc -->

This is the setup guide for both smapi(the mod handler for stardew vallet) and stardew access.

## Other Pages <!-- omit in toc -->

- [Home](/)
- [Mod Details](/mod-details)
- [Guides](/guides)
- [Useful Coords](/useful-coords)

## Table of Contents <!-- omit in toc -->

- [Quick Links](#quick-links)
- [SMAPI setup](#smapi-setup)
  - [Configuring the game client](#configuring-the-game-client)
    - [For Steam](#for-steam)
    - [For GOG Galaxy](#for-gog-galaxy)
  - [Xbox Setup](#xbox-setup)
- [Mod Installation](#mod-installation)
- [Other Mods](#other-mods)
  - [Essential](#essential)
  - [Recommend](#recommend)

## Quick Links

- [Access for All Website](https://a4a-mods.com/) - developed by [GrumpyCrouton](https://a4a-mods.com/mods/user?user_id=2)
- [Stardew Access Page](https://a4a-mods.com/mods/details?uid=2#)
- [SMAPI website](https://smapi.io/)
- [Latest SMAPI Release Page](https://github.com/Pathoschild/SMAPI/releases/latest)
- [All Stardew Access Releases](https://github.com/stardew-access/stardew-access/releases)

## SMAPI setup

*Note: Follow the [Xbox Setup](#xbox-setup) if using the xbox/gamepass version of the game.*

1. Before installing SMAPI, run the game at least once.
2. Download the [latest version of SMAPI](https://smapi.io/).
3. Extract the .zip file somewhere. (Your downloads folder is fine.)
4. For Windows users, double-click `install on Windows.bat`, and follow the on-screen instructions. At this point, you can run the `StardewModdingAPI.exe` which will be generated in your game folder. If you want the game clients to lauch the game through this file automatically and to enable features like tracking and awards, go to [configuring the game client](#configuring-the-game-client)
5. For Linux users, run the `install on Linux.sh` file, and follow the on-screen instructions.
   - if you've installed steam through flatpak, follow [this](#TODO-add-link-here) guide.
   - if the installer asks for game folder path, follow [this](#TODO-add-link-here) guide.

(Credit: for [windows](https://stardewvalleywiki.com/Modding:Installing_SMAPI_on_Windows) and for [linux](https://stardewvalleywiki.com/Modding:Installing_SMAPI_on_Linux))

### Configuring the game client

*(Skip if you are on linux, this process is not required for linux users.)*

Configuring the game client is not a necessary step, only do this if you want the tracking and awards from the client.

#### For Steam

1. Open the `properties` for Stardew (you can do this by right clicking the game in the library and then selecting `properties` from the drop down list)
2. Go to the `Launch Options` in the `General` tab and paste the following line:
   - `"{Stardew Valley Folder path}\StardewModdingAPI.exe" %command%`
   - Replace the `{Stardew Valley Folder path}` with the correct path.
   - Default for most users is: `"C:\Program Files (x86)\Steam\steamapps\common\Stardew Valley\StardewModdingAPI.exe" %command%`
 
#### For GOG Galaxy

1. Open Notepad and paste in the following: 
   - `start "" "{Stardew Valley Folder path}\StardewModdingAPI.exe"`
   - Replace the `{Stardew Valley Folder path}` with the correct path.
   - Default for most users is: `start "" "C:\Program Files (x86)\GOG Galaxy\Games\Stardew Valley\StardewModdingAPI.exe"`
2. Save the file with the name `start.bat` into the Stardew Valley folder. Make sure to change `Save as type` to `all files` when saving.
3. In the GOG Galaxy client, click on Stardew Valley > settings icon > Manage installation > Configure.
4. In the menu that appears, enable the `Custom executables / arguments` checkbox.
5. Click Add another `executable / arguments`.
6. Choose `start.bat` in the window that appears and click Open.
7. Enable the `Default Executable` radio button under the File 2 section you just added, and click OK.


### Xbox Setup

**Before you install SMAPI:**

1. Open the Stardew Valley section in the Xbox app.
2. Click the `3 dots button` (should be next to the share button) then `Manage button`
3. Click the `Files tab` and then `Browse button` to open your game folder
4. Open the Stardew Valley > Content folder. You should see a lot of files with names like api-ms-win-core-*
5. Copy the full path from the address bar at the top.

**Run the SMAPI installer:**

Run the SMAPI installer like usual, but:
- Download the installer to somewhere that's not the game directory (like your downloads folder).
- When it asks where to install, enter the path you copied from the previous step. (In cmd, you can either `right click` or `Ctrl V` to paste)

**After you install SMAPI:**

In your game folder:
1. rename `Stardew Valley.exe` to another name such as `Stardew Valley original.exe`
2. make a copy of `StardewModdingAPI.exe` and name the copy `Stardew Valley.exe`
3. That's it! Now just launch the game through the Xbox app to play with mods. 
   
*Note that when the game updates, you'll need to redo the last two sections.*

## Mod Installation

1. Download the [latest version.](https://a4a-mods.com/mods/details?uid=2#/downloads)
2. Extract the zip file (extracting it into the download folder should be fine).
3. Copy/Cut the generated `stardew-access` folder.
4. Paste it into the `Mods` folder in your game folder.
5. These instructions are same for most of the mods.

## Other Mods

### Essential

- [Accessible Tiles](https://a4a-mods.com/mods/details?uid=3) - developed by [GrumpyCrouton](https://a4a-mods.com/mods/user?user_id=2), adds grid movement and object tracking features
- [Auto Travel](https://a4a-mods.com/mods/details?uid=1) - developed by [GrumpyCrouton](https://a4a-mods.com/mods/user?user_id=2), allows you to create custom travel points, which you can fast travel to from anywhere.
- [Wasteless Watering](https://a4a-mods.com/mods/details?uid=5) - also developed by [GrumpyCrouton](https://a4a-mods.com/mods/user?user_id=2), you will no longer waste water on non-soil tiles
- [Chat Commands](https://www.nexusmods.com/stardewvalley/mods/2092) - makes it so you can enter commands from chat directly

### Recommend

- [Glue Down Furniture](https://www.nexusmods.com/stardewvalley/mods/10374) - Prevents you from picking up your furniture. We highly recommend installing.
