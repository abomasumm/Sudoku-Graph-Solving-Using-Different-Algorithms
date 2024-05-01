**Repository Name: Sudoku Solver using Graph-based Search Algorithms**

### Overview

This repository contains Python code for solving Sudoku puzzles using graph-based search algorithms. Sudoku is a popular puzzle game that involves filling a 9x9 grid with digits so that each column, each row, and each of the nine 3x3 subgrids contains all of the digits from 1 to 9 without repetition. In this repository, you will see how each algorithm tries to solve sudoku as well as learn about their pros and limitations as solutions.

### Sudoku Solving Approach

The Sudoku solving approach implemented in this repository treats the puzzle as a constraint satisfaction problem (CSP) and models it as a graph. Each cell in the Sudoku grid represents a node in the graph, and the constraints (i.e., the rules of Sudoku) are represented as edges between nodes.

### Supported Algorithms

The following graph-based search algorithms are implemented for solving Sudoku puzzles:

1. **Breadth First Search (BFS)**: Explores all the neighbor nodes at the present depth prior to moving on to the nodes at the next depth level.

2. **Depth First Search (DFS)**: Explores as far as possible along each branch before backtracking.

3. **Uniform Cost Search (UCS)**: Expands the node with the lowest path cost.

4. **A Star Search**: Uses a heuristic function to estimate the cost of reaching the goal node from the current node and chooses the node with the lowest total cost.

5. **Greedy Search**: Selects the node that appears to be the closest to the goal according to some heuristic, without considering the cost of reaching that node.

### Usage

1. Clone the repository to your local machine:

```
git clone https://github.com/yourusername/sudoku-solver.git
```

2. Open the notebook(.ipynb) file

3. Input the Sudoku puzzle in the cell

4. Run all cells

### Example Input Format

The input Sudoku puzzle should be input in the cell containing a 9x9 grid. Here's an example:

```
0 0 3 0 2 0 6 0 0
9 0 0 3 0 5 0 0 1
0 0 1 8 0 6 4 0 0
0 0 8 1 0 2 9 0 0
7 0 0 0 0 0 0 0 8
0 0 6 7 0 8 2 0 0
0 0 2 6 0 9 5 0 0
8 0 0 2 0 3 0 0 9
0 0 5 0 1 0 3 0 0
```

### Output

The solver will print the solved Sudoku puzzle to the console step by step through the various algorithms. 

### Contributions

Contributions to this repository are welcome! If you have any suggestions for improvements or want to add support for additional search algorithms, feel free to submit a pull request.


### Acknowledgments

This project was inspired by the desire to explore graph-based search algorithms in the context of solving Sudoku puzzles as well as a school assignment. Special thanks to the contributors of the open-source community for their valuable insights and contributions.

### Contact

For any inquiries or feedback, please contact [abomasumm@gmail.com].
