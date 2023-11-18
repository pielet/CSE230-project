# CSE230-project

#### Idea1: terminal minesweeper

This minesweeper game starts from an empty scene with boundary. User can choose the density of the mines (sparse, medium, and dense) and board size. At every round, the player can use arrow key to navigate around the board, `d` to open a new grid, or `m` to mark a grid as danger. If there is a mine lands in this grid when `n` is pressed, then game is over. Otherwise updating the map to scale up a "detected" area and display the number of mines around the boundary. Player wins the game when all the board grids are detected or marked as danger, and the marker is placed correctly. Optionally, player can press `q` to quit the game and `r` to start over.

#### Idea2: Single player ping-pong game

To launch the game, user can choose where to place a ping-pong ball and its initial velocity. While playing , player can use left/right key to control a ping-pong paddle to move around at the bottom of the playing board. When the ping-pong ball move downwards and is going to penatrate the bottom boundary, the player should control the paddle to catch it, otherwise they will lose the game. The collision between the ball and all boundary is elastic collision, which only involves the change of direction of the velocity. Hit `q` to quit the game and `r` to start over. 