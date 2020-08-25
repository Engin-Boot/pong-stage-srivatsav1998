# MainPage

## Feature

Entry point to the Pong Game.

## Acceptance Criteria

### Scenario: Insert one coin

  Given there is a working videogame console and
  the coin collector is listening for coint insert event

  When I insert a coin

  Then I am player 1, player 1 controller is active,
  and I see options to select the game mode.

### Multiple coin insert

  Given there is a working videogame console and
  the coin collector is listening for coin insert event

  When I insert more than one coins

  Then I am player 1, player 1 controller is active,
  and I see options to select the game mode.
