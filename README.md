# Number Guessing Game

## Overview

Welcome to the Number Guessing Game! This simple console-based Java program allows users to guess a randomly generated number within a specified range.

## Features

- Generates a random number within a specified range (default: 1 to 100).
- Prompts the user to enter their guess for the generated number.
- Compares the user's guess with the generated number and provides feedback on correctness.
- Limits the number of attempts the user has to guess the number.
- Allows the option for multiple rounds, letting the user play again.
- Displays the user's score, based on the total number of attempts made across all rounds.

## How to Run

1. Ensure you have Java installed on your machine.
2. Clone this repository.
3. Compile and run the `NumberGame.java` file.

bash
javac NumberGame.java
java NumberGame
Gameplay
You will be prompted to guess a randomly generated number within a specified range.
Receive feedback on each guess, indicating if it's correct, too high, or too low.
You have a limited number of attempts to guess the number.
After each round, you can choose to play again.
Customization
Feel free to customize the game parameters, such as the range of numbers, attempts limit, etc., by modifying the relevant variables in the NumberGame.java file.

Enjoy the Game!
Have fun playing the Number Guessing Game and challenge yourself to improve your score with each round!

Note: Ensure that you close the scanner properly to avoid resource leaks. The scanner.close(); statement is included in the provided code.
