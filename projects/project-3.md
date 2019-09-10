---
layout: project
type: project
title: Android Games with Unity
date: 2014-05-17
labels:
  - Unity
  - C#
summary: I created three games for Android using the Unity game engine.
---
During my time at Heald College, I took the time to try my hand at using the Unity game engine and Blender3D to create relatively simple games. it took a while to get them working, but at the same time, it was a rewarding experience as to what I would be able to do later on. Two of those games used 3Dmodels I created myself using Blender with textures edited using GIMP. While simple in nature, it took a lot of coding to get right due to my relative inexperience in working with 3D models.

The first game I was known as PaperFlier and was by far one of the most complicated. The basic premise was simply getting a paper plane through holes in a wall. To that end, I created nine walls, each with a gap large enough for the paper plane to fly through. I set them up with an object that spawns a random one a certain distance away from the player and move toward the player at a speed determined by the player's score. Because I set up the walls to move toward the player, I set the paper plane up so that it is mostly stationary along one axis while freedom of movement is available on the others. Then I set up GUIthat consists of two concentric circles where the player can touch and move the inner circle. By limiting the inner circle's movement to inside the outer circle, I was able to use that as a rough quivalent of a joystick, which I was able to map the paper airplane's movement to. After that I modified the walls to give a point each time a player successfully clears the wall while also passing a "GAME OVER" if the player hits it. It was a difficult one to pull off, especially as I didn't know much about object-oriented programming at the time.

The second game I made with Unity was a simple 2D four-by-five sheet of bubble wrap. It wasn't really a game per se, but it used a nested array of "bubbles" that "popped" whn you touched one and reappeared after around half a second later. This one used objects, the bubbles, that was scaled to the size of the screen so th amount of bubbles would stay the same. When it was pressed, the method used was to make the color change, disable touch interaction for half a second, and play a sound. Very simple.

The third game was also simple by comparison. It was basically Russian Roulette.

