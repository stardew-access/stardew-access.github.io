---
title: Mod Details
permalink: /mod-details/
---

# Mod Details <!-- omit in toc -->

This page contains details about the new feature, keybinds and commands.

*Note that the keybinds can be remapped from the config file, you follow [this](#TODO-add-this) guide.*

## Other Pages <!-- omit in toc -->

- [Home](/)
- [Setup](/mod-setup)
- [Guides](/guides)
- [Useful Coords](/useful-coords)

## Table of Content <!-- omit in toc -->

- [Features](#features)
  - [Read Tile](#read-tile)
  - [Tile Viewer](#tile-viewer)
  - [Radar](#radar)
  - [Snap Mouse](#snap-mouse)
  - [Warning](#warning)
  - [Manually Triggered](#manually-triggered)
- [Keybindings](#keybindings)
  - [Global keys](#global-keys)
  - [Chat menu keys](#chat-menu-keys)
  - [New Game or Charachter Customization menu keys](#new-game-or-charachter-customization-menu-keys)
  - [Menus With Inventory keys](#menus-with-inventory-keys)
  - [Junimo Note or Community Center Menu keys](#junimo-note-or-community-center-menu-keys)
  - [Carpenter Menu keys](#carpenter-menu-keys)
  - [Animal info menu keys](#animal-info-menu-keys)
  - [Museum Menu keys](#museum-menu-keys)
  - [Fish Pond menu keys](#fish-pond-menu-keys)
  - [Quest menu keys](#quest-menu-keys)
- [Commands](#commands)
  - [Read tile related](#read-tile-related)
  - [Radar related](#radar-related)
  - [Building related](#building-related)
  - [Other](#other)

## Features

### Read Tile

Reads the name and information about the tile the player is currently looking (not the one the player is standing on).

**Related Commands:-**

- `readtile` = Toggle this feature. *Enabled* by default.
- `flooring` = Toggle reading floorings. *Disabled* by default.
- `watered` = Toggle speaking watered or unwatered for crops. *Enabled* by default.

**Related Keybinds:-**

- `J` = Manually trigger read tile for the tile player is *looking at*.
- `Left Alt + J` = Manually trigger read tile for the tile player is *standing on*.

### Tile Viewer

Allows browsing of the map and snapping mouse to tiles with the arrow keys. This Feature can be used to place items into the world like calender.

**Releated Config:-**

- `TileCursorPreciseMovementDistance` = Default to *8*. Specifies the number of pixels the cursor should move when using precision movement i.e. with *left shift*.
- `LimitTileCursorToScreen` = Default to *false*. Toggle whether to prevent cursor from going out of screen.

**Related Keybinds:-**

- `L` = Toggles realative cursor lock i.e. if enabled, the cursor will reset when player moves.
- `Left Control + enter` = Auto walk to the tile
- `Arrow up` = Move the cursor one tile up
- `Arrow right` = Move the cursor one tile right
- `Arrow down` = Move the cursor one tile down
- `Arrow left` = Move the cursor one tile left
- `Left Shift + Arrow up` = Move the cursor up by precision i.e. pixel by pixel
- `Left Shift + Arrow right` = Move the cursor right by precision i.e. pixel by pixel
- `Left Shift + Arrow down` = Move the cursor down by precision i.e. pixel by pixel
- `Left Shift + Arrow left` = Move the cursor left by precision i.e. pixel by pixel

### Radar

Plays the sound at any point of interest nearby. This feature is not fully developed so haven't included the commads for it here as they are overwhelming.

### Snap Mouse

Snaps the mouse cursor to the adjacent tile to the player according to the direction the player is facing.

**Related Commands:-**

- `snapmouse` = Toggle this feature. *Enabled* by default.

### Warning

Warns the player when their health or stamina/energy is low. Also warns when its past midnight.

### Manually Triggered

These features are manually triggered when a certain key is pressed.

**Related Keybinds:-**

- `[ or Ctrl Enter`	= Simulate mouse left click.
- `] or Shift Enter` = Simulate mouse right click.
- `H` = Narrate health and stamina.
- `Left alt + K` = Narrate current location name.
- `K` = Narrate player position.
- `Q` = Narrate the time of day, day and date and season
- `R` = Narrate the money the player has currently.

<!-- #TODO add API -->

## Keybindings

*Note that the primary info key used in a few of the menus is default to "C" key.*


### Global keys

| Key                | Description                                                      |
| ------------------ | ---------------------------------------------------------------- |
| Left Ctrl + Enter  | Primary key to simulate mouse left click                         |
| Left Shift + Enter | Primary key to simulate mouse right click                        |
| [                  | Secondary key to simulate mouse left click                       |
| ]                  | Secondary key to simulate mouse right click                      |
| H                  | Narrate health and stamina.                                      |
| Left alt + K       | Narrate current location name.                                   |
| K                  | Narrate player position.                                         |
| Q                  | Narrates the time of day, day and date and season                |
| R                  | Narrates the money the player has currently.                     |
| Left alt + J       | Manually trigger Read Tile for the tile player is *stanfing on*. |
| J                  | Manually trigger Read Tile for the tile player is *looking at*.  |

### Chat menu keys

| Key       | Description                |
| --------- | -------------------------- |
| Page up   | Read previous chat message |
| Page down | Read next chat message     |

### New Game or Charachter Customization menu keys

| Key             | Description                                                                            |
| --------------- | -------------------------------------------------------------------------------------- |
| Right Arrow Key | Next element.                                                                          |
| Left Arrow Key  | Previous element.                                                                      |
| Enter           | Select the entered value <br/>in a text box(name, farm name <br/>& fav thing text box) |

### Menus With Inventory keys

| Key            | Description                                                                             |
| -------------- | --------------------------------------------------------------------------------------- |
| I              | Select the first item in chest inventory/crafting recipe/item to buy                    |
| Left Shift + I | Select the first item in the player's inventory                                         |
| C              | (Only in crafting page) Cycle through the available recipes in the current recipe lists |

### Junimo Note or Community Center Menu keys

| Key                 | Description                                                  |
| ------------------- | ------------------------------------------------------------ |
| I or Left shift + I | Cycle through the ingredients in the current selected bundle |
| C or Left shift + C | Cycle through the items in the player's inventory            |
| V or Left shift + V | Cycle through the ingredient input slots                     |
| P                   | Move the mouse cursor to purchase button                     |
| Backspace           | Move the mouse cursor to back button                         |

### Carpenter Menu keys

| Key                 | Description                                |
| ------------------- | ------------------------------------------ |
| Primary info key(C) | Speak the info about the current blueprint |

### Animal info menu keys

| Key                 | Description                                            |
| ------------------- | ------------------------------------------------------ |
| Primary info key(C) | For narrating animal details                           |
| Escape              | For escaping/unselecting from the animal name text box |

### Museum Menu keys

| Key                 | Description                   |
| ------------------- | ----------------------------- |
| Primary info key(C) | Donate currently hovered item |

### Fish Pond menu keys

| Key                 | Description               |
| ------------------- | ------------------------- |
| Primary info key(C) | Speak the info about pond |

### Quest menu keys

| Key                 | Description              |
| ------------------- | ------------------------ |
| Primary info key(C) | Speak current quest info |

## Commands

### Read tile related

| Command  | Description                                     |
| -------- | ----------------------------------------------- |
| readtile | Toggle Read Tile feature                        |
| flooring | Toggle reading folooring                        |
| watered  | Toggle speaking watered or unwatered for crops. |

### Radar related

| Command  | Description                                                    |
| -------- | -------------------------------------------------------------- |
| radar    | Toggle Radar feature                                           |
| rdebug   | Toggle debugging in radar feature                              |
| rstereo  | Toggle stereo sound in radar feature                           |
| rfocus   | Toggle focus mode in radar feature                             |
| rdelay   | Set the delay of radar feature in milliseconds                 |
| rrange   | Set the range of radar feature                                 |
| readd    | Add an object key to the exclusions list of radar feature.     |
| reremove | Remove an object key from the exclusions list of radar feature |
| relist   | List all the exclusions in the radar feature                   |
| reclear  | Remove all keys from the exclusions list in the radar featrure |
| recount  | Number of exclusions in the radar feature                      |
| rfadd    | Add an object key to the focus list of radar feature.          |
| rfremove | Remove an object key from the focus list of radar feature      |
| rflist   | List all the focus in the radar feature                        |
| rfclear  | Remove all keys from the focus list in the radar featrure      |
| rfcount  | Number of focus in the radar feature                           |

### Building related

| Command   | Description                                                                                         | Special Syntax (If any)                  | Argument details (If any)                                                                                                         | Example      |
| --------- | --------------------------------------------------------------------------------------------------- | ---------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- | ------------ |
| mark      | Marks the player's position for use in building cunstruction in Carpenter Menu                      | mark [Index:number]                      | Index: the index at which we want to save the position. From 0 to 9 only                                                          | mark 0       |
| marklist  | List all marked positions                                                                           |                                          |                                                                                                                                   | marklist     |
| buildlist | List all buildings for selection for upgrading/demolishing/painting                                 |                                          |                                                                                                                                   | buildlist    |
| buildsel  | Select the building index which you want to upgrade, demolish and paint.                            | buildsel [Index:number]                  | Index: the index of the building we want to select, use buildlist command to list the buildings with their index                  | buildsel 3   |
| buildsel  | Select the marked position index where we want to cunstruct the building.                           | buildsel [Index:number]                  | Index: the index of the marked position, use marklist command to list the marked positions with their index                       | buildsel 0   |
| buildsel  | Select the building index along with a index of marked position where we want to move the building. | buildsel [Index1:number] [Index2:number] | Index1: the index of the building we want to select. Index2: the index of the marked position where we want to move the building. | buildsel 3 0 |

Check the [guide](#TODO-add-this) on how to use these.

### Other

| Command    | Description                                                             |
| ---------- | ----------------------------------------------------------------------- |
| snapmouse  | Toggle Snap Mouse Feature                                               |
| hnspercent | Toggle between speaking in <br/> percentage or full health and stamina. |
| refsr      | Refreshes screen reader                                                 |
| refst      | Refreshes static tiles json file                                        |
| refmc      | Refreshes mof config json file                                          |