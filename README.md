# Lab 17 - Chutes and Ladders Simulator

## Lab Goal
You will simulate games of Chutes and Ladders and report on the minimum, maximum, and average number of turns it takes to finish a game.

## Instructions
* Complete the method `runGame`. This is where a complete game of Chutes and Ladders is simulated.  This returns the number of turns it took to finish the game.
* Complete the method `main`. This method already prompts the user for the number of players and the number of games.  You need to add a loop that will repeatedly call `runGame` and update the results accordingly.  After all of the games have been simulated output the results.
* There are no tests to be run on this.  I will have to grade it manually.

## Rules of Chutes and Ladders
* All players start at location 0 (not on the board yet) and spin a spinner with the numbers 1-6 on it. The player moves the appropriate number of spaces.
* If a player lands on the base of the ladder, the player climbs to the top of the ladder to complete their turn.
* If a player lands on the top of a slide, the player slides to the bottom of the slide to complete their turn.
* To end the game, a player must land exactly on square 100.  If a spin takes them past square 100 they don't move and it is the next player's turn.
* See the included game_board.gif to see what the game board looks like.

![game-board](game_board.gif)

## Sample Output
```
How many players (1-4)? 4
How many simulations should be run? 100

Chutes and Ladders Simulator
Number of Players = 4
Number of Games = 100
Average game length = 71 turns
Minimum game length = 26 turns
Maximum game length = 171 turns
```
