# Chemistry Terms Hangman Game

by Megan Tran

## Purpose of this Program

This hangman game I coded is intended for high school students to study their chemistry terms in a entertaining and educational way. 
Python was used to create the bulk of the program (game functionality, word bank) and ASCII art was used to create my rendition of "Nanopuritan"
```
+-------------------------------+
              |                 |
     \|/     _|_     \|/        |
      \     /   \    /          |
    \\\\\   O   O  ///          |
     \\\\\   \ /  ///           |
         \    |   /             |
          \ //  \/              |
          | /    ||             |
          |      ||             | 
          \\      /             | 
            \\  /               |
              |                 |
              |                 |
           /   \\               |
          /     \\              |
    ____/        \\____         |
                                |
                                |
                                |
                                |
========================================
```
When coding this program, a challenge I faced was formatting my ASCII art so that the picture was not distorted when viewing it on Visual Studio Code. Another challenge was properly creating the word bank in a seperate Python file and importing that into my main hangman game ""Final.Hangman Chem"

Some features I hope to implement in this is a word bank that includes more words and something that displays a timer for how long the user has to guess to make the game hard.

## How to Play the Game

When the user begins the game, they will be show the hanging stand display and is prompted to guess a letter:

```You have 6 lives left and you have used these letters:


+-------------------------------+
              |                 |
              |                 |
                                |
                                |
                                |
========================================
Current word:  - - - - -
Guess a letter:
```
The user will be show a letter bank of what letters used, how many lives they have left, the letters guessed correctly/ incorrectly, and the hanging character piece by piece if they incorrectly guess. The user will keep guessing until they run out of lives or they correctly guess the word.

Incorrect guess display:

```
Your letter, E is not in the word.
You have 4 lives left and you have used these letters:  W E

+-------------------------------+
              |                 |
             _|_                |
            /   \               |
            O   O               |
             \ /                |
              |                 |
            //  \               |
          | /    ||             |
          |      ||             |
          \\      /             |
           \\    /              |
                                |
                                |
                                |
                                |
                                |
                                |
                                |
                                |
                                |
========================================

Current word:  - - - - -
Guess a letter:
```
Correctly guessed word display:

```
+-------------------------------+
              |                 |
              |                 |
                                |
                                |
                                |
                                |
                                |
                                |
                                |
                                |
                                |
                                |
                                |
                                |
                                |
                                |
                                |
                                |
                                |
                                |
========================================
Current word:  A R R H E N I U -
Guess a letter: s

YAY! You guessed the word ARRHENIUS !!

```

# Credits
I refered to the links below for the hangman template:

> https://www.youtube.com/watch?v=cJJTnI22IF8
> https://gist.github.com/chrishorton/8510732aa9a80a03c829b09f12e20d9c
