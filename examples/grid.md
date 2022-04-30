--- 
layout: default
title: RPG Maker-like
parent: Examples
permalink: examples/grid
nav_order: 1
---

<iframe id="" src="Grid-Build" name="" width="960" height="540" frameborder="0" marginheight="0" scrolling="no"></iframe>

RPG Maker-like example, a grid-based game with the possibility to interact with objects.

### Controls

|         | Mouse/Keyboard | Controller |
| ------: | :-------------:  | :----------: |
|  Move   | <img src="../assets/KeyPrompts/Keyboard/W.png" width="40"> <img src="../assets/KeyPrompts/Keyboard/A.png" width="40"> <img src="../assets/KeyPrompts/Keyboard/S.png" width="40"> <img src="../assets/KeyPrompts/Keyboard/D.png" width="40"> <br> <img src="../assets/KeyPrompts/Keyboard/Arrow_Up.png" width="40"> <img src="../assets/KeyPrompts/Keyboard/Arrow_Left.png" width="40"> <img src="../assets/KeyPrompts/Keyboard/Arrow_Down.png" width="40"> <img src="../assets/KeyPrompts/Keyboard/Arrow_Right.png" width="40">| <img src="../assets/KeyPrompts/Controller/LeftStick.png" width="40"> <img src="../assets/KeyPrompts/Controller/Dpad.png" width="40">|
| Interact | <img src="../assets/KeyPrompts/Keyboard/Mouse_Left.png" width="40"> <img src="../assets/KeyPrompts/Keyboard/X.png" width="40"> <img src="../assets/KeyPrompts/Keyboard/J.png" width="40"> | <img src="../assets/KeyPrompts/Controller/A.png" width="40"> |


### Mechanics used
- `Interact`
  - One of the built-in actions.
- `Movement Type`
  - Specify the type of movement the player can make.<br>
    In this case, the player can only move in a grid, like a Pokémon game.<br>
    The possible options are:
    - `None`
    - `Straight`
    - `Diagonal`
    - `All`