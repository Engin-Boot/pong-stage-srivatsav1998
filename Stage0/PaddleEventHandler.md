# PaddleEventHandler

## Feature

Handles the movement of paddle.

## Acceptance Criteria

### Scenario: When the handler receives up movement event from listener

  Given contoller event handler is running

  When handler receives up event

  Then the corresponding paddle moves up.

### Scenario: When the handler receives down movement event from listener

  Given contoller event handler is running

  When handler receives down event

  Then the corresponding paddle moves down.

  ### Scenario: When the handler receives left movement event from listener

  Given contoller event handler is running

  When handler receives left event

  Then the corresponding paddle moves left.

  ### Scenario: When the handler receives right movement event from listener

  Given contoller event handler is running

  When handler receives right event

  Then the corresponding paddle moves right.
