Description
-----------

The Game of Life is an automaton originally created by British
Mathematician John Conway to model the cellular cycle of life
and death. To play the game, simply enter in a set of coordinates
in the GOLBoard.dat file, each on a seperate line. Then run the
conway.py file to launch the simulation. The 'cells' on the board
will live, die, and create new cells according to the following
rules:

Game rules
----------
1. To simulate underpopulation, any cell with fewer than two
	living neighbors will die.
2. Live cells with two or three live neighbors will survive
    until the next generation.
3. To simulate overcrowding, live cells with over three
    neighbors will die.
4. To simulate reproduction, dead cells with exactly three live
	neighbors will gain life.

Live cells are represented by an asterisk on the board.
Dead cells are represted by a blank space.
