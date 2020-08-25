# Interaction Sequences

## Startup Sequence

1) Game will load with MainPage and coin collector will start listening to
coin inserted event.
2) After first coin insertion, GameMode page gets loaded with ability for 
player 1 to select the appropriate game mode
3) After game mode selection, Main menu page is loaded with ability for
player 1 to start game or make setting changes.
4) When player 1 selects start game, actual game loads up.

## Movement Initiation

1) Player 1 bat will listen to player 1 controller
2) Player 2 bat will listen to player 2 controller
3) Player 1 bat moves according to its controller movements
4) Player 2 bat moves according to its controller movements
5) Number of non scoring cycles will determine the ball speed between bats
6) If ball hits any of the walls, the score of the opponent increases accordingly
7) If any of the player reaches score of 7, he is declared winner and game 
redirects to MainPage
