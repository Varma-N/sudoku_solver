# Sudoku Solver

## Description:
This repository contains a Python script for solving Sudoku puzzles using a backtracking algorithm. The Sudoku Solver reads a 9x9 Sudoku grid from user input, processes it to find a solution, and prints the solved grid or indicates if no solution exists. The script is designed to be interactive and user-friendly, allowing users to input each row of the Sudoku puzzle individually.

## Features:
Interactive Input: Enter each row of the Sudoku puzzle separately.
Backtracking Algorithm: Uses a backtracking approach to solve the Sudoku puzzle.
Validation: Checks for valid placements of numbers according to Sudoku rules.
Output: Displays the initial and solved Sudoku grids.

## Code Explanation:
print_board(board): Prints the Sudoku board in a readable format.
input_board(): Prompts the user to enter each row of the Sudoku grid and constructs the 9x9 board.
is_valid(board, row, col, num): Checks if placing a number in a given cell is valid according to Sudoku rules.
solve_sudoku(board): Uses a backtracking algorithm to solve the Sudoku puzzle.
main(): The entry point of the script, which manages user input, solves the Sudoku, and displays the results.

## Example:
Here’s an example of how to enter a Sudoku puzzle:
Enter each row of the Sudoku puzzle, with numbers separated by spaces. Use 0 for empty cells.
Enter row 1: 5 3 0 0 7 0 0 0 0
Enter row 2: 6 0 0 1 9 5 0 0 0
Enter row 3: 0 9 8 0 0 0 0 6 0
Enter row 4: 0 0 0 0 6 0 0 0 3
Enter row 5: 4 0 0 8 0 3 0 0 1
Enter row 6: 7 0 0 0 2 0 0 0 6
Enter row 7: 0 6 0 0 0 0 2 8 0
Enter row 8: 0 0 0 4 1 9 0 0 5
Enter row 9: 0 0 0 0 8 0 0 7 9
