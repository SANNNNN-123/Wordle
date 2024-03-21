# Wordle Game

## Description
This project is a simple implementation of the popular game Wordle using Python and Pygame library. In Wordle, players guess a secret word and receive feedback on the correctness of their guesses.

## Features
- Players can input their guesses using the keyboard.
- Feedback on the correctness of the guesses is provided through color-coded indicators.
- Players can play multiple rounds with a different secret word each time.
- Option to play again after each round.

## Files Included
1. `main.py`: Python script containing the game implementation.
2. `words.py`: Python file containing a list of words used as secret words in the game.
3. `pics/`: Directory containing images used in the game (background, icon, fonts).

## Installation
1. Clone the repository to your local machine.
2. Make sure you have Python installed on your system.
3. Install Pygame library using `pip install pygame`.
4. Run the `main.py` script to start playing the game.

## How to Play
1. Guess the secret word by entering a 5-letter word using the keyboard.
2. Press Enter to submit your guess.
3. Feedback will be provided on the correctness of your guess:
   - Green indicates correct letter in the correct position.
   - Yellow indicates correct letter in the wrong position.
   - Grey indicates incorrect letter.
4. You have 6 attempts to guess the word correctly.
5. After each round, you will be prompted to play again by pressing Enter.
