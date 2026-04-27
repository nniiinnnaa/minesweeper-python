# Minesweeper
A classic Minesweeper game built with Python and the Pygame library. Features custom graphics, breadth-first search (BFS) for auto-revealing safe zones, and a guaranteed safe-first-click mechanic.

## Features

* **Safe first click:** Mines are algorithmically generated and placed only *after* your first click, guaranteeing that you will never hit a mine on your very first move.
* **Smart reveal:** Automatically reveals adjacent empty and safe tiles using the breadth-first search algorithm.
* **Live tracking:** Keeps track of the time elapsed since the start of the game and the number of remaining mines you need to flag.

## Prerequisites

To run this game, you need to have Python 3.x installed on your computer, along with the `pygame` library.

1. **Install Python:** [Download Python](https://www.python.org/downloads/)
2. **Install Pygame:** Considering you already have pip installed, open your terminal or command prompt and run:
   ```bash
   pip install pygame
