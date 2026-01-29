# Pygame Asteroids

A classic arcade-style **Asteroids** game built with Python and [Pygame](https://www.pygame.org/), created as part of the [Boot.dev](https://www.boot.dev/) curriculum to practice **object-oriented programming** concepts.

You control a spaceship, shoot asteroids to break them into smaller pieces, avoid collisions, and try to survive as long as possible!

## Features

- Smooth player controls (rotation, thrust, shooting)
- Asteroids that split into smaller ones when hit
- Wrap-around screen edges (fly off one side and appear on the opposite)
- Collision detection between ship, asteroids, and shots
- Clean OOP design with inheritance (circular shapes for ship/asteroids/shots)
- Modular structure for easy extension

## Project Structure
pygame-asteroids/
├─ main.py
├─ player.py
├─ asteroid.py
├─ asteroidfield.py
├─ shot.py
├─ circleshape.py
├─ constants.py
├─ logger.py
├─ pyproject.toml
├─ uv.lock
├─ .gitignore
└─ .python-version


## Requirements

- Python 3.10+ (see `.python-version`)
- Pygame (`pip install pygame`)

Dependencies are managed with [uv](https://github.com/astral-sh/uv) (see `pyproject.toml` and `uv.lock`).

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/AggroSec/pygame-asteroids.git
   cd pygame-asteroids
   ```

2. (Recommended) Install uv if you don't have it already:
   ```bash
   # macOS/Linux
   curl -LsSf https://astral.sh/uv/install.sh | sh
   ```
3. Sync dependencies:
   ```bash
   uv sync
   ```
   or if you prefer to run without uv:
   ```bash
   pip install pygame
   ```

## How to Run

```bash
# with uv
uv run main.py

# without uv
python3 main.py
```

## Controls

Left Arrow / Right Arrow → Rotate ship
Up Arrow → Thrust forward
Space → Shoot laser
Close window → Quit

## Learning Goals

This project was built while working through Boot.dev's Python curriculum to reinforce:

Classes and inheritance
Composition vs inheritance
Game loops and event handling
Basic vector math (movement, rotation, wrapping)
Collision detection algorithms

Feel free to fork it, modify it, add features (UFOs, high scores, sound effects, etc.), or use it as reference for your own Pygame projects!





