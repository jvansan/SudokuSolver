# SudokuSolver
A simple program for solving sudoku puzzles.

Takes a simple representation of a board as an input. Samples can be found in the 
`puzzles` directory. 

The input at this point must conform to the format provided in the samples, where 
given the values are input as a 9x9 grid of numbers separated by spaces. Given 
values should be input and blanks should be input as '0'. 

### Example input:
```
0 0 6 0 0 8 5 0 0
0 0 0 0 7 0 6 1 3
0 0 0 0 0 0 0 0 9
0 0 0 0 9 0 0 0 1
0 0 1 0 0 0 8 0 0
4 0 0 5 3 0 0 0 0
1 0 7 0 5 3 0 0 0
0 5 0 0 6 4 0 0 0
3 0 0 1 0 0 0 6 0
```


## Usage:
`python solve_sudoku.py input.file`

## Requirements:
See `requirements.txt`
