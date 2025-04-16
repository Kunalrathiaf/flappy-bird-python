# 🐦 Flappy Bird Game (Python + Pygame)

A fun Flappy Bird clone created with **Python** and **Pygame**. This version features smooth bird motion, randomly generated pipes, score tracking, accurate collision detection, and a restart option — all packed in a clean modular format without sound effects.

---

##  Features

-  Smooth bird jump animation
-  Dynamic, randomly positioned pipes
-  Accurate collision detection (pipes + ground)
-  Score tracking
-  Game over and restart screen
-  Clean, modular file structure

---

## Project Structure

flappy_bird_game/
│
├── assets/                  # Folder containing game images
│   ├── bird1.png
│   ├── bird2.png
│   ├── bird3.png
│   ├── pipe.png
│   ├── base.png
│   └── bg.png
│
├── bird.py                  # Bird class: jump, movement, animation
├── pipe.py                  # Pipe class: pipe generation, movement, collision
├── base.py                  # Base class: handles ground scrolling
├── utils.py                 # Utility functions: drawing window, score, game over
├── game.py                  # Core game logic and main loop
├── main.py                  # Entry point to start the game
└── README.md                # Project documentation

main.py: Starts the game using game_loop() from game.py.
game.py: Contains the core loop, manages bird, pipes, collisions, and restart.
bird.py: Handles bird animation, jump physics, and drawing.
pipe.py: Controls pipe spacing, movement, rendering, and collision.
base.py: Infinite scrolling ground logic.
utils.py: Responsible for drawing elements like background, pipes, bird, base, score, and game over screen.

## Controls 

Spacebar or Mouse Click: Make the bird jump
R key: Restart the game after Game Over

## Screenshots



## Developed by
@kunalrathiaf
