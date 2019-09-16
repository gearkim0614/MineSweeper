# MsSaSiM
How to install: http://lindawills.ece.gatech.edu/misasim/index.html

# MineSweeper
The goal of this project is to write programs that solve a minesweeper game. If you've never
played Minesweeper1 (or Mines in Linux), your first task is to play the game for hours (as
important research). In Minesweeper, there is an 8x8 minefield of squares, originally all
unopened. Hidden mines are buried under m squares in the field. Normally, if you step on a
mine by opening one of these squares, Game Over ... except in this class project! In ours, it is
not fatal to step on a mine if you are making a “necessary guess” when no local inferences are
possible, as explained below. As you open squares, numbers are revealed (unless you open a
mined square, in which case a bomb is shown). A number on a square indicates how many mines
are in the immediately adjacent squares surrounding it. Based on this information, the object of
the game is to infer where the mines are and to place flags on those squares.

# Result

|| Baseline Program | My Program |
| --- | --- | --- |
| Static code size: | 120 | 107 |
| Dynamic instruction length: | 22,195 | 195 |
| Storage required: | 40 | 9 |

![Minesweep](https://user-images.githubusercontent.com/32786111/64939392-d3803200-d82e-11e9-82aa-7295bdf387fe.JPG)
