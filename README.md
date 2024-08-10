Here's a sample README for the Tic Tac Toe game code:

---

# Tic Tac Toe Game

This is a simple implementation of the classic Tic Tac Toe game in Python, allowing two players to compete in multiple rounds until they choose to quit. The game keeps track of the score for each player.

## Features

- **Two-Player Mode**: Two players can play against each other on the same device.
- **Scoreboard**: The game maintains a scoreboard, displaying the current scores of both players after each round.
- **Multiple Rounds**: Players can continue playing rounds of Tic Tac Toe until they choose to quit.
- **Win and Draw Detection**: The game detects winning conditions for each player and also recognizes when the game ends in a draw.

## How to Play

1. **Player Names**: The game starts by asking each player to input their names.
2. **Choose Symbol**: Each player can choose to play as `X` or `O`.
3. **Gameplay**: Players take turns to choose a position on the 3x3 grid. The first player to align three of their symbols vertically, horizontally, or diagonally wins the round.
4. **Continue or Quit**: After each round, players can choose to continue playing or quit. The final scoreboard will be displayed upon quitting.

## Code Overview

### Functions

- **`print_tic_tac_toe(values)`**: Displays the current state of the Tic Tac Toe board.
- **`print_scoreboard(score_board)`**: Displays the current scores of both players.
- **`check_win(player_pos, cur_player)`**: Checks if the current player has won by matching any of the winning combinations.
- **`check_draw(player_pos)`**: Checks if the game is drawn by determining if all positions are filled without a winner.
- **`single_game(cur_player)`**: Manages the gameplay for a single round of Tic Tac Toe.

### Main Program

- **Player Setup**: The game starts by prompting both players to enter their names.
- **Game Loop**: Players alternate between choosing their symbol (`X` or `O`) and playing rounds of Tic Tac Toe.
- **Winning and Drawing**: The game checks for wins or draws after each move.
- **Scoreboard Update**: The scoreboard is updated based on the outcome of each round.
- **Quit Option**: Players can choose to quit the game, at which point the final scores are displayed.

## How to Run the Game

To play the game, run the Python script in a terminal or command prompt:

```sh
python tic_tac_toe.py
```

Follow the on-screen instructions to enter player names, choose symbols, and play the game.

## Example

Below is an example of how the Tic Tac Toe board looks during the game:
![Screenshot](Screenshot%202024-08-11%20033924.png
)

https://github.com/zuhaakashif/TicTacToe/blob/main/Screenshot%202024-08-11%20033924.png

```
     |     |     
  X  |  O  |  X  
_____|_____|_____
     |     |     
  O  |  X  |  O  
_____|_____|_____
     |     |     
  X  |     |  X  
     |     |
```

In this example, player `X` wins the game by aligning three `X`s diagonally.

## Conclusion

This Tic Tac Toe game is a simple yet fun way to engage in friendly competition. Feel free to enhance the game by adding more features or improving the interface!

---

You can modify the content to better suit your project or add more details if necessary.
