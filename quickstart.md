---
layout: default
title: Quick start guide
has_children: true
permalink: examples
nav_order: 3
---

# Quick start guide
1. Go to the Asset Store window on the Unity Editor and import the package. You can import it on an existing project, or create a new one.  

2. Once completed, a message will appear, saying that the asset has 

3. Create a new Game Object or use an existing one for the player.

4. Add a collider of any sort to the player, as it's needed for the proper functioning of the controller.

5. Add the Easy Top-Down Controller 2D script to the player.

6. Create a new Player Data Scriptable Object and assign it to the player.  
   To create a Player Data, go to the Project view, right click and choose `Create > Easy TopDown Controller 2D > Player Data`.

7. Open the Scriptable Object to edit the controller parameters.

8. Choose what kind of movement you want to use (free or grid-based).

9.  Enable all the actions you want your player to be able to use (interact, attack, shoot, roll).

10. Create all the animations needed for each action (idle and walk too).  
    To create an animation asset, go to the Project view, right click and choose `Create > Easy TopDown Controller 2D > Animation`.

11. Each animation has a "Time" field, which is the time it will take to play the animation.  
    You can change this value to make the animation faster or slower.  
    Also, you need to add the sprites you want to use to the corresponding directions (marked with "Right", "Left", etc).

12. Once everything is done, you can hit "Play" and the player will move as expected!
