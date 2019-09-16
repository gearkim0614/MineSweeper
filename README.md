# MiSaSiM
How to install: http://lindawills.ece.gatech.edu/misasim/index.html

# Language used
C & MIPS

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
| Dynamic instruction length: | 22,195 | 40,000 |
| Storage required: | 40 | 27 |
| Grade: | 100% | 100%+ |

![Minesweep](https://user-images.githubusercontent.com/32786111/64939954-a46ac000-d830-11e9-9c95-9a1924e05843.JPG)

# Disclaimer
This is for education purpose only. Actual code is not posted in compliance with Georgia Tech's Honor Code. All credit goes to Professor Linda Wills. https://www.ece.gatech.edu/faculty-staff-directory/linda-m-wills
