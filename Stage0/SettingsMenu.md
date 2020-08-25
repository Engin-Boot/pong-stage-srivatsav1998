# SettingsMenu

## Feature

Menu for controlling activities like (music, sound, themes etc)

## Acceptance Criteria

### Scenario: Selecting sound off

  Given player 1 and player 2 are ready as per game mode
  and game sound is on

  When player 1 selects sound off

  Then sound for the game goes off.

### Scenario: Selecting music off

  Given player 1 and player 2 are ready as per game mode
  and game music is on

  When player 1 selects music off

  Then music for the game goes off.

### Scenario: Selecting sound on

  Given player 1 and player 2 are ready as per game mode
  and game sound is off

  When player 1 selects sound on

  Then sound for the game goes on.

### Scenario: Selecting music on

  Given player 1 and player 2 are ready as per game mode
  and game music is off

  When player 1 selects music on

  Then music for the game goes on.

### Scenario: Player 2 tries to select options

  Given player 1 and player 2 are ready as per game mode

  When player 2 tries to select an option in settings menu

  Then nothing happens on the screen.
