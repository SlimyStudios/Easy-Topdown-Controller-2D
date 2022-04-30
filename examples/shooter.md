--- 
layout: default
title: Top-down Shooter
parent: Examples
permalink: examples/shooter
nav_order: 4
---

<iframe id="" src="Shooter-Build" name="" width="960" height="540" frameborder="0" marginheight="0" scrolling="no"></iframe>

Top-down shooter example, dodge the enemy bullets while shooting at them.

### Controls

|         | Mouse/Keyboard | Controller |
| ------: | :-------------:  | :----------: |
|  Move   | <img src="../assets/KeyPrompts/Keyboard/W.png" width="40"> <img src="../assets/KeyPrompts/Keyboard/A.png" width="40"> <img src="../assets/KeyPrompts/Keyboard/S.png" width="40"> <img src="../assets/KeyPrompts/Keyboard/D.png" width="40"> <br> <img src="../assets/KeyPrompts/Keyboard/Arrow_Up.png" width="40"> <img src="../assets/KeyPrompts/Keyboard/Arrow_Left.png" width="40"> <img src="../assets/KeyPrompts/Keyboard/Arrow_Down.png" width="40"> <img src="../assets/KeyPrompts/Keyboard/Arrow_Right.png" width="40">| <img src="../assets/KeyPrompts/Controller/LeftStick.png" width="40"> <img src="../assets/KeyPrompts/Controller/Dpad.png" width="40">|
| Shoot | <img src="../assets/KeyPrompts/Keyboard/Mouse_Right.png" width="40"> | <img src="../assets/KeyPrompts/Controller/RT.png" width="40"> |
| Aim | Mouse cursor | <img src="../assets/KeyPrompts/Controller/RightStick.png" width="40"> |
| Dodge | <img src="../assets/KeyPrompts/Keyboard/Space.png" width="40"> <img src="../assets/KeyPrompts/Keyboard/Mouse_Left.png" width="40"> | <img src="../assets/KeyPrompts/Controller/LT.png" width="40"> <img src="../assets/KeyPrompts/Controller/LB.png" width="40"> |

### Mechanics used
- `Shoot` and `Dodge`
  - Built-in actions.
- `Shoot While Button Pressed`
  - Keep shooting if the shoot button is held down, but only if a certain amount of time has passed.
- `Shoot Direction: Mouse/Joystick`
  - Specify the direction the player shoots in.<br>
    In this case, the direction is set to `Mouse/Joystick`, so the player can aim their gun with the mouse/joystick.<br>
    The possible options are:
    - `Mouse/Joystick`
    - `Player Facing`
    - `Fixed`
- `Shooter Rotation`
  - Makes the player face the mouse cursor (or the right stick on a controller).<br>
    Instead of rotating the player transform, it changes to the sprite corresponding on the direction the player is facing.
- `Roll Interrupts Attack`
  - If enabled, the player will be able to roll while attacking.<br>
    This will interrupt the attack animation and make the shooting smoother.
- `Roll Follows Movement Direction`
  - If enabled, instead of dodging towards the direction the player is facing, the player will roll towards the direction they are moving.