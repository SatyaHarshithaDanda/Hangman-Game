# Hangman Game 🎮

A simple terminal-based Hangman game built with Python. The player must guess the randomly chosen word one letter at a time before running out of attempts. With each wrong guess, a part of the hangman is drawn — fail to guess the word in 10 tries, and the game is over!

## Features ✨

- Random word selection from a preset list
- ASCII-art style hangman drawing after each wrong guess
- Input validation for lowercase alphabet letters
- Friendly and interactive terminal experience

## How to Run 🖥️

1. Make sure you have Python installed (`python3` recommended).
2. Download or clone this repository.
3. Run the game using the command:

```bash
python Hangman.py
```

## Gameplay Instructions 🎯

- You will be prompted to enter your name.
- A random word will be selected, and you will see underscores representing each letter.
- Enter one lowercase letter per guess.
- Each incorrect guess draws part of the hangman.
- You have 10 attempts to guess the entire word.

## Example Output

```
Enter Your Name: Alex
Welcome  Alex
---------------------
Before finishing 10 attempts guess the word
Guess the word:  _ _ _ _ _
```

## Word List

Words are selected from the following:

`solar, environment, ocean, superman, batman, forest, mountain, nation, asia, europe, pineapple, custard, science, english, story, terminal, command, virtual`

Happy guessing! 😊
