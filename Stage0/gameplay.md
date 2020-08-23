# Game-play

## Feature

This module interacts with level module,
draw objects module continuously for animating objects
and is responsible for initiating and maintaining game-play.

## Acceptance Criteria

### Scenario: Game-play started

Given: User selects new game or resume game.
When: Game-play starts either at first level or loaded from last saved level.
Then: There should be an interval of three seconds
with timer displaying on the screen before the actual game-play
starts and all objects should be placed on predefined positions.

### Scenario: Player moves the paddle vertically

Given: User game-play has started and is in progress.
When: User presses direction keys (up/down).
Then: The paddle should move vertically at predefined speed.

### Scenario: CPU player auto-moves the paddle vertically

Given: User game-play has started and is in progress.
When: The ball collides with user paddle or
ball crosses a predefined threshold line on board.
Then: The paddle should randomly move vertically at predefined speed.

### Scenario: Current level should be displayed

Given: User game-play has started.
When: User game-play is in progress.
Then: Current level should be displayed.

### Scenario: Game over

Given: User game-play is in progress.
When: The ball goes behind user paddle.
Then: Game over menu should be prompted.
