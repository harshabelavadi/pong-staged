# Game Menus

## Feature

This module is responsible for prompting main menu, profiles menu and pause menu.

## Acceptance Criteria

### Scenario: Main menu

Given: Game is installed and has started.
When: Game has started for the first time or
player quits the game and switches back to main game screen.
Then: Main menu should display new game, load game,
delete profile and settings options.

### Scenario: New game option in main menu

Given: Main menu is being displayed.
When: New game option is selected.
Then: User should enter details like name, email to create new profile
and proceed to start game.

### Scenario: Load profiles menu

Given: User selects load game option in main menu.
When: User already has existing account with previous game saved.
Then: User can select one of profiles to load the game at the level
from where it was left off previously.

### Scenario: Delete profiles menu

Given: User selects delete profile option in main menu.
When: User already has existing accounts with previous game saved.
Then: User can delete any one of profiles.

### Scenario: Settings menu

Given: User selects settings option in main menu.
When: User selects different color for texts, background or objects.
Then: Texts, background or objects color in the game should change.

### Scenario: Pause menu

Given: User game-play is in progress.
When: User pauses the game by pressing escape key.
Then: Pause menu should appear, resume game and exit options should be
displayed for user to choose.

### Scenario: Pause menu options

Given: Pause menu being displayed.
When: User selects resume option or
user selects exit option.
Then: Game is resumed if user selects resume option or
user should be navigated back to main menu if exit option is chosen.

### Scenario: Game over menu

Given: User game-play is in progress.
When: User loses the game.
Then: Game over menu should appear, replay game
and exit options should be displayed for user to choose.

### Scenario: Game over options

Given: Game over menu being displayed.
When: User selects replay option or
user selects exit option.
Then: Game is restarted from the same level
where user lost if user selects replay option or
user should be navigated back to main menu if exit option is chosen.
