--- 
layout: default
title: Zelda-like
parent: Examples
permalink: examples/zelda
nav_order: 2
---

<iframe id="" src="Zelda-Build" name="" width="960" height="540" frameborder="0" marginheight="0" scrolling="no"></iframe>

Zelda-like example, non-restricted movement with the ability to attack and destroy objects.

### Controls

|         | Mouse/Keyboard | Controller |
| ------: | :-------------:  | :----------: |
|  Move   | <img src="../assets/KeyPrompts/Keyboard/W.png" width="40"> <img src="../assets/KeyPrompts/Keyboard/A.png" width="40"> <img src="../assets/KeyPrompts/Keyboard/S.png" width="40"> <img src="../assets/KeyPrompts/Keyboard/D.png" width="40"> <br> <img src="../assets/KeyPrompts/Keyboard/Arrow_Up.png" width="40"> <img src="../assets/KeyPrompts/Keyboard/Arrow_Left.png" width="40"> <img src="../assets/KeyPrompts/Keyboard/Arrow_Down.png" width="40"> <img src="../assets/KeyPrompts/Keyboard/Arrow_Right.png" width="40">| <img src="../assets/KeyPrompts/Controller/LeftStick.png" width="40"> <img src="../assets/KeyPrompts/Controller/Dpad.png" width="40">|
| Attack | <img src="../assets/KeyPrompts/Keyboard/Mouse_Left.png" width="40"> <img src="../assets/KeyPrompts/Keyboard/X.png" width="40"> <img src="../assets/KeyPrompts/Keyboard/J.png" width="40"> | <img src="../assets/KeyPrompts/Controller/X.png" width="40"> |


### Mechanics used
- `Attack`
  - One of the built-in actions.
- `Attack Direction: Facing`
  - Specify the direction the player attacks to.<br>
    In this case, the player attacks towards the direction in which they are facing.<br>
    The possible options are:
    - `Mouse/Joystick`
    - `Player Facing`
    - `Fixed`
- `Stop When Attack`
  - Specify if the player should stop moving when attacking.<br>
    It can give a retro feel to the game.