# 2048 Game

The game is written using JavaScript, HTML and SCSS.
Rules of the game.
Each round, a tile appears with a value of “2” (with a 90% probability) or “4” (with a 10% probability)
By pressing the arrow, the player can throw all the tiles of the playing field in one of 4 directions. If, when discarding, two tiles of the same value “fly” into one another, then they turn into one, the value of which is equal to the sum of the connected tiles. After each move, a new tile with a value of “2” or “4” appears on a free section of the field. If, when you press the button, the location of the tiles or their value does not change, then the move is not made.
If there are more than two tiles of the same value in one row or in one column, then when discarded they begin to connect on the side in which they were directed. For example, tiles in the same row (4, 4, 4) will turn into (8, 4) after a move to the left, and into (4, 8) after a move to the right. This processing of ambiguity allows you to more accurately formulate a game strategy.
For each connection, game points increase by the value of the resulting tile.
The game ends in defeat if it is impossible to perform an action after the next move.

    - [DEMO LINK](https://andrii-rykal.github.io/2048-Game/)
