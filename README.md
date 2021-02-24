# SAT_solver
SAT_solver for solving Sudoku puzzles

The program receives as input a file with Sudokus in "sdk.txt" format. It is automatically implementing the Sudoku rules.

To run the program, type "SAT -Sn inputfile" or "SAT -Sn inputfile -Dm", where Dm is optional;

n takes values from 0 to 5, representing the heuristics: 0 - no heuristic; 1 - random; 2 - DLIS; 3 - DLCS; 4 - Minimum; 5 - JW; 

m takes the value 4 or 9, representing the dimension. The default dimension is 9.

The program outputs the solution(s) in a ".out" file with the same name as the input file and in the same location.
