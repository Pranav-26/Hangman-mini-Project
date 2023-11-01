# Hangman-mini-Project
A python based hangman game

In this code, I've implemented a simple Hangman game in Python. Here's a summary of the key concepts and features I've employed in my code:

![1](https://github.com/Pranav-26/Hangman-mini-Project/assets/92203147/9d7302c8-d637-490d-b25f-e7ff0f2057db)

1. Importing Modules:
   - I imported the `random` module to help me generate random words and choices.
   - I imported specific word lists from a custom module named `words`, including `random_words`, `bodyParts`, `fruits`, `vegetables`, and `animals`.

![2](https://github.com/Pranav-26/Hangman-mini-Project/assets/92203147/9b9dafc0-1b18-489d-a831-521103e998a1)


2. User-Defined Functions:
   - I created the `get_word()` function, which allows me to choose a category (random words, body parts, fruits, vegetables, or animals) and then returns a randomly selected word from the chosen category.
   - I developed the `play(word)` function to handle the main game logic. It initializes the game state, including the word to be guessed, the word completion display, and tracks guessed letters and words.
   - The player has a limited number of tries (6), and the game displays a progressing hangman figure as they make incorrect guesses.
   - I've also implemented the `display_hangman(tries)` function, which takes the number of remaining tries as input and returns a string representing the hangman figure based on the number of incorrect guesses.

![3](https://github.com/Pranav-26/Hangman-mini-Project/assets/92203147/224f9742-f812-48ec-88ac-eef9c44c0973)


3. Main Game Loop:
   - I use the `main()` function as the entry point of the game. I call `get_word()` to select a word, and then call `play(word)` to start the game.
   - After a game is finished, the player is prompted with the choice to replay the game. If they choose to continue (by entering 'Y'), a new word is selected, and the game begins again.

Programming concepts employed in my Hangman game program:
Module Import ,Functions ,Conditional Statements ,Loops ,Randomization ,Data Structures: Lists and Strings ,String Handling ,User I/O ,Function Calls ,Error Handling ,String Manipulation and Code Organization

Overall, my code demonstrates basic game development concepts, including user input, random word selection, tracking game state, and handling player interactions. 
It provides an interactive Hangman game that the player can play and replay as many times as they like.
