# tictactoe

This project is heavily inspired by an article that appeared in c't magazine using the algorithms Minimax, Negamax and Minimax with Alpha-Beta Pruning on the example of TicTacToe.

## Run

You need [Python](https://www.python.org/downloads/) and [Pipenv](https://pipenv.pypa.io/en/latest/installation.html) to run the Code.

### Linux, macOS, Windows

Install dependencies (PyGame):

```bash
pipenv install
```

Run:

```bash
pipenv run python tictactoe.py
```

Additional you have the following parameters:

```bash
-c, --computer        Let the computer make the first move instead of the player.
-m {random,minimax,minimax-ab,negamax}, --mode {random,minimax,minimax-ab,negamax} Select the algorithm the computer will use to make moves.
```

## License

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version, see <https://www.gnu.org/licenses/>.
