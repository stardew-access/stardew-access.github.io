---
title: Mod Details
permalink: /mod-details/
---

# Mod Details <!-- omit in toc -->

This page contains details about the new feature, keybinds, commands and the mods config.

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

## Features

### Read Tile

Reads the name and information about the tile the player is currently looking (not the one the player is standing on).

**Related Commands:-**

- `readtile` = Toggle this feature. *Enabled* by default.
- `flooring` = Toggle reading floorings. *Disabled* by default.

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