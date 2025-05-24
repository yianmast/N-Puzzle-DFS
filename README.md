# N-Puzzle Solver using Depth-First Search (DFS)

This project implements a **Depth-First Search algorithm** to solve the N-Puzzle (e.g. 8-puzzle, 15-puzzle) using Python. It was created as part of an Artificial Intelligence course.

## 🔍 What It Does

- Accepts user-defined puzzle size and custom start/goal states.
- Uses DFS to explore state space and find a solution path.
- Prints each step from initial to goal state, showing how the blank tile (`0`) moves.

## 📂 Files

- `solver.py`: Contains core logic for DFS, legal moves, child generation, and backtracking path.
- `puzzle.py`: Runs the solver and prints step-by-step state transitions.
- `example_input.txt`: Example puzzle input format for reference (optional).
- `assets/puzzle_demo.gif`: Demo showing solution steps (optional).

## ▶️ How to Run

Make sure Python 3 is installed.

Run python puzzle.py


You’ll be prompted to enter:

Puzzle size (e.g., 3 for a 3x3 puzzle)
Start state (row-by-row)
Goal state (row-by-row)
