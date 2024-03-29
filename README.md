# SnakeAI

AI learns to play "[Snake](https://en.wikipedia.org/wiki/Snake_(video_game_genre))".

This project uses a combination of genetic algorithms and neural networks to teach an AI to play the game "Snake".

A three layer feedforward neural network is used as the snake's brain. After the first generation of snakes is 
randomly initialized, each snake is tested in how it performs in the game. The best performing snakes make it to the
next generation--some of the neurons in their brains being randomly mutated.

When the application is started, a window displaying the playing field allows the user to follow the evolutionary 
progress. Typically, the generated snakes will get better at playing the game over time.


![screenshot](screenshot.PNG)
