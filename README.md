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

### 5. Usage
#### Running IPython Notebook on Conda

To run an IPython Notebook (`.ipynb` file) on Conda, follow these steps:

1. **Activate Conda Environment:** Open your terminal or command prompt and activate your Conda environment where you have installed Jupyter Notebook:

    `conda activate (enviornment name)`

   Replace `(environment name)` with the name of your Conda environment.

3. **Install Jupyter Notebook (if not installed):** If you haven't installed Jupyter Notebook in your Conda environment, you can install it using the following command:

   `conda install jupyter`
   
5. **Navigate to Notebook Directory:** Use the `cd` command to navigate to the directory where your `.ipynb` file is located.

6. **Launch Jupyter Notebook:** Once you are in the directory containing your notebook file, run the following command to launch Jupyter Notebook:

    `jupyter notebook`
   
8. **Access Notebook in Browser:** After running the above command, Jupyter Notebook will open in your default web browser. You should see a file browser interface where you can navigate to your `.ipynb` file. Click on the file to open and run it.

9. **Run Notebook Cells:** Once the notebook is open, you can run each cell individually by selecting it and pressing `Shift + Enter`. Alternatively, you can run all cells by selecting `Cell` from the menu and choosing `Run All`.



