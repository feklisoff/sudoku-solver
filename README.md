# sudoku-solver
a sudoku game with a generator and a solver

## Install
To play the game yourself, simply download the source code and run the _sudokuGame.py_. 
A GUI screen should pop up with a sudoku puzzle for you to solve, you will have a timer and see how many errors you've made along the way.

## Changing difficulty
To change the diffulty, change the integer value on line 30 in _sudokuGen.py_
```python
for i in range(17)
```
It represents how many values you want on your board, hence the lower the number the harder the setting.

## TODO:
* <s>fix the quitting bug</s>
* add a solution button
* limit losses to (n)
