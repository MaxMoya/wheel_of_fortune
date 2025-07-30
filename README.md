Wheel of Fortune (CLI Game)


This repository contains a command-line version of the classic "Wheel of Fortune" game. It's a fun, single-player game where you spin a virtual wheel, guess letters, and try to solve a hidden phrase to win!

Key Features
Phrase Bank: The game uses a phrases.txt file as its source for a wide variety of phrases.

Virtual Wheel: A Game_wheel class simulates spinning the wheel, with possible outcomes including different dollar amounts, "Bankrupt," and "Lose a Turn."

Player Turn System: The game handles player turns, including guessing consonants, buying vowels, and attempting to solve the puzzle.

Winnings Tracking: Tracks the player's round and total winnings throughout the game.

Technologies Used
Python 3

Installation
Clone the repository to your local machine:

Bash

git clone https://github.com/MaxMoya/wheel_of_fortune.git
cd wheel_of_fortune
Ensure the following files are in the same directory:

game.py

Game_wheel.py

phrases.txt

Usage
To start the game, simply run the game.py script from your terminal:

Bash

python game.py
Gameplay
The game will start by randomly selecting a phrase from phrases.txt and displaying a hidden version of it. You will be prompted to choose an action:

Spin the Wheel: This is your primary action. The wheel will land on a value (a dollar amount, "Bankrupt," or "Lose a Turn"). If you land on a dollar amount, you can then guess a consonant.

Buy a Vowel: If you have earned at least $250, you can choose to buy a vowel for that amount.

Solve the Puzzle: You can try to guess the entire phrase at any time. Be careful, a wrong guess will cost you your turn!

The game will continue until you either solve the phrase or run out of turns.

File Structure
game.py: The main script that runs the game loop and handles player interaction.

Game_wheel.py: Contains the Game_wheel class, which manages the spinning wheel's logic and outcomes.

phrases.txt: A simple text file where each line is a phrase for the game. You can easily add your own!
