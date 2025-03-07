# Sudoku Solver

A Python-based Sudoku solver using the **Pygame** library. This project provides a graphical interface to solve Sudoku puzzles using a **backtracking algorithm**.

## Features

- Interactive Sudoku board with **GUI**.
- Solves puzzles using **backtracking**.
- Allows users to enter their own puzzles.
- **Real-time visualization** of the solving process.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sudoku-solver.git
   cd sudoku-solver

2. **Install the required packages**:
   ```bash
   pip install pygame
   ```

## Usage

1. **Run the game**:
   ```bash
   python SudokuGUI.py
   ```

2. **Controls**:
   - Click on a tile to select it.
   - Use number keys (1-9) to input a number in the selected tile.
   - Press `Backspace` or `Delete` to remove a number from a tile.
   - Press `Enter` to confirm the number in the selected tile.
   - Press `H` to get a hint.
   - Press `Space` to solve the puzzle automatically.

## Project Structure
- `SudokuGUI.py`: Contains the main game logic and GUI implementation.
- `sudokutools.py`: Contains utility functions for generating and solving Sudoku puzzles.

## Acknowledgments
- This project uses the Pygame library for rendering the game interface.
