# CS 351 Lab Task - Number Guessing Game

Welcome to the repository for the CS 351 lab task! This repository contains implementations of a number guessing game using different algorithms for guessing the number. The objective of this lab is to explore and implement various search strategies to solve the guessing game problem.


## Requirements

- Python 3.x
- No additional libraries are required.

## Contributing

If you wish to contribute to this repository or suggest improvements, please fork the repository and submit a pull request with your changes. Ensure your changes are well-documented and tested.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, please contact [your-email@example.com](mailto:your-email@example.com).

---

Thank you for checking out this lab task implementation. Happy coding!


AI Genetic Algorithm Number Guessing Game

This project implements an AI-powered number guessing game using a Genetic Algorithm (GA). In this game, the AI attempts to guess a number selected by the player using principles from evolutionary algorithms such as crossover, mutation, and selection.

How the Genetic Algorithm Works:

Population: The AI starts with a population of random guesses.

Fitness: Each guess is evaluated based on how close it is to the target number, using a fitness function.

Crossover: The best guesses (parents) are combined to produce new guesses (children).

Mutation: The children may undergo small mutations to introduce randomness and explore other possibilities.

Selection: The next generation is formed by selecting the best guesses (elitism) based on fitness.

Termination: The algorithm continues until the AI guesses the correct number or reaches a generation limit.

Requirements
Make sure you have Python 3.x installed

Game Overview

The AI uses a genetic algorithm to guess a number between 1 and 100 that the player is thinking of.
The player provides feedback by entering their number (this number remains hidden from the AI).
The genetic algorithm generates a population of guesses, selects the best ones, and iterates through generations until the AI guesses the correct number.

How to Run the Game
Clone the repository or copy the code into a Python script file (e.g., ai_genetic_guessing_game.py).







Sudoku Solver
This project is a Python implementation of a Sudoku Solver using the Backtracking Algorithm. The program takes a partially filled Sudoku board as input and fills it to solve the puzzle.

Features
Solves a standard 9x9 Sudoku grid.
Uses backtracking to find a solution efficiently.
Checks constraints for rows, columns, and 3x3 subgrids to ensure valid placements.
Prints the solved Sudoku puzzle.

Requirements
This project requires Python 3.x. No additional libraries are needed.

How It Works

Algorithm Overview

Empty Cell Search:
The program searches for the first empty cell (denoted by 0).

Validation:
It checks if a number from 1 to 9 can be legally placed in the empty cell by verifying:
The number is not already present in the same row.
The number is not already present in the same column.
The number is not already present in the corresponding 3x3 grid.

Backtracking:
If a valid number is placed, the algorithm recursively attempts to solve the rest of the grid.
If no valid number can be placed, it backtracks and tries the next possibility for previous cells.

Termination:
The puzzle is solved when no empty cells are left.
If no solution exists, the program notifies the user.






