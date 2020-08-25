# CollisionEventHandler

## Feature

It detects the collision with wall or paddle and
sends the corresponding event.

## Acceptance Criteria

### Scenario: When the ball hits the paddle

  Given we have positions of ball and paddles

  When the ball hits the paddle

  Then a paddle hit event is raised to BallEventHandler

### Scenario: When the ball hits the player 1 wall

  Given we have positions of ball and paddles

  When the ball hits the player 1 wall

  Then player 2 score update event is raised to scoreCounter
  and ball position reset event is raised to BallEventHandler.

### Scenario: When the ball hits the player 2 wall

  Given we have positions of ball and paddles

  When the ball hits the player 2 wall

  Then player 1 score update event is raised to scoreCounter
  and ball position reset event is raised to BallEventHandler.
