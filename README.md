# SCRABBLE
A C program that calculates and compares the Scrabble scores of two words, completed as part of Harvard's CS50 Week 2.
# Scrabble 🎯

A C program that calculates the Scrabble score of two words and determines which player has the higher score.

This was completed as part of **Harvard's CS50x — Week 2: Arrays**.

## How It Works

The program asks both players to enter a word.

It then goes through each letter and assigns points based on the Scrabble point values.

For example:

- A = 1 point
- B = 3 points
- C = 3 points
- D = 2 points
- ...
- Z = 10 points

The program calculates the total score for both players and prints:

- `Player 1 wins!`
- `Player 2 wins!`
- `Tie!`

Uppercase and lowercase letters are treated the same, and characters that aren't letters don't add any points.

## Example

Player 1: QUESTION?
Player 2: QUESTION!

Tie!

## What I Used

- C
- CS50 Library
- Arrays
- Strings
- `strlen()`
- `isupper()`
- `islower()`
- `for` loops
- Functions
- Character indexing

## What I Learned

This problem helped me understand how arrays can be used to store related values and how a character can be used to find the corresponding position in an array.

I also got more practice with strings, loops, functions, and working with individual characters.

## How to Run

Compile:

``bash
make scrabble
./scrabble
