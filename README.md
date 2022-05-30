# Tile-Flipping-Game
A memory based tile flipping game. The user must flip a tile and the flip its partner tile through either guess or by memory of the previously flipped tile. The tile will flip back if wrong partner tile is chosen.

GAME CONCEPT:

The Game consists of a 3X4 grid of tiles with 6 pairs of special characters hidden behind them. 
The user first flips a tile by clicking on the same.
The character of the tile will be revealed. 
Now the user must try to find the tile with same character behind it. 
If the second tile is found immediately after the first one, the user will earn the tiles as they turn black and must find the rest of the tiles.
If not, then the already flipped tile will disappear and the user must now remember the tile position for future references.
The game continues until all the tiles are flipped and the label shows "YOU WON"

TECHNOLOGIES USED:

The game has been programmed in Python vesion 3.10.4
Python library "Tkinter" has been used to generate the GUI of the game.
Basic widgets such as "Label" and "Buttons" has been used.
Python library "random" has been used to generate the random tile positions at each run.
Concepts like functions, arrays and loops has been used extensively.
