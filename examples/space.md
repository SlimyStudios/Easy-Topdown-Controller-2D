--- 
layout: default
title: Shoot'em up
parent: Examples
permalink: examples/space
nav_order: 3
---

<iframe id="" src="Space-Build" name="" width="960" height="540" frameborder="0" marginheight="0" scrolling="no"></iframe>

Shoot'em up example, avoid the asteroids and shoot to push them away.

### Controls

|         | Mouse/Keyboard | Controller |
| ------: | :-------------:  | :----------: |
|  Move   | <img src="../assets/KeyPrompts/Keyboard/W.png" width="40"> <img src="../assets/KeyPrompts/Keyboard/A.png" width="40"> <img src="../assets/KeyPrompts/Keyboard/S.png" width="40"> <img src="../assets/KeyPrompts/Keyboard/D.png" width="40"> <br> <img src="../assets/KeyPrompts/Keyboard/Arrow_Up.png" width="40"> <img src="../assets/KeyPrompts/Keyboard/Arrow_Left.png" width="40"> <img src="../assets/KeyPrompts/Keyboard/Arrow_Down.png" width="40"> <img src="../assets/KeyPrompts/Keyboard/Arrow_Right.png" width="40">| <img src="../assets/KeyPrompts/Controller/LeftStick.png" width="40"> <img src="../assets/KeyPrompts/Controller/Dpad.png" width="40">|
| Shoot | <img src="../assets/KeyPrompts/Keyboard/Mouse_Left.png" width="40"> <img src="../assets/KeyPrompts/Keyboard/X.png" width="40"> <img src="../assets/KeyPrompts/Keyboard/J.png" width="40"> | <img src="../assets/KeyPrompts/Controller/X.png" width="40"> |


### Mechanics used
- `Shoot`
  - One of the built-in actions.
- `Shoot While Button Pressed`
  - Keep shooting if the shoot button is held down, but only if a certain amount of time has passed.
- `Disable Animation`
  - This example disables the Shoot animation as it's not needed.<br>
    Instead, the Walk and Idle animations continue playing. 
- `Shoot Direction: Fixed`
  - Specify the direction the player shoots in.<br>
    In this case, the direction is set to be `Fixed`, and upwards.<br>
    The possible options are:
    - `Mouse/Joystick`
    - `Player Facing`
    - `Fixed`