

# 📘 Assignment: Hangman Game

## 🎯 Objective

Build a classic Hangman word-guessing game in Python. Practice string manipulation, loops, conditionals, and user input while reinforcing problem-solving skills.

## 📝 Tasks

### 🛠️ Game Logic Implementation

#### Description
Create the core logic for a Hangman game where the player guesses letters to reveal a hidden word. The game should track guesses, display progress, and handle win/lose conditions.

#### Requirements
Completed program should:

- Randomly select a word from a predefined list
- Accept single-letter guesses from the user
- Display the current progress (e.g., _ a _ _ m a n)
- Track and display the number of incorrect guesses remaining
- End the game when the word is fully guessed or attempts are exhausted
- Show a win or lose message at the end

Example:
```
Word: _ _ _ _ _ _ _
Guess a letter: a
Word: _ a _ _ _ a _
Incorrect guesses left: 5
...
```

### 🛠️ User Experience Enhancements

#### Description
Improve the user experience by adding features such as input validation, replay option, and clear instructions.

#### Requirements
Completed program should:

- Validate that user input is a single alphabetic character
- Prevent repeated guesses of the same letter
- Display all guessed letters so far
- Offer the player a chance to play again after the game ends

Example:
```
Guessed letters: a, e, r
Guess a letter: r
You already guessed 'r'. Try another letter.
```
