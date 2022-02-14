# sudoku_solver

View notebook <a href = "https://github.com/mcconvillec/sudoku_solver/blob/main/sudoku_graph_colouring.ipynb">here</a>

## Introduction

The chromatic number of a graph refers to the minimum number of colours that are required to colour in all vertices of a graph such that no two connected vertices have the same colour.

This graph colouring problem has several useful applications in Management Science, including scheduling and timetabling. In this instance we will apply the colouring problem to solving a Sudoku puzzle using an integer linear programming formulation.

The rules of the Sudoku as they apply to this example are as follows:

1) The Sudoku board is a 9x9 matrix composed of 81 cells, further subdivided into 9 individual 3x3 groupings. Each box must be filled with a number between 1-9
2) No two boxes in the same row or column may have the same number
3) No two boxes in the same 3x3 grouping may have the same number