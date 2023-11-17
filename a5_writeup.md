# Assignment 5 Write up

Assignment 5 can be broken up into the following parts:
1. Import the Necessary Modules:
- `copy`: For creating deep copies of objects
- `Stack` and `Queue`: Custom implementations for DFS and BFS operations
2. Utility Functions: 
- `remove_if_exists`: Removes a specified element from a list if it exists, which is used to remove the possibilites from a cell
3. Board Class:
- Represents the Sudoku board
- Consists of functions that will find the most constrained cell, and update the board, which eliminates possible solutions
4. DFS & BFS Functions:
- `DFS`: Uses depth-first search to solve the Sudoku puzzle. It works by trying to fill the most constrained cell with potential values until a solution is found or backtracks if a mistake is made
- `BFS`: Uses breadth-first search to solve the Sudoku puzzle in a similar fashion to DFS but explores nodes level by level
5. Main Execution:
- Defines two different sets of initial moves for Sudoku puzzles
- Uses both DFS and BFS to solve each puzzle and prints the results


After completing the assignment, answer the following reflection questions:

## Reflection Questions

1. How do the performance and efficiency of the Depth-First Search (DFS) and Breadth-First Search (BFS) algorithms compare when solving Sudoku puzzles? In what scenarios might one approach be preferable over the other?

The difference between DFS and BFS is that DFS goes for the longest path to the solution while BFS goes for the shortest path. I would say that BFS would be better when the sudoku is close to being done while DFS could be used when there's not too many numbers filled in.


2. How did the choice of data structures (like the Stack for DFS and Queue for BFS) impact the implementation and functionality of the algorithms? Are there alternative data structures or design patterns that could have been used to achieve the same objectives?

The choice of data structures impact the implementation and functionality of the algortihims as stacks, the element inserted last comes out first while queues, the element inserted first comes at first, so the impact of the data strucutres impact the implementation and functionality as stacks would try to the find the hardest numbers while queue would start by finding the easiest numbers. I am not sure what other data strucutres could be used to better acheive the same objectives.


3. Considering the current implementation, how might the Sudoku solver be adapted or extended for larger puzzles or different types of grid-based logic games? How can the lessons learned from this assignment be applied to real-world problem-solving or optimization challenges?

The Sudoku solver could be adapted for larger puzzles or different types of grid-bases logic games by changing the code a bit to be able to do those puzzles. We already have most of the coding down but some changes are needed for the code to hold bigger sudoku boards. These lessons could be used in real-world problems as we could use codes like the sudoku solver to organize complex things that we would have a hard time solving.