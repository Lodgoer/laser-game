# Turtle Space Invaders

A simple **Space Invaders–style arcade game** built with Python’s `turtle` graphics module. Control a laser cannon, shoot incoming aliens, and survive as long as you can.

This project is lightweight, beginner-friendly, and runs with **no external dependencies** beyond the Python standard library.

---

## 🎮 Gameplay Overview

* You control a laser cannon at the bottom of the screen.
* Aliens spawn at the top and move downward.
* Shoot aliens before they reach the floor.
* The game ends when any alien reaches the cannon level.

Your **score** increases for each alien destroyed, and **time survived** is tracked in real time.

---

## 🕹 Controls

|           Key | Action            |
| ------------: | ----------------- |
|  ⬅ Left Arrow | Move cannon left  |
| ➡ Right Arrow | Move cannon right |
|         Space | Fire laser        |
|             Q | Quit the game     |

---

## ⚙️ Game Mechanics

* **Frame rate:** 30 FPS for smooth animation
* **Alien spawn interval:** Every 1.2 seconds
* **Alien movement:** Constant downward speed
* **Laser behavior:**

  * Fired upward from the cannon tip
  * Removed when leaving the screen or hitting an alien
* **Collision detection:** Distance-based (laser vs alien)

---

## 🧠 Features

* Real-time score and timer display
* Random alien spawn positions and colors
* Simple but effective collision detection
* Clean separation of game logic (movement, rendering, spawning)
* Fully event-driven keyboard input

---

## 🧪 Requirements

* Python **3.8+**
* No third-party libraries required

The game uses only:

* `turtle`
* `time`
* `random`

(All included in the Python standard library.)

---

## ▶️ How to Run

1. Make sure Python is installed:

   ```bash
   python --version
   ```

2. Save the script as, for example:

   ```text
   space_invaders.py
   ```

3. Run it:

   ```bash
   python space_invaders.py
   ```

A game window will open automatically.

---

## 🧩 Project Structure (Conceptual)

* **Cannon:** Player-controlled object at the bottom
* **Lasers:** Fired projectiles stored in a list
* **Aliens:** Falling enemies spawned at intervals
* **Game loop:**

  * Updates movement
  * Checks collisions
  * Handles rendering and timing

---

## 🚀 Possible Improvements

* Add lives instead of instant game over
* Sound effects and background music
* Increasing difficulty over time
* Alien formations or movement patterns
* High-score saving

---

## 📜 License

This project is free to use for learning, experimentation, and personal projects.

---

Have fun blasting turtles from space 🐢🚀
