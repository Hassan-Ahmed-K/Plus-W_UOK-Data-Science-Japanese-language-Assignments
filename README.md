# Plus-W_UOK-Data-Science-Japanese-language-Assignments
This repsitory include all the assignments of the course which is the done on the jupyter notebook in python language and Question of this is also uploade in the form of pdf

## ASSIGNMENT 1

##### Question 1

This Python script prompts users to input two names, combines them, and calculates a 2-digit love score. The score is based on the counts of letters in "TRUE" and "LOVE." Messages vary: "coke and mentos" for extreme scores, "alright together" for mid-range, and a straightforward score message otherwise. The script provides a simple and fun way to gauge compatibility.

##### Question 2

This Python script simulates a coin toss using the random module. It generates a random number (0 or 1) and prints "Heads" if the result is 1, otherwise "Tails." It offers a straightforward way to simulate a coin toss for decision-making or game
##### Note:
For running the code of assigment 1 and question 2,You must have the random module(automatically installed with python installation) install in your computer

##### Question 3

This Python script presents a text-based adventure on Treasure Island. Players make choices by entering "Left" or "Right" and navigating through subsequent options. The narrative unfolds based on the decisions made, leading to different outcomes. A fun and interactive way to explore an imaginary world and test decision-making skill

## ASSIGNMENT 2

**Hangman Game in Python**

This Python script implements a simple Hangman game. The game randomly selects a word from a predefined list, and the player must guess the letters of the word within a certain number of lives. The game provides visual feedback through ASCII art for each incorrect guess.

**Game Flow:**

1. **Initialization (Step 1):**
   - Randomly selects a word from the predefined list (`word_list`).
   - Asks the user to guess a letter, converting the input to lowercase.
   - Checks if the guessed letter is in the chosen word.

2. **Display Initialization (Step 2):**
   - Creates an empty list called `display` with underscores representing each letter in the chosen word.
   - Updates the display to reveal correctly guessed letters.

3. **Game Loop (Step 3):**
   - Utilizes a while loop to allow the user to make multiple guesses until the word is completely guessed.
   - Informs the user upon winning.

4. **Visual Feedback (Step 4):**
   - Imports the `random` module and defines a variable `stages` containing ASCII art for the Hangman.
   - Introduces a `lives` variable to track remaining lives.
   - Decreases lives if a guessed letter is not in the chosen word.
   - Prints the corresponding Hangman ASCII art based on the remaining lives.
   - Ends the game with a "You lose" message if lives reach zero.

5. **Additional Features (Step 5):**
   - Handles cases where the user enters a letter they've already guessed.
   - Provides feedback when a guessed letter is not in the chosen word.

This Hangman game is an interactive and visually engaging way for users to practice word guessing while enjoying the classic Hangman experience. The modular structure allows for easy customization and extension.
