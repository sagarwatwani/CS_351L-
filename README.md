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

