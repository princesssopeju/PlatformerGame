
https://github.com/user-attachments/assets/13b65d04-270a-421d-90a9-755d44c4b122
# Princess Platformer Game

Welcome to the **Princess Platformer Game**! This project is a 2D platformer game developed in Java, where players navigate through levels, avoid hazards, defeat enemies, and complete various challenges.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Gameplay](#gameplay)
- [Project Structure](#project-structure)
- [Lessons Learned](#lessons-learned)
- [Potential Improvements](#potential-improvements)
- [Challenges Faced](#challenges-faced)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
The **Princess Platformer Game** is a Java-based 2D platformer that showcases various aspects of game development, including state management, user interface design, gameplay mechanics, and visual effects. The project is designed to be both an educational tool and an engaging game.

## Features
- **Game States:** Includes a main menu, options menu, gameplay state, and more.
- **Interactive Gameplay:** Control the player character to navigate through levels, avoid spikes, defeat enemies, and collect items.
- **Enemy AI:** Different enemy types with unique behaviors.
- **Environmental Effects:** Simulates rain and other visual effects to enhance gameplay.
- **Audio Management:** Background music and sound effects enhance the gaming experience.
- **Customizable Settings:** Players can adjust game settings like resolution and audio levels.

## Installation
To run the game locally, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/YourUsername/Princess-Platformer-Game.git

## Gameplay
Movement: Use the WASD keys to move the character.
Interacting: Use the mouse to interact with UI elements and objects in the game.
Objective: Navigate through levels, avoid hazards, defeat enemies, and complete each level to progress.

## Project Structure
The project is organized into several packages, each handling different aspects of the game:

## Screenshot
![Screenshot 2024-08-09 001221](https://github.com/user-attachments/assets/d8512fb4-499b-4782-a24d-5296324f4274)

## DEMO

https://github.com/user-attachments/assets/d64c5b05-d522-41b8-bcc7-7c9562e077c5


## Project Structure

**Main Package:** Core game loop and window management (GamePanel, GameWindow, Game, MainClass).
**Input Package:** Handles user input through keyboard and mouse (KeyboardInputs, MouseInputs).
**Utilz Package:** Utility functions for resource management and constants (HelpMethods, LoadSave, Constants).
**UI Package:** Manages UI components and overlays (GameCompletedOverlay, GameOverOverlay, AudioOptions, MenuButton, etc.).
**Levels Package:** Manages the levels and their rendering (Level, LevelManager).
**Entity Package:** Manages game entities, including the player and enemies (Enemy, Player, EnemyManager, etc.).
**Object Package:** Handles static and dynamic objects in the game world (BackgroundTree, Cannon, Projectile, ObjectManager, etc.).
**Effects Package:** Manages visual effects like rain and dialogue (Rain, DialogueEffect).
**Audio Package:** Handles audio playback (AudioPlayer).
**GameStates Package:** Manages different game states (GameOptions, State, Menu, Playing, etc.).

## Lessons Learned
Throughout the development of this project, I gained experience in various aspects of game development:

**Custom Painting in Java Swing:** Learned how to override the paintComponent method for custom rendering.
**Event Handling:** Set up keyboard and mouse event listeners to handle user input.
**State Management:** Implemented a state management system for handling different game states like the main menu and gameplay.
**Resource Management:** Managed game assets efficiently, including handling errors gracefully when resources were missing.

## Potential Improvements
Here are some areas where the game could be improved:

**Performance Optimization:** Further optimization of the rendering pipeline and object management.
**Advanced AI:** Implementing more complex behavior patterns for enemies.
**Enhanced Visuals** Adding dynamic lighting, shadows, and particle effects.
**Level Design:** Expanding the levels to include more interactive elements and puzzles.
**Audio Enhancements:** Implementing spatial audio and context-sensitive music.

## Challenges Faced
Some of the challenges faced during development include:

State Management: Ensuring smooth transitions between different game states.
Collision Detection: Balancing performance and accuracy in collision detection.
Multithreading: Implementing a multithreaded game loop while avoiding race conditions.
