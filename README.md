# JS-Pig-Game
JavaScript tutorial project on the Pig game

## GAME RULES:

- The game has 2 players, playing in rounds
- In each turn, a player rolls a dice as many times as he whishes. Each result get added to his ROUND score
- BUT, if the player rolls a 1, all his ROUND score gets lost. After that, it's the next player's turn
- The player can choose to 'Hold', which means that his ROUND score gets added to his GLBAL score. After that, it's the next player's turn
- The first player to reach 100 points on GLOBAL score wins the game

[Play the game here](https://dahrahmohlah.github.io/JS-Pig-Game/).

### TODO list
- [X] A player looses his entire score when he rolls two 6 in a row, then next players turn. (branch: doubleSix)
- [X] Add input field where players can set winning score, rather than pre-defined score of 100. (branch: setWinScore)
- [ ] Add a second dice to game, player losses current score when one dice rolls a 1.
