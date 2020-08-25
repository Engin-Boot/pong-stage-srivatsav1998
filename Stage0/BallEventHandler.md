# BallEventHandler

## Feature

Handles position, speed and direction of the ball.

## Acceptance Criteria

### Scenario: When a paddle hit event received

  Given the BallEventHandler is listening for events

  When it receives paddle hit event from CollisionEventHandler

  Then it changes the direction of the ball and increases the speed
  of the ball.

### Scenario: When a ball position reset event is received

  Given the BallEventHandler is listening for events

  When it receives ball position reset event from CollisionEventHandler

  Then it resets the position of the ball.
