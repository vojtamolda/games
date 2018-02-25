
# Games and AIs :)


## Sheriff Chase - [`sheriff/`](sheriff/)
Implementation of value iteration, policy iteration and Q learning algorithms that search for the optimal
policy. The game is a simple deterministic implementation of an OpenAI gym environment extended to Markov
Decision Process.

<img src="sheriff/screenshot.png" alt="Sheriff Chase" width="60%">



## Game of Life - [`life/`](life/)
Gray-Scott reaction diffusion system and a simple cellular automaton with a fancy history fading visualization bundled
in one compact application.

<img src="life/screenshot-mac.png" alt="Game of Life (MacOS)" width="30%">



## Tetris - [`tetris/`](tetris/)
Yet another clone of the greatest game of all time. Peppered up with fancy tetrimino bouncing animation.

<img src="tetris/screenshot-mac.png" alt="Tetris (MacOS)" width="30%">



## Fourplay - [`fourplay/`](fourplay/)
Logical game for two with a quite-hard (but not impossible) to beat AI. One algorithm uses depth first search with
branch pruning of obviously wrong choices for speed-up and looks 8 moves ahead.

<img src="fourplay/screenshot-mac.png" alt="Fourplay (MacOS)" width="30%">



## Maze - [`maze/`](maze/)
Maze typically found in a children's magazine generated by a stochastic DFS algorithm. This guarantees that the end of
the maze is always hard to get to. Also check out the fancy ball animations :)

<img src="maze/screenshot-mac.png" alt="Maze (MacOS)" width="31%">



## Minesweeper - [`minesweeper/`](minesweeper/)
Clone of the only good software produced by a certain Seattle company...

<img src="minesweeper/screenshot-mac.png" alt="Minesweeper (MacOS)" width="30%">



## Tic-Tac-Toe - `tictactoe.py`
Oldie but goodie 3 by 3 noughts against crosses. Peppered up with a simple but never-losing AI. Good luck trying to
beat it!

__How to play__: Get three ◯s or ☓s in a row!

__Details__: [Wikipedia](https://en.wikipedia.org/wiki/Tic-tac-toe)

<img src="screenshots/tictactoe-mac.png" alt="Tic-Tac-Toe MacOS" width="20%"> <img src="screenshots/tictactoe-lnx.png" alt="Tic-Tac-Toe Ubuntu" width="20%"> <img src="screenshots/tictactoe-win.png" alt="Tic-Tac-Toe Windows" width="20%">



## Requirements
- [Python 3.6](https://www.python.org/downloads/)
- [PyQt5](https://riverbankcomputing.com/software/pyqt/download5) (May also work with [PySide](http://www.pyside.org/), but wasn't tested)
- [Numpy](http://www.numpy.org) (Only for `life.py`)


This work is licensed under the [MIT License](https://opensource.org/licenses/MIT) © 2017.
