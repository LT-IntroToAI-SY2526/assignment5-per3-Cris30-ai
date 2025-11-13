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

1. What are some things that you learned through this assignment? Think about the concepts of backtracking, constraint satisfaction, and search algorithms. Were there any particular challenges you faced while implementing the Board class methods or the DFS/BFS functions? How did you overcome them? 
This assignment taught be about backtracking and constraint satisfaction which was used to solve the Sudoku puzzles. By using the Board class helped me understand how DFS and BFS searches possibly states differently.Lastly, the biggest challenge to  overecome was managing the nested list, the solution was testing my code in small parts each step of the way. 



2. How can you apply what you learned in this assignment to future programs or projects? Consider other types of problems that involve searching through possibilities, making decisions, and backtracking when those decisions don't work out. Can you think of real-world scenarios where DFS or BFS might be useful? What about other constraint satisfaction problems?
I can used the concepts learned in this assignment to help solve problems like scheduling and AI decision-making. One real-world scenarios where DFS and BFS are in pathfinding(Such as Google Maps) where they explore possible path to the desire destination. Additionally, constraint satisfaction can also be implemented in resource allocation where rigours requirments must be met. All in all, within this assignment I learned how to solve real world problems by using complex search and decision making.




3. Explain how the Stack and Queue classes work and why they are important for DFS and BFS algorithms. Describe the difference between LIFO (Last In First Out) and FIFO (First In First Out) data structures. How does using a Stack versus a Queue change the way the search algorithm explores possible solutions? Why is one data structure better suited for depth-first search and the other for breadth-first search? 

The Stack and Queue classes oversee how the search alogirthm explores possible solutions. Moreover, a stack uses LIFO(last in First out) order by removing the newest part first, while FIFO(First in , First out) is used in a Queue is removes the oldest emlement first. Also, DFS uses a stack class to explore one path deeply beforce backtracking(depth). BFS uses a queue to explore level by level(breath). In closing, each data structure uses different approaches that suited the problem type. 