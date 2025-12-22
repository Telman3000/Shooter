# Space Fighter — 2D Arcade Shooter (Pygame)

Space Fighter is a 2D arcade shooter developed using **Python and Pygame**.
The project represents a more advanced stage of my game development journey compared to earlier experiments.

The game features horizontal world scrolling, multiple weapon types, enemies, sound design, and complete game state management.

---

## 🎮 Gameplay Overview

The player controls a character moving through a side-scrolling level filled with enemies and obstacles.
The objective is to survive, defeat enemies, and reach the final goal.

Core gameplay features:
- Side-scrolling 2D world
- Player movement with gravity and jumping
- Multiple weapon types (pistol, shotgun)
- Ammo system and reloading mechanics
- Enemies with dynamic behavior
- Pause, restart, win and lose states
- Sound effects and background ambience

---

## 🛠 Tech Stack

- **Language:** Python  
- **Library:** Pygame  
- **Graphics:** 2D sprites  
- **Audio:** Pygame mixer  
- **Platform:** Desktop

---

## 🧩 Game Architecture

The project is structured around core game development concepts:

- `Hero` — player character logic, movement, weapons
- `Enemy` — enemy behavior and interactions
- `Bullet` / `Patron` — shooting and ammo mechanics
- `Wall` — static level geometry and collision handling
- `Princess` — level goal entity
- Central game loop managing:
  - input handling
  - physics and gravity
  - collision detection
  - world scrolling
  - game states (pause, restart, win, lose)

---

## 📸 Screenshots

<p align="center">
  <img src="https://github.com/Telman3000/Shooter1/assets/136071674/52341453-5ec4-4487-90cc-190ca47c5750" width="400"/>
</p>

<p align="center">
  <img src="https://github.com/Telman3000/Shooter1/assets/136071674/c6eaeeed-cff0-4f25-a17d-f525dddf1e33" width="400"/>
</p>

<p align="center">
  <img src="https://github.com/Telman3000/Shooter1/assets/136071674/c3fc4719-4928-4311-8473-704fed9683ef" width="400"/>
</p>

---

## ▶️ How to Run

```bash
pip install pygame
python main.py
Ensure that all required assets (images and sounds) are placed in the correct directories.

📌 Project Status
🟡 Archived / Educational Project

This project is preserved as an educational and portfolio example.
No active development is planned.

📈 What I Learned
Building a scrolling 2D game world

Managing multiple game states

Implementing weapon and reload systems

Handling physics and collisions

Structuring a larger Pygame project

Improving code organization and gameplay complexity
