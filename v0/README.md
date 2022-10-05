# Island Databank Schema v0
#### This fork has the Regex strings from the original and strings for "contains" (When needed, of course).
## Global
* `titles` *(object)*: Contains different titles that are the same in all minigames.
	* `gameOver`*(regex)*: "Game Over"-title.
* `subtitles` *(object)*: Contains different subtitle strings that are the same in all minigames.
	* `win` *(regex)*: "1st Place!"
## Minigames
### Hole in the Wall
#### Properties
* `titles` *(object)*: Contains different titles that appear in Hole in the Wall.
	* `eliminated` *(regex)*: Title that appears to you when you jump off the platform.
* `chatStrings` *(object)*: Contains system chat messages that appear in Hole in the Wall.
	* `wallDifficultyIncrease` *(regex and contains)*: Message that appears when the wall difficulty increases during the game.
### Sky Battle
#### Properties
* `titles` *(object)*: Contains different titles that appear in Sky Battle.
	* `eliminated` *(regex)*: Title that appears to you when you die (any method).
