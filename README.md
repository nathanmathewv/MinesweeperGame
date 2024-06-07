# Minesweeper on CircuitVerse
This was an emulation of the popular game 'Minesweeper' which was made on CircuitVerse. It consists of adders, subtractors, randomisers, and many other circuit components that I had learnt.

## How To Run
  1. Import the file as a project on CircuitVerse.
  2. Go to the 'Game On' subcircuit and click on the 'New Game' button.
  3. If you click on 30 of the 36 cells without triggering a bomb, you win the game, else you lose.

## How It Works
The circuits in the file are used to first randomize bomb locations, then calculate all 9 (or less if it is a corner or edge) neighbours of a user-clicked cell to see how many bombs are there in the vicinity using the adders, and subtractors. 
If the neighbours (or the clicked cell) are bombs, the clicked cell will display the necessary hints about where the bomb is by matching the locations of the bombs and neighbours.
