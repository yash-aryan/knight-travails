# Overview

This project prints how many moves it takes for a "Knight" in the game of Chess, to go reach any square on the
board from anywhere. The gameboard ranges from 0 to 7 in both X and Y coordinates. This program works only on the console, so no GUI (yet).

To run the program, call the function: `knightMoves()`, which takes 2 arguments:

-   starting position
-   target position

The program then generates all the valid moves for the knight and enqueues it. It uses the BFS search algorithm to search the target. Each generated move is created into a node that links to it's parent (previous move).

**Example**:-

```
// input
knightMoves([0,0], [3,3])

// output
You made it in 2 moves!  Here's your path:
(0,0) --> (1,2) --> (3,3)
```
