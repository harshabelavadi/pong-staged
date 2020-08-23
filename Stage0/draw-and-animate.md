# Game graphics

## Feature

This module is responsible for drawing different objects, texts and animating them.

## Acceptance Criteria

### Scenario: Display and animate texts in menus

Given: Main menu options and pause menu options.
When: User is either in main menu or pause menu.
Then: Option texts should be drawn and
transition animation between options should be applied.

### Scenario: Draw paddles

Given: Height, width and co-ordinates of the object to be drawn.
When: User game-play has started.
Then: The paddles for both user and CPU should be drawn and
positioned on given coordinates on the board.

### Scenario: Draw obstacles

Given: User game-play is in progress; Height, width and
co-ordinates of the object to be drawn.
When: User completes a level.
Then: The new obstacles are drawn and
positioned on given coordinates on the board.

### Scenario: Display relevant messages

Given: User game-play has started; User game-play is in progress.
When: User has either started the game-play or
paused the game-play or user completes the level.
Then: Display relevant messages depending on given scenario with animation.

### Scenario: Apply different color to background, objects, texts

Given: Game is in main menu screen; User game-play has started;
User game-play is in progress.
When: User has configured texts and objects color in settings.
Then: Display background, objects and
texts in user configured color.

### Scenario: Ball collides with paddle

Given: User game-play is in progress; Co-ordinates of paddle and ball.
When: Any one of co-ordinates of user paddle and ball are same.
Then: Ball should move in opposite direction of collision
by calling relevant function to modify its co-ordinates.

### Scenario: Ball collides with obstacles

Given: User game-play is in progress; Co-ordinates of obstacles and ball.
When: Any one of co-ordinates of an obstacle and ball are same.
Then: Ball should move in opposite direction of collision
by calling relevant function to modify its co-ordinates.
