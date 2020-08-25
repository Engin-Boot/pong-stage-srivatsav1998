# MainMenu

## Feature

Menu for starting the game or changing settings for the game

## Acceptance Criteria

### Scenario: Selecting start game

  Given player 1 and player 2 are ready as per game mode

  When player 1 selects start game

  Then the game starts.

### Scenario: Selecting settings option

  Given player 1 and player 2 are ready as per game mode

  When player 1 selects settings option

  Then we see a settings page with all the settings

### Scenario: Player 2 tries to select options

  Given player 1 and player 2 are ready as per game mode

  When player 2 tries to select an option in main menu

  Then nothing happens on the screen.
