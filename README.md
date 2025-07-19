# 🐑 RicoSheep – Puzzle Game in Python

**RicoSheep** is a 2D grid-based puzzle game developed in Python.  
The player must guide sheep across a grid filled with obstacles to reach all the grass tiles, using keyboard controls.  
The game includes both a player mode and an AI solver mode with a graphical interface.

> 🧠 **This project was my very first programming project**, developed during the first year of my Computer Science degree. It introduced me to Python, algorithms, file I/O, recursion, and graphical interfaces.

## 🎮 Game Features

- 🐏 Move sheep using arrow keys
- 🌿 Guide all sheep to grass tiles to win
- 🌳 Bushes block movement and create obstacles
- 🧠 Solver mode with automatic solution finding using recursive search
- 🖱️ Menu system with map selection via mouse click
- 🎨 Graphical rendering using the `fltk` graphics library

## 🧠 Core Concepts

- Game logic handled via functions like:
  - `superpos` – Validates possible moves
  - `jouer` – Updates sheep positions based on direction
  - `victoire` – Checks win condition
  - `solveur` – Recursive solver that finds a path to success
- Custom level files define the initial map layout

## 🛠️ Tech Stack

- **Language**: Python 3
- **Graphics**: FLTK Python wrapper (`fltk.py`)
- **Libraries**: `PIL`, `collections`, `ImageTk`
- **OS**: Desktop (Windows/Linux)

## ▶️ How to Play

### 💻 Launch the game

1. Clone the project:
```bash
git clone https://github.com/SalimChabchoub/RicoSheep
cd ricosheep
```
2. Launch ricosheep.py:
   ```bash
   python ricosheep.py
   ```
