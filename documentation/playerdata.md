---
layout: default
title: Player Data
parent: Documentation
permalink: documentation/playerdata
nav_order: 1
---

# Player Data
Contains all the configuration of the controller.  
It's a Scriptable Object, so it can be switched at any time, or even copied to other projects.

To create one, go to the Project view, right click and choose `Create > Easy TopDown Controller 2D > Player Data`.  
This will generate a new Scriptable Object with the default values.

Select it to see all the parameters in the inspector.

In the documentation below, when a parameter is defined as "[*Other Param*] Parameter", it will be only available if *Other Param* is enabled.  
Possible values will be shown as a dotted list.

## Movement Parameters
### Movement Type
- **Normal**: The player can move freely, without any restrictions.
- **Grid**: The player can only move in a grid-like pattern.  
  IMPORTANT: You **must** set all tile-based colliders to polygon (instead of outline) for the collisions to work properly.

### [[Grid]](#movement-type) Grid Size
The size of the grid, can be of arbitrary size.  
Default value: `(1, 1)`

### [[Grid]](#movement-type) Collides With
The layers that the player can collide with.
Default value: `Default`

### Allow Diagonals
If the player can move diagonally.  
Default value: `true`

### Velocity
How fast the player moves.  
Default value: `5` 