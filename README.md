Slime Skirmish

A 2-dimensional video game I developed on the game engine Unity in C#

---

GAMEPLAY

The premise of the game is you are a character in a clearing in a forest with a gun, and "slime" monsters spawn from the forest and try to kill you.

If they touch you, you die. You can point and click with your mouse to aim and shoot your gun to kill the slimes.

There is a timer at the top of the screen tracking how long you've lived for.

There are 4 difficulty levels: easy, medium, hard, impossible

---

HOW I MADE SLIME SKIRMISH

MAP

To begin, I designed the pixelated forest map using assets from the Unity Asset Store.

The forest clearing is populated with rocks, rivers, and shrubbery.

CHARACTER

Next, I designed the player's controllable character. Again, I used assets from the Unity Asset Store to bring a cute, white character to life with idle and running animations. The player can move up, down, left, right, and the diagonals between using WASD or the arrow keys.

Then I gave the character a gun that shoots a bullet in the direction of the mouse on click.

SLIME MONSTERS

Next, I designed 3 species of slime monster taken from the Unity Asset Store, each with different size and speed.

I set ~40 spawnpoints hidden within the forest that spawn slimes at a randomly, at an average rate determined by the difficulty level.

The slime monsters are programmed with A.I. pathing, so they walk around obstacles on the map such as trees, shrubbery, and bodies of water.

POINT SYSTEM

Lastly, I implemented a simple stopwatch at the top of the screen, tracking how long the player has lived for.

The player also has the option to ramp up the difficulty, although it has no affect on the point system (survival time) of the game. It is merely for the purpose of making the game more challenging for fun.
