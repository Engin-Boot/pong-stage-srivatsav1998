# ControllerEventListener

## Feature

Listens to the controller events

## Acceptance Criteria

### Scenario: When it listens to an event corresponding to up movement

  Given the controller to which it is listening is available

  When I move the controller up

  Then the event listener should send up movement event to event handler.

### Scenario: When it listens to an event corresponding to down movement

  Given the controller to which it is listening is available

  When I move the controller down

  Then the event listener should send down movement event to event handler.

### Scenario: When it listens to an event corresponding to left movement

  Given the controller to which it is listening is available

  When I move the controller left

  Then the event listener should send left movement event to event handler.

### Scenario: When it listens to an event corresponding to right movement

  Given the controller to which it is listening is available

  When I move the controller right

  Then the event listener should send right movement event to event handler.
