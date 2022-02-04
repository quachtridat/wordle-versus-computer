*The `.ipynb` notebook contains interactive elements. Please make sure your Python kernel and your notebook support interactivity.*

## The Wordle Game

**Wordle** is an English word game. You as a player, by default settings, has to guess a 5-letter English word within 6 attempts.

A guess has to be a 5-letter word. When a guess has been made, the game reveals to you how accurate your guess was, by marking your letters with colors:

- <span style="color: grey;">**Grey**</span> letters are the letters that **do not** appear in the correct word.
- <span style="color: goldenrod;">**Yellow**</span> letters are the letters that **do** appear in the correct word, however are placed at the **wrong** positions.
- <span style="color: darkgreen;">**Green**</span> letters are the letters that **do** appear in the correct word, and are placed at the **right** positions.

The game ends when you guess the correct hidden word within 6 attempts.

## The Wordle vs. Computer game

The rule of the **Wordle** game still applies, however, this time, you face a computer that can also make guesses. As you play the game, after every guess you have made, the computer reveals to you the guess it has made. The catch is, the computer does not reveal to you the letters it has entered, but the game tells you how accurate the computer's guess is, using the colors.

You lose when you have not guessed the correct word and the computer has already finished the game with its correct guess. Just like you, however, the computer is not always winning, and might lose the game.

## Python Version

The `.ipynb` notebook has been tested running with Python 3.7 and Python 3.10.2.

## Play

1. Execute all cells.
2. Leave the cursor on the left side's canvas (the user's field).
3. Play the game.
4. Re-run the last cell if you want to play again.
