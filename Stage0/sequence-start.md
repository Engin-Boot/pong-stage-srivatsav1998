# Interaction Sequences

## Startup Sequence

1) When the StartGame module is triggered, all the paddles,
balls and score counter are initialized with the starting positions & values.

2) All the event handlers like ControllerEventListener, PaddleEventHandler,
CollisionEventHandler, and BallEventHandler are triggered.

3) Ball starts moving with the set initial speed in the default direction.

## Movement Initiation

1) ControllerEventListeners of corresponding Paddles, listen to controller events
and raise events to the PaddleEventHandlers

2) PaddleEventHandlers update the direction of paddles considering the assigned
direction of paddles

3) CollisionEventHandler continuously listens for collisions by fetching positions
of paddles and the ball. If there is a collision with paddles, it will raise the
corresponding event to BallEventHandler. Else, if there is a collision with wall,
it will raise event to scoreCounter.

## One score

1) When the scoreCounter receives the update score event, it will update the
score of the corresponding player.

2) If any of the player scores the maximum score, he is declared winner
and program quits.
