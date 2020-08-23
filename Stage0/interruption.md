# Game Interruption

## Feature

This module is responsible for saving the state of game if exited abruptly.

## Acceptance Criteria

### Scenario: Game exited due to manual exit, software crash or power failure

Given: User already cleared some number of levels.
When: User gameplay is in progress.
Then: Latest level successfully completed
by the user should be saved in profile.
