# 🧩 Sudoku Solver in Java

This project is a simple and efficient **Sudoku Solver** built using the **backtracking algorithm** in Java. It can solve any valid 9x9 Sudoku puzzle where empty cells are represented by `0`.

---

## 🚀 Features

- ✅ Solves any valid 9x9 Sudoku puzzle
- ✅ Uses recursion and backtracking
- ✅ Checks constraints for rows, columns, and 3x3 subgrids
- ✅ Clean, modular code with comments
- ✅ Console-based output

---

## 📂 File Structure

SudokuSolver.java → Main Java file containing the solution logic
README.md → Project documentation


---

## 📋 How the Algorithm Works

1. Traverse the Sudoku board cell by cell.
2. When an empty cell (value `0`) is found:
   - Try placing digits from 1 to 9.
   - For each digit, check if it's **safe** using:
     - Row validation
     - Column validation
     - 3x3 grid validation
3. If safe, place the digit and recursively solve the rest.
4. If it leads to a dead-end, **backtrack** by removing the digit.
5. Repeat until the board is completely filled or no solution exists.

---

## 🔢 Sample Input

```java
int sudoku[][] = {
    {0, 0, 8, 0, 0, 0, 0, 0, 0},
    {4, 9, 0, 1, 5, 7, 0, 0, 2},
    {0, 0, 3, 0, 0, 4, 1, 9, 0},
    {1, 8, 5, 0, 6, 0, 0, 2, 0},
    {0, 0, 0, 0, 2, 0, 0, 6, 0},
    {9, 6, 0, 4, 0, 5, 3, 0, 0},
    {0, 3, 0, 0, 7, 2, 0, 0, 4},
    {0, 4, 9, 0, 3, 0, 0, 5, 7},
    {8, 2, 7, 0, 0, 9, 0, 1, 3}
};
Solution exists
6 1 8 9 4 2 7 3 5 
4 9 7 1 5 7 8 6 2 
... (completed grid)
```
## 🧪 How to Run
Clone the repository or download SudokuSolver.java
Open a terminal or use any Java IDE
Compile and run:

javac SudokuSolver.java
java SudokuSolver

## 🙋 Author
Vishal Verma

📫 LinkedIn- www.linkedin.com/in/vishal-verma-6a99a5328

📌 GitHub- 2ViShAlv1

#Java #SudokuSolver #Backtracking #Algorithms #DSA #ProblemSolving #JavaProjects


