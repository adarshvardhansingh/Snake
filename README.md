# Snake
The code is a Python implementation of the classic arcade game "Snake". It uses the Pygame library to create the game window and handle user input, and the Tkinter library to display a message box when the game ends.

The game is made up of two main classes: "cube" and "snake". A "cube" object represents a single block on the game board, while a "snake" object represents the entire snake. The game board is represented as a grid of cubes.

The "snake" object is responsible for moving the snake, checking for collisions with the game board and the snack, and adding new cubes to the snake when it eats the snack. The "cube" object is responsible for drawing itself on the game board.

The game loop is handled by the "redrawWindow" function, which clears the game board, draws the snake and the snack, and draws the grid.

When the game ends (i.e., the snake collides with the game board or itself), a message box is displayed using the Tkinter library. The message box offers the player the option to restart the game or quit.
