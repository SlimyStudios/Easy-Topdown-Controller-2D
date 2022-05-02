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

### [[Movement Type: Grid]](#movement-type) Grid Size
The size of the grid, can be of arbitrary size.  
Default value: `(1, 1)`

### [[Movement Type: Grid]](#movement-type) Collides With
The layers that the player can collide with.  
Default value: `Default`

### Allow Diagonals
If the player can move diagonally.  
Default value: `true`

### Velocity
How fast the player moves.  
Default value: `5` 

### Shooter Rotation
If the player will rotate to face the mouse cursor or the right stick of a controller instead of looking to the movement direction.  
Default value: `false`


## Interact

### Can Interact
If the player can interact with other objects.  
Default value: `false`

### [[Interact]](#can-interact) Disable Animation
If the player's animation when interacting should be disabled.  
Default value: `false`

### [[Interact]](#can-interact) Animation
The animation to play when the player interacts with an object.  
Default value: `Default Animation`


## Idle

### Disable Animation
If the player's animation when idle should be disabled.  
Default value: `false`

### Animation
The animation to play when the player is in the idle state.  
Default value: `Default Animation`


## Walk

### Disable Animation
If the player's animation when walking should be disabled.  
Default value: `false`

### Animation
The animation to play when the player is walking.  
Default value: `Default Animation`


## Attack

### Can Attack
If the player can attack.  
Default value: `false`

### [[Attack]](#can-attack) Attack Direction
The direction where the player will attack.  
- **Mouse/Joystick**: The player attacks in the direction of the mouse cursor or the right stick of a controller, best used in conjunction with the `Shooter Rotation` parameter.
- **Facing**: The player attacks in the direction it's facing.
- **Fixed**: The player attacks in a fixed direction.
Default value: `Facing`

### [[Attack, Attack Direction: Fixed]](#can-attack) Direction
The direction where the player will attack when Attack Direction = Fixed.  
The value of all axis will be clamped to [-1, 1].  
Default value: `(0, 1)`

### [[Attack]](#can-attack) Stop When Attack
If the player should stop moving when attacking.  
Gives a retro feel to the attack action.  
Default value: `true`

### [[Attack]](#can-attack) Disable Animation
If the player's animation when attacking should be disabled.  
Default value: `false`

### [[Attack]](#can-attack) Animation
The animation to play when the player attacks.  
Default value: `Default Animation`


## Shoot

### Can Shoot
If the player can shoot.  
Default value: `false`

### [[Shoot]](#can-shoot) Shoot While Button Held
If the player should continue shooting while the configured "Shoot" button is held.  
Default value: `true`

### [[Shoot While Button Held]](#shoot-while-button-held) Shoot Cooldown
The cooldown between each shot.
Default value: `0.25`

### [[Shoot]](#shoot-shoot-while-button-held) Shoot Direction
The direction where the player will shoot.  
- **Mouse/Joystick**: The player shoots in the direction of the mouse cursor or the right stick of a controller, best used in conjunction with the `Shooter Rotation` parameter.
- **Facing**: The player shoots in the direction it's facing.
- **Fixed**: The player shoots in a fixed direction.
Default value: `Mouse/Joystick`

### [[Shoot, Shoot Direction: Fixed]](#can-shoot) Direction
The direction where the player will shoot when Shoot Direction = Fixed.  
The value of any axis will be clamped to [-1, 1].  
Default value: `(0, 1)`  

### [[Shoot]](#can-shoot) Disable Animation
If the player's animation when shooting should be disabled.  
Default value: `false`

### [[Shoot]](#can-shoot) Animation
The animation to play when the player shoots.  
Default value: `Default Animation`


## Roll

### Can Roll
If the player can roll.

### [[Roll, Shooter Rotation]](#shooter-rotation) Follow Movement Direction
If the player should rotate to face the movement direction when rolling.  
Only active if Shooter Rotation is enabled.  
Default value: `true`  

### [\[Roll](#can-roll)[and (Attack](#can-attack)[ or Shoot)\]](#can-shoot) Roll Interrupts Attack
If rolls should interrupt attack and shoot animations.  
Default value: `true`  

### [[Roll]](#can-roll) Roll Velocity
How fast the player rolls.  
Default value: `7.5`  

### [[Roll]](#can-roll) Disable Animation
If the player's animation when rolling should be disabled.  
Default value: `false`  

### [[Roll]](#can-roll) Animation
The animation to play when the player rolls.  
Default value: `Default Animation`  