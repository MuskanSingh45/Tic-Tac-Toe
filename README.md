# Tic-Tac-Toe

A simple and interactive **Tic-Tac-Toe game** built using HTML, CSS, and JavaScript. The game allows two players to play against each other with an interactive game board, sound effects, and winning animations.

## Tech Stack

- HTML5
- CSS3
- JavaScript
- DOM Manipulation
- JavaScript Event Handling
- Audio

## How to Play

1. Player 1 starts the game.
2. Players take turns placing their mark on an empty cell.
3. The first player to get three marks in a row wins.
4. A winning combination can be:
   - Horizontal
   - Vertical
   - Diagonal
5. If all cells are filled without a winner, the game ends in a draw.
6. Use the restart/new game option to play again.

## Winning Conditions

A player wins when they get three of their marks in a row.

The possible winning combinations are:

```text
[ 0 ] [ 1 ] [ 2 ]
[ 3 ] [ 4 ] [ 5 ]
[ 6 ] [ 7 ] [ 8 ]

Horizontal:
0 → 1 → 2
3 → 4 → 5
6 → 7 → 8

Vertical:
0 → 3 → 6
1 → 4 → 7
2 → 5 → 8

Diagonal:
0 → 4 → 8
2 → 4 → 6
