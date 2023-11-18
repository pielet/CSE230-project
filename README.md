# CSE230-project

#### Idea 1: Minesweeper game

This minesweeper game starts from an empty scene with boundaries. Users can choose the density of the mines (sparse, medium, and dense) and board size. At every round, the player can use the arrow key to navigate around the board, `d` to open a new grid, or `m` to mark a grid as dangerous. If there is a mine landing in this grid when `n` is pressed, then the game is over. Otherwise, update the map to scale up a "detected" area and display the number of mines around the boundary. The player wins the game when all the board grids are detected or marked as dangerous, and the marker is placed correctly. Optionally, the player can press `q` to quit the game and `r` to start over.

#### Idea 2: Single-player ping-pong game

To launch the game, the user can choose where to place a ping-pong ball and its initial velocity. While playing, the player can use the left/right key to control a ping-pong paddle to move around at the bottom of the playing board. When the ping-pong ball moves downwards and is going to penetrate the bottom boundary, the player should control the paddle to catch it, otherwise, they will lose the game. The collision between the ball and all boundaries is an elastic collision, which only involves the change of direction of the velocity. Hit `q` to quit the game and `r` to start over. 
