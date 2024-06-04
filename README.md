Old school snake game using TurtlePy on Python.

Each file is responsible for the efficient working of the game.

Food.Py is responsible for the random position of the food on the board. Once eaten by the snake, the food renders on some random position on the board.

Scoreboard.Py stores the points which are created when the snake eats the food. After each successfully collision with the food, the score increases by
1 point.

Snake.Py is responsible for the movement of the snake. The snake is controlled by the user by pressing the arrow keys on the keyboard. After every 
successful collision with the food, the size of the snake increases by 1. If the snake touches the border then the match ends and score resets to zero
along with the size of the snake.

Main.Py is responsible for the working of the entire game by making the code work together where it is called. It is responsible for detecting when the
snake is colliding with the food, when its size has to be increased, when the snake collided with the border and to display the "GAME OVER" message.
