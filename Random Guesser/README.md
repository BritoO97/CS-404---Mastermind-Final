CS 404 Final Project - Mastermind Game

Random Guesser

The implementation of a random guesser for Mastermind

randomGuess.py - Contains the actual algorithm for solving the game
randomRunner - A bash script that automatically runs the python script, along with performing timestamping and automatic analysis using awk scripts
game.py - This is the actual game code, it is the same for every algorithm tested. Has not been modified since the beginning of the project
awkScript - see the Awk Script folder

========================================================================

Usage:
bash fiveRunnerMinimax numGames

where numGames are the desired number of games to run (ie: 1000 will run 1000 individual games and output a results file with 1000 entries)

========================================================================

Output:

There are 3 files created as a result of running the algorithm
results - contains one line for every game 'played'. Lines are in the following format: 
		solution for that game | number of guesses | time taken in ns
formatted - output of the awkScript being called
time - two timestamps from the beginning and end of testing (not used directly in the project, it served as a reference to our testing schedule)
