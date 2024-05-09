# Adversarial Search and Game Playing

## Overview
This repository contains implementations and evaluations of adversarial search algorithms, focusing on the Minimax algorithm and its enhancements, including alpha-beta pruning and parallelization. Additionally, a modified tic-tac-toe game is provided where the AI player exhibits randomized behavior and uses heuristics to evaluate game states.

## Evaluations
### 1. Minimax Algorithm
- Implemented minimax algorithm without pruning.
- Implemented alpha-beta pruning to optimize minimax search.
- Evaluated the average number of nodes evaluated using both approaches over 3 runs.

### 2. Parallelization
- Developed a parallel version of alpha-beta pruning using 2 threads.
- Compared the performance of the parallel version with the sequential version.

### 3. Enhanced Alpha-Beta Pruning
- Developed a heuristic for non-terminal states to reduce the search space.
- Compared the performance of enhanced alpha-beta pruning with the standard alpha-beta pruning algorithm.

### 4. Modified Tic-Tac-Toe Game
- Implemented a modified version of tic-tac-toe where the AI player exhibits randomized behavior.
- Added functionality to randomly pick a tile at the start of the game, which the AI player will not use during the game.
- Utilized a heuristic to define the desirability of a state for the AI player.

## Usage
1. Clone the repository.
2. Navigate to the project directory.
3. Ensure Python 3.x is installed on your system.
4. Run the provided code for each evaluation scenario:
   -  `python main.py`
5. Or you can download the file uplaod it on google drive, and run it on Google Collab.
