# About Dataset
## Context
This dataset includes A/B test results of Cookie Cats to examine what happens when the first gate in the game was moved from level 30 to level 40. When a player installed the game, he or she was randomly assigned to either gate_30 or gate_40.

## Content
The data we have is from 90,189 players that installed the game while the AB-test was running. The variables are:

* __userid__: A unique number that identifies each player.
* __version__: Whether the player was put in the control group (gate_30 - a gate at level 30) or the group with the moved gate (gate_40 - a gate at level 40).
* __sum_gamerounds__: the number of game rounds played by the player during the first 14 days after install.
* __retention_1__: Did the player come back and play 1 day after installing?
* __retention_7__: Did the player come back and play 7 days after installing?

When a player installed the game, he or she was randomly assigned to either.