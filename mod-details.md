---
title: Mod Details
permalink: /mod-details/
---

# Mod Details

## Description

A mod that adds screen reader and keyboard only support for windows. Trying to make the game more accessible.

You can post issues or suggestions in GitHub or Discord. I prefer Discord.

| [Discord](https://discord.gg/yQjjsDqWQX) | [GitHub Discussions](https://github.com/stardew-access/stardew-access/discussions) | [GitHub Issues](https://github.com/stardew-access/stardew-access/issues)

## Other Pages

- [Setup](/setup)
- [Getting Started](/getting-started)
- [Home](/)
- [Useful Coords](/useful-coords)

## Table of Content

1. [New Keybindings](#new-keybindings)
    - [Global Keys](#global-keys)
    - [New Game or Charachter Customization menu keys](#new-game-or-charachter-customization-menu-keys)
    - [Menus With Inventory keys](#menus-with-inventory-keys)
    - [Junimo Note or Community Center Menu](#junimo-note-or-community-center-menu)
    - [Carpenter Menu key](#carpenter-menu-key)

## New Keybindings

### Global keys

| Key | Description |
| --- | ----------- |
| H | Narrate health and stamina. |
| K | Narrate player position. |
| [ or Ctrl Enter | Simulate mouse left click |
| ] or Shift Enter | Simulate mouse right click |
| Q | Narrates the time of day, day and date and season |
| R | Narrates the money the player has |
| J | Manually trigger Read Tile |

### New Game or Charachter Customization menu keys

| Key | Description |
| --- | ----------- |
| Right Arrow Key | (only for new game menu) Next UI element. |
| Left Arrow Key | (only for new game menu) Previous UI  |

### Menus With Inventory keys

| Key | Description |
| --- | ----------- |
| I | Select the first item in chest inventory/crafting recipe/item to buy |
| Shift I | select the first item in the player's inventory |
| C | (Only in crafting page) Cycle through the available recipies in the current recipe lists |

### Junimo Note or Community Center Menu

| Key | Description |
| --- | ----------- |
| I | Cycle through the ingredients in the current selected bundle |
| C | Cycle through the items in the player's inventory |
| V | Cycle through the ingredient input slots |
| P | Move the mouse cursor to purchase button |
| Backspace | Move the mouse cursor to back button |

### Carpenter Menu key

| Key | Description |
| --- | ----------- |
| B | Speak the info about the current blueprint |

## New Commands

| Command | Description | Special Syntax (If any) | Argument details (If any) | Example |
| --- | ----------- | --- | --- | --- |
| readtile | Toggle Read Tile feature | | | readtile |
| radar | Toggle Radar feature | | | radar |
| rdebug | Toggle debugging in radar feature | | | rdebug |
| rstereo | Toggle stereo sound in radar feature | | | rstereo |
| rfocus | Toggle focus mode in radar feature | | | rfocus |
| rdelay | Set the delay of radar feature in milliseconds | rdelay [Delay:milliseconds] |  Delay: In milliseconds, should be atleast 1 second or 1000 millisecond | rdelay 1200 |
| rrange | Set the range of radar feature | rrange [Range:number] | Range: it should be atleast 2 and maximum 10 | rrange 3 |
| mark | Marks the player's position for use in building cunstruction in Carpenter Menu | mark [Index:number] | Index: the index at which we want to save the position. From 0 to 9 only | mark 0 |
| marklist | List all marked positions | | | marklist |
| buildlist | List all buildings for selection for upgrading/demolishing/painting | | | buildlist |
| buildsel | Select the building index which you want to upgrade, demolish and paint. | buildsel [Index:number] | Index: the index of the building we want to select, use buildlist command to list the buildings with their index | buildsel 3 |
| buildsel | Select the marked position index where we want to cunstruct the building. | buildsel [Index:number] | Index: the index of the marked position, use marklist command to list the marked positions with their index | buildsel 0 |
| buildsel | Select the building index along with a index of marked position where we want to move the building. | buildsel [Index1:number] [Index2:number]| Index1: the index of the building we want to select. Index2: the index of the marked position where we want to move the building. | buildsel 3 0 |
| snapmouse | Toggle Snap Mouse Feature | | | snapmouse |
| refsr | Refreshes screen reader | | | refsr |

## Features

1. Screen Reader:- It supports NVDA and JAWS currently.
1. Keyboard-Only:- The mod adds two keybindings to simulate mouse clicks via AutoHotKey. Although sometimes it does not registers the click so you have to click multiple times in that case.
1. Read Tile(experimental):- This feature reads the objects and NPCs at the current grab/tool hit tile. Also reads the crop's name. Use `read_tile` command to toggle it. It also says `Colliding` if the player is stuck by any houses or map boundaries. This feature is `enabled` by default. You can also manually trigger this feature with `J`.
1. Dialogue Narrator:- It narrates the dialogues at the screen. there is a know bug in this feature in which certain dialogues gets repeated infinitely.
1. Snap Mouse:- This feature snaps mouse to the focused tile's position. Use `snap_mouse` to toggle it. This feature is `enabled` by default.
1. Time and Day Narraotr:- It narrates current the time of day, day, date and season. The keybind for this is `Q`.
1. Money Narrator:- It narrates the money you have. The keybind for this is `R`.

## Future Features

1. Sound Cues for nearby objects, npc, copper stones in mines, etc.
1. More accessible menus.