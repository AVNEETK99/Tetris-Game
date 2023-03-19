# Tetris-Game

Tetris is a classic tile-matching puzzle video game originally designed and programmed by Russian game designer Alexey Pajitnov in 1984. The game is played by manipulating geometric shapes called Tetriminos that fall down a playing field. The objective of the game is to complete lines of Tetriminos across the playing field by moving and rotating them to fit into a specified pattern. As the game progresses, the Tetriminos fall faster and the player must work quickly to keep the playing field from filling up with blocks. The game ends when the playing field is completely filled and no new Tetriminos can be placed. Tetris is a simple yet addictive game that has remained popular over the years, with numerous versions and adaptations available on various gaming platforms.

## Instructions to run the game

* Install Python and Pygame: If you haven't already, install Python (version 3.x) and Pygame. You can download Python from the official website (https://www.python.org/downloads/) and install Pygame using pip.
To install Pygame, open the command prompt (on Windows) or terminal (on Mac or Linux) and type the following command:
``` pip install pygame ```

* Download the code: Download the code from the GitHub repository (https://github.com/your-repository) and save it to your computer.

* Run the game: Open the command prompt or terminal and navigate to the directory where the code is saved. Type the following command to run the game:
```python tetris.py```

* Play the game: Use the arrow keys to move the falling blocks left, right, or down. Use the up arrow key to rotate the blocks. Use the spacebar to drop the block to the bottom. The goal is to create horizontal lines without gaps to score points and clear the board. The game ends when the blocks reach the top of the screen.

## Functionality of the code

* The code imports the pygame library and defines a list of colors to be used in the game.
* A class called Figure is defined to represent each of the seven types of Tetris pieces. This class also contains a method to rotate the pieces.
* A class called Tetris is defined to manage the overall game. This class contains methods to move the current piece down, freeze it in place when it reaches the bottom, and break completed lines.
* The code initializes the Pygame engine, sets the game window's size and title, and starts the game loop.
* The game loop continually checks for user input and updates the game state based on that input. The game loop also handles the graphics and rendering of the game.
* Once the game is over, the loop stops and Pygame quits.
