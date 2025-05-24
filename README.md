# N-Puzzle Solver using Depth-First Search (DFS)

This project implements a **Depth-First Search algorithm** to solve the N-Puzzle (e.g. 8-puzzle, 15-puzzle) using Python. It was created as part of an Artificial Intelligence course.

## 🔍 What It Does

- Accepts user-defined puzzle size and custom start/goal states.
- Uses DFS to explore state space and find a solution path.
- Prints each step from initial to goal state, showing how the blank tile (`0`) moves.

## 📂 Files

- `solver.py`: Contains core logic for DFS, legal moves, child generation, and backtracking path.
- `puzzle.py`: Runs the solver and prints step-by-step state transitions.
- `example_input.txt`: Example puzzle input format for reference.
- `sample.docx` : Screenshot of sample inputs and outputs

## ▶️ How to Run

Make sure Python 3 is installed.

Run python puzzle.py


You’ll be prompted to enter:

Puzzle size (e.g., 3 for a 3x3 puzzle)
Start state (row-by-row)
Goal state (row-by-row)

## Example Input

Enter size of tile puzzle (integer greater that 0): 3  

Enter start state row by row (numbers delimited by white space):   
Enter Start state: row 1 : 1 2 3  
Enter Start state: row 2 : 4 0 6  
Enter Start state: row 3 : 7 5 8  

Enter goal state row by row (numbers delimited by white space):   
Enter Goal state: row 1 : 1 2 3  
Enter Goal state: row 2 : 4 5 6  
Enter Goal state: row 3 : 7 8 0  

## 📦 Dependencies
Python Standard Library (queue is built-in for Python 3+)

If you're using an older Python version and encounter issues, refer to the official packaging guide

## 🧠 Concepts Used
DFS (Depth-First Search)
Tree traversal
Backtracking
Puzzle state representation (1D list)
AI search algorithms

## 🧑‍💻 Author
Ioannis Mastoras
Created for AI coursework – March 2020

## 📝 License
This project is licensed under the MIT License.
