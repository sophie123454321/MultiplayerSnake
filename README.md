# 2-Player Snake Game (Java)

A classic Snake game implemented in Java with **support for two players**, featuring boosts, obstacles, and a save/load system.  
This project demonstrates game logic, real-time input handling, and modular Java project organization.

---

## Features
- Two-player mode with independent controls
- Boosts that increase speed or score
- Save and load game state to continue sessions
- Collision detection for walls, self, and other player
- Modular code structure for easy expansion

---

## Project Structure
MULTIPLAYERSNAKE/
├── src/ 
├── assets/ 
├── saves/ 
├── README.md
└── .gitignore
- src/ contains all game logic and helper classes  
- assets/ contains images or sounds used in the game  
- saves/ stores runtime-generated game saves

---

## How to Run
1. Clone or download the repository
2. Make sure Java (JDK 8 or newer) is installed
3. Compile the source files
4. Run 'Main.java'

---

## Controls
* Player 1: W/A/S/D keys  
* Player 2: Arrow keys  
* S: open settings
* ESC: close game
* Boosts and other game mechanics can be modified in the settings

---

## Save System
- Game settings are automatically saved upon exit 
- Save files are not included in the repository

---

## What I Learned
- Handling real-time input for multiple players
- Efficient game loop design with proper timing and frame control
- Collision detection and object management
- Writing modular code for game logic, boosts, and scoring
- Implementing graphics rendering logic for smooth updates and screen redraws
- Structuring a moderately complex project into clear folders and packages

---

## Future Improvements
- Add AI-controlled opponents
- Networked multiplayer for remote play
- Enhanced graphics or custom skins
- More advanced boost mechanics or power-ups, such as projectile-based weapons

---

## License
This project is provided for educational and demonstration purposes.