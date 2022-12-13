# Quantum Computing

## 2x2 Sudoku 

The Sudoku solver finds solutions for a 2x2 Sudoku, subject to the following constraints:
1) The 2x2 sudoku is binary, i.e. the cells can only have values 0 or 1
2) No number appears twice in the same row
3) No number appears twice in the same column
We use Grover's Algorithm to find solution states [0110] and [1001].

## Triangle Finding Problem

The Triangle Finding Problem is a famous graph theory problem. In this problem, we are given a graph (a set of edges) that may or may not contain a triangle. Our task is to find the triangle/s within the graph and point out the nodes that form the triangle.

Our solver uses Grover's Algorithm. It takes the list of edges as input and outputs the set of nodes that form the triangle.
