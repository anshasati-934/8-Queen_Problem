# 8 Queen Problem Solver

This project implements a solution to the classic 8 Queen Problem using the A* search algorithm and visualizes the solution using Tkinter.

## Project Overview

The 8 Queen Problem is a chess puzzle where the goal is to place eight queens on an 8x8 chessboard so that no two queens threaten each other. This means that no two queens should share the same row, column, or diagonal.

This implementation uses the A* search algorithm to find a solution and provides a step-by-step visualization of the problem-solving process.

## Features

- A* search algorithm implementation for solving the 8 Queen Problem
- Heuristic function to guide the search process
- Tkinter-based GUI for visualizing the solution
- Step-by-step display of the solution process
- Fullscreen display with scrollable canvas
- Color-coded chessboard representation

## Requirements

- Python 3.x
- Tkinter (usually comes pre-installed with Python)

## How to Run

1. Ensure you have Python installed on your system.
2. Clone this repository to your local machine.
3. Navigate to the project directory.
4. Run the following command:

   ```
   python main.py
   ```

   or if you're using a Jupyter notebook:

   ```
   jupyter notebook main.ipynb
   ```

5. The program will solve the 8 Queen Problem and display the solution in a new window.

## Implementation Details

The project consists of several key components:

1. `Node` class: Represents a state in the search space.
2. `heuristic` function: Calculates the number of conflicts in a given state.
3. `successors` function: Generates possible next states from a given state.
4. `a_star` function: Implements the A* search algorithm to find a solution.
5. `display_solution` function: Creates a Tkinter GUI to visualize the solution.

The main algorithm uses A* search to find a solution, starting from an initial state where all queens are placed in the first row. It then explores possible states, guided by the heuristic function, until it finds a state with no conflicts.

## GUI Layout

The GUI displays the following elements:

- Title and author information
- A chessboard representation of each step in the solution
- A side panel showing the step-by-step progression of queen placements
- An exit button to close the application

## Author

Ansh Asati

## License

[Include your chosen license here]

## Acknowledgements

[Include any acknowledgements or references if applicable]
