# Sudoku Solver README

### CM50263 Artificial Intelligence Coursework - University of Bath

#### Introduction

This project is part of the coursework for the CM50263 Artificial Intelligence module as part of the MSc Computer Science course at the University of Bath. The main task involves the development of a Sudoku solver, implemented in a Jupyter notebook named `sudoku.ipynb`. 

The coursework will be graded based on the performance of the Sudoku solver, with automated tests assessing its accuracy and efficiency. The tests aim to differentiate between grade levels by evaluating the solver's ability to handle puzzles of varying difficulty.

#### Implementation Details

My proposed solution comprises several key components aimed at efficiently solving Sudoku puzzles:

- **Pre-Processing**: Initializes a grid of possible values for each cell in the Sudoku puzzle, identifying cells where only one value is possible. This step uses constraint propagation techniques to simplify the puzzle before applying more complex algorithms.

- **Dancing Links (Algorithm X)**: For cells where the pre-processing step does not conclusively determine a value, the implementation employs the Dancing Links algorithm (also known as Algorithm X) to solve the exact cover problem represented by the Sudoku puzzle.

#### Requirements

- Python 3.x
- NumPy
- Jupyter Notebook

#### Setup

1. Ensure Python 3.x and Jupyter Notebook are installed on your system.
2. Install NumPy using pip: `pip install numpy`
3. Open the `sudoku.ipynb` notebook in Jupyter Notebook.

