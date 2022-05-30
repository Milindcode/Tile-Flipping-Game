# Tile-Flipping-Game
A memory based tile flipping game. The user must flip a tile and the flip its partner tile through either guess or by memory of the previously flipped tile. The tile will flip back if wrong partner tile is chosen.

GAME CONCEPT:

The Game consists of a 3X4 grid of tiles with 6 pairs of special characters hidden behind them. 
![image](https://user-images.githubusercontent.com/91339883/170927560-7199b095-36c1-4e11-bbe7-247079a87e42.png)



The user first flips a tile by clicking on the same.
![image](https://user-images.githubusercontent.com/91339883/170927288-847a70e4-eba8-4154-a947-96cc9e4a9ef4.png)


The character of the tile will be revealed. 
Now the user must try to find the tile with same character behind it. 
If the second tile is found immediately after the first one, the user will earn the tiles as they turn black and must find the rest of the tiles.


![image](https://user-images.githubusercontent.com/91339883/170927375-9b5c3e42-bafc-43d8-bc44-95f4224ca636.png)


If not, then the already flipped tile will disappear and the user must now remember the tile position for future references.
The game continues until all the tiles are flipped and the label shows "YOU WON"


![image](https://user-images.githubusercontent.com/91339883/170927450-8c959f57-e0ee-47f6-bec5-0787a52b1a11.png)


TECHNOLOGIES USED:

The game has been programmed in Python vesion 3.10.4
Python library "Tkinter" has been used to generate the GUI of the game.
Basic widgets such as "Label" and "Buttons" has been used.
Python library "random" has been used to generate the random tile positions at each run.
Concepts like functions, arrays and loops has been used extensively.
