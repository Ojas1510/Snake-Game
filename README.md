# Snake-Game
This is a simple console-based Snake game coded in C++. The game allows you to control a snake using 'W', 'A', 'S', and 'D' keys and try to eat as many fruits as possible to increase your score. The game ends if the snake collides with the boundary or itself. The game is not optimized for performance or graphical excellence; it serves as a simple demonstration of basic game mechanics.
# How to Play
Use 'W', 'A', 'S', and 'D' keys to control the snake's movement: 

'W' - Move Up 
'A' - Move Left 
'S' - Move Down 
'D' - Move Right 
Try to eat the fruit ('X') that appears on the screen to increase your score. 

The game will end if the snake collides with the boundary or itself. /br
# Instructions 
Compile the C++ code using a C++ compiler
Run the compiled executable (./snake_game ) 
This game runs in the console, so make sure your terminal or command prompt supports ANSI escape sequences for proper display 
The game's frame rate is set to 100 milliseconds (10 frames per second). You can adjust it in the Sleep() function to make the game faster or slower. 
# Code Explanation
The C++ code provided in snake_game.cpp consists of various functions and variables that handle different aspects of the game. Here's a brief explanation of each part: 

Setup(): Initializes the game by setting the initial positions of the snake and the fruit. \br

Draw(): Clears the console and draws the game grid along with the snake, fruit, and score. \br 

Input(): Checks for user input (W, A, S, D, or 'X') to control the snake's direction. \br

Logic(): Handles the game logic, including updating the snake's position, checking for collisions, and increasing the score when the snake eats the fruit. \br

main(): The main function that sets up the game, runs the game loop until the game is over, and controls the game's frame rate using Sleep(). \br
