---
title: Mod Details
permalink: /mod-details/
---

# Mod Details

## Description

A mod that adds screen reader and keyboard only support for windows. Trying to make the game more accessible.

You can post issues or suggestions in GitHub or Discord. I prefer Discord.

| [Discord](https://discord.gg/yQjjsDqWQX) | [GitHub](https://github.com/stardew-access/stardew-access) |

## Other Pages

- [Setup](/setup)
- [Getting Started](/getting-started)
- [Home](/)
- [Useful Coords](/useful-coords)

## Requirements

- [SMAPI](https://stardewvalleywiki.com/Modding:Installing_SMAPI_on_Windows)
- [AutoHotKey](https://www.autohotkey.com/)

## New Keybindings

- H = Narrate health and stamina.
- K = Narrate player position.
- [ or Ctrl Enter = Simulate mouse left click
- ] or Shift Enter = Simulate mouse right click
- Right Arrow Key = (only for new game menu) Next UI element.
- Left Arrow Key = (only for new game menu) Previous UI element.
- Q = Narrates the time of day, day and date and season
- R = Narrates the money the player has
- J = Manually trigger Read Tile

## New Commands

- read_tile = Toggle Read TIle feature
- snap_mouse = Toggle Snap Mouse Feature
- ref_sr = Refreshes screen reader

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