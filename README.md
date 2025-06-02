# 🎯 Number Guessing Game (Python)

Welcome to the Number Guessing Game! This is a fun and simple Python-based console game where the player tries to guess a randomly generated number within a specified range. The player has 7 attempts to guess the correct number.

## Objective

Welcome to the Number Guessing Game! This is a fun and simple Python-based console game where the player tries to guess a randomly generated number within a specified range. The player has 7 attempts to guess the correct number.

## How the Game Works

To understand how the number guessing game functions, let’s walk through two practical scenarios. These examples demonstrate how narrowing down the range intelligently—similar to a binary search—can help guess the number efficiently.

## 🕹️ How to Play

1. The game begins by asking the user to input a lower bound and an upper bound.

2. The computer will randomly choose a number within that range.

3. You get 7 chances to guess the number correctly.

4. After each guess, you'll receive a hint:

  “Too high! Try a lower number.” or

  “Too low! Try a higher number.”

5.If you guess it correctly within 7 tries, you win!

6. If not, the correct number is revealed and the game ends.

## 📌 Example Output

Hi! Welcome to the Number Guessing Game.
You have 7 chances to guess the number. Let's start!
Enter the Lower Bound: 1
Enter the Upper Bound: 50

You have 7 chances to guess the number between 1 and 50. Let's start!
Enter your guess: 25
Too high! Try a lower number.
Enter your guess: 12
Too low! Try a higher number.
...
Correct! The number is 17. You guessed it in 4 attempts.

## Example 1: Guessing in a Range from 1 to 100

Suppose the user defines the range from 1 to 100, and the system randomly selects 42 as the target number. The guessing process might look like this:

Guess 1: 50 → Too high
Guess 2: 25 → Too low
Guess 3: 37 → Too low
Guess 4: 43 → Too high
Guess 5: 40 → Too low
Guess 6: 41 → Too low
Guess 7: 42 → Correct!
Total Guesses: 7
