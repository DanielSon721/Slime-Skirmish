# 🧪 Slime Skirmish

*A 2-dimensional video game I developed on the Unity game engine using C#.*

---

## 🎮 Gameplay

You are dropped in a clearing in a forest, armed with a gun, and **slime** monsters emerge from the forest and try to kill you.

**Objective**: Survive for as long as possible

**Controls**:
  - WASD/Arrow keys - Move in 8 directions
  - Mouse - Aim
  - Click - Shoot

**4 difficulty levels**:
  - Easy  
  - Medium  
  - Hard  
  - Impossible

---

## 🛠️ How I Made Slime Skirmish

### 🌲 Map

To begin, I designed the pixelated forest map using assets from the Unity Asset Store.  
The forest clearing is populated with **rocks**, **rivers**, and **shrubbery**.

### 👤 Character

Next, I designed the player's controllable character.  
Again, I used assets from the Unity Asset Store to bring a cute, white character to life with idle and running animations.  
The player can move **up, down, left, right**, and the diagonals between using **WASD** or the **arrow keys**.

Then I gave the character a **gun** that shoots a bullet in the direction of the mouse on click.

### 🧟 Slime Monsters

Next, I designed **3 species** of slime monster taken from the Unity Asset Store, each with different **size** and **speed**.

I set approximately **40 spawn points** hidden within the forest that spawn slimes randomly, at an average rate determined by the difficulty level.

The slime monsters are programmed with **A.I. pathing**, so they walk around obstacles on the map such as trees, shrubbery, and bodies of water.

### 🕐 Point System

Lastly, I implemented a simple **stopwatch** at the top of the screen, tracking how long the player has lived for.

The player also has the option to **ramp up the difficulty**, although it has no effect on the point system (survival time) of the game. It is merely for the purpose of making the game more challenging for fun.
