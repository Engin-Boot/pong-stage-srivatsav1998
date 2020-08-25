# ScoreCounter

## Feature

Handles the score for a given game.

## Acceptance Criteria

### Scenario: When it receives player 1 score update event

  Given the scoreCounter is listening to the events

  When it receives player 1 score update event

  Then it increments the score of player 1.


### Scenario: When it receives player 2 score update event

  Given the scoreCounter is listening to the events

  When it receives player 2 score update event

  Then it increments the score of player 2.

### Scenario: When any of the player's score reaches 7 points

  Given the scoreCounter is keeping track of scores of each player

  When any of the player's score reaches 7 points

  Then it declares the player with 7 points as winner
  and termintes the current game.
