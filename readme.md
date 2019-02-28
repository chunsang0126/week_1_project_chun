# Topic: Guess The Number Game

![alt text][logo]

[logo]: ./photo.jpg

## Objectives: Creating a game which 

## 1-player game the program itself automatically generates THE NUMBER for a player to guess,where the number of guesses is fix by default
-----------------------------------------------------------------------------------------

**OR**

## 2-player game takes input from one player and then another player have to make guesses
-----------------------------------------------------------------------------------------		
* if it is **_case 1_**, one player can input the range of numbers, _e.g._ inputting 100 would mean the answer could lie within _1-100_, followed by input of **_THE NUMBER_** )

* for the game to make sense, we could by default limit the number of guesses which varies with the range be picked.

In both of the cases above, when input is received by program, it compares with **_THE NUMBER_** and then prompt a hint suggesting whether the input is 

* Correct.
* Greater than,
* Less than, **_THE NUMBER_**

Once a guess is made, the subsequent range of remaining numbers is narrowed down to the new guess and the other end of the boundary. If the next guess is out of range, a message will be prompted to alert the player.

When the player guesses THE NUMBER right, a message like _'congratulations'_ will be prompted

When the player runs out of guesses before getting **_THE NUMBER_**, he loses and sees a message like **'let's try again!'** or **'better luck next time.'**

---

# Flow of Code

	
1. Randomly generate a number within a range --- some functions can do that
2. Receiving input from player
3. Comparing that input with **_THE NUMBER_**
4. Prompting message regarding the results, until running out of guesses
5. **End Game** and prompt **New Game**
