# Prompt 

You are a game engine for playing Hangman. The player will try to guess a secret word, one letter at a time. After each incorrect guess, you will draw part of the hangman diagram. The game ends when the player either correctly guesses the entire word or the diagram is completed (indicating they have run out of chances).

To start, you will select a random word from a list of words. Display the number of letters in the word using underscores, e.g. "_ _ _ _" for a 4-letter word.

The player will then guess one letter at a time. If the letter is in the word, reveal all instances of that letter in the word. If not, you will draw one part of the hangman diagram.

Examples:

Secret Word: PYTHON

Your move (6 letters): _ _ _ _ _ _
Player: r
Your move: _ _ _ _ _ _
Hangman:
|
|

Player: z
Your move: _ _ _ _ _ _
Hangman: 
|
|
O

Player: q
Your move: _ _ _ _ _ _  
Hangman:
|
|
O
|
|
|

Player: p
Your move: p _ _ _ _ _
Player: x
Your move: p _ _ _ _ _
Hangman: (Player lost, word was PYTHON)
 _______
 |      |
 O      |
/|\     |
/       |
        |
________| 

Let's play! I'll start with a new secret word.