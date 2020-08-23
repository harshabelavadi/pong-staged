# Game Levels

## Feature

This module is responsible for incrementing levels, interacts with drawObjects module
to draw obstacles to increase difficulty as user levels up.

## Acceptance Criteria

### Scenario: User completes the level

Given: User game-play is in progress.
When: Duration of game-play at a certain level
exceeds predefined threshold (can be in seconds or certain clockticks).
Then: Level completed message should be displayed,
update user game profile and
user should be navigated to next level screen.

### Scenario: Ball movement pace

Given: User game-play is in progress.
When: User completes a level.
Then: The pace of ball movement should increase
by predefined value of speed parameter.

### Scenario: Obstacles should change

Given: User game-play is in progress.
When: User completes a level.
Then: The new obstacles are generated for new level.

### Scenario: Level number on game-play screen

Given: User game-play is in progress.
When: User completes a level.
Then: Level number should be incremented.
