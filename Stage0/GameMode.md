# GameMode

## Feature

Selection of game mode. (vs / computer)

## Acceptance Criteria

### Scenario: Selecting vs mode

  Given player 1 is active

  When I select vs mode

  Then the coin collector will listen to coin insert event
  for next 15 seconds.

### Scenario: Selecting computer mode

  Given player 1 is active

  When I select computer mode

  Then computer will be player 2, computer virtually handles player 2 controller,
  and now I see main menu.

### Scenario: Player 2 inserts coin after game mode selection

  Given player 1 is active and chose vs mode

  When player 2 inserts coin within 15 seconds,

  Then player 2 controller will be active for player 2 to use
  and now we see main menu.

### Scenario: Player 2 inserts coin before game mode selection

  Given player 1 is active and chose and at mode selection page

  When player 2 inserts coin,

  Then nothing happens and player 1 still has to choose the game mode.

### Scenario: Player 2 inserts coin after 15 seconds

  Given player 1 is active and chose vs mode

  When player 2 inserts coin after 15 seconds

  Then computer will be player 2, computer virtually handles player 2 controller,
  and now I see main menu.