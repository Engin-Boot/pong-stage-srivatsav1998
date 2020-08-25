# Game

## Feature

This is the actual gameplay

## Acceptance Criteria

### Scenario: When Player 1 moves player 1 controller to the right

  Given player 1 and player 2 are ready as per game mode
  and in the game

  When player 1 moves the player 1 controller to the right

  Then the virtual bat of player 1 moves downwards.

### Scenario: When Player 1 moves player 1 controller to the left

  Given player 1 and player 2 are ready as per game mode
  and in the game

  When player 1 moves the player 1 controller to the left

  Then the virtual bat of player 1 moves upwards.

### Scenario: When Player 2 moves player 2 controller to the right

  Given player 1 and player 2 are ready as per game mode
  and in the game

  When player 2 moves the player 2 controller to the right

  Then the virtual bat of player 2 moves downwards.

### Scenario: When Player 2 moves player 2 controller to the left

  Given player 1 and player 2 are ready as per game mode
  and in the game

  When player 2 moves the player 2 controller to the left

  Then the virtual bat of player 2 moves upwards.

### Scenario: When ball htis the bat

  Given player 1 and player 2 are ready as per game mode
  and in the game

  When the ball hits a bat

  Then the ball reflects back with increased speed (1.5 times) and in opposite direction

### Scenario: When ball hits the wall of player 1
  
  Given player 1 and player 2 are ready as per game mode
  and in the game

  When the ball hits the wall of player 1

  Then the counter for the player 2 increases
  and ball restarts from player 1 location.

### Scenario: When ball hits the wall of player 2
  
  Given player 1 and player 2 are ready as per game mode
  and in the game

  When the ball hits the wall of player 2

  Then the counter for the player 1 increases
  and ball restarts from player 2 location.

### Scenario: When player 1 score reaches 7
  
  Given player 1 and player 2 are ready as per game mode
  and in the game

  When player 1 score reach 7

  Then winner is player 1, and after 10 seconds game redirects to MainPage

### Scenario: When player 2 score reaches 7
  
  Given player 1 and player 2 are ready as per game mode
  and in the game

  When player 2 score reach 7

  Then winner is player 1, and after 10 seconds game redirects to MainPage

### Scenario: When ball restarts after player 2 scores a point
  
  Given player 1 and player 2 are ready as per game mode
  and player 2 scored a point

  When the ball restarts

  Then ball will wait near bat of player 2 for 2 seconds and 
  starts off after that duration

### Scenario: When ball restarts after player 1 scores a point
  
  Given player 1 and player 2 are ready as per game mode
  and player 1 scored a point

  When the ball restarts

  Then ball will wait near bat of player 1 for 2 seconds and 
  starts off after that duration