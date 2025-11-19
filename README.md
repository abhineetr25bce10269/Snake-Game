# Snake-Game
It is basically a game developed by me in python as part of my college project. It uses import functions like RANDOM,TURTLE and TIME. The game is simply a snake which can be controlled by WASD keys which should eat food to increase its length. Each food gives +10 health. The snake would die if its head hits its tail or it goes out of boundary.
FEATURES
Smooth snake movement controlled by WASD keys
Food appears at random positions
Score increases as the snake eats food
Snake grows after each food item
Game Over on collision with borders or with itself
Clean and beginner-friendly code
MODULES USED
MODULE	                               PURPOSE
TURTLE	                               For graphics, snake movement, drawing, and screen handling
RANDOM                                 To generate random food positions
TIME                                   To manage game speed and delays
CONTROLS
W    Move Up
A 	 Move Left
S	   Move Down
D	   Move Right
GAME ELEMENTS
Snake Head       : Moves continuously in the direction set by the player
Food             : Appears randomly, eaten by snake to gain score
Scoreboard       : Displays current score and high score(+10 for each food)
Border           : Collision ends the game
GAME LOGIC
The snake moves in steps using turtle.forward()
A list stores body segments, and each segment follows the previous one
Random coordinates generate food positions
Collision checks include
Hitting the wall
Hitting its own tail
CONCLUSION
This Snake Game is a great beginner project to understand Python graphics, loops, and game logic.
