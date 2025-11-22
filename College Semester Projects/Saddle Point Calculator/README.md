M × N Zero-Sum Game Solver (Java Swing)

This is a Java Swing application designed to input, analyze, and solve zero-sum matrix games.
The tool allows users to enter a payoff matrix, generates its negative counterpart, and computes Maximin, Minimax, and Saddle Point results.

Features
1)GUI-based input for M × N matrices (supports up to 6 × 6)
2)Generates and displays:
  Matrix A (user input)
  Matrix B = –A (automatically computed)
3)Computes:
  Maximin value (row strategy)
  Minimax value (column strategy)
  Detects and reports the presence of a Saddle Point
4)Simple and intuitive interface with dedicated buttons for matrix generation and calculations
5)Uses Java Swing with absolute layout for precise control

How It Works
1)User specifies the matrix size (M × N, where 1 ≤ M, N ≤ 6).
2)Matrix A is entered manually.
3)The application computes Matrix B by negating each entry (B = –A).
4)It calculates:
  Maximin value from Matrix A
  Minimax value from Matrix B
5)The program compares their positions to determine whether a Saddle Point exists.

Instructions for Use
->Enter the number of rows (M) and columns (N).
->Click "Generate Matrix Fields" to create the input grid.
->Enter all values of Matrix A.
->Click "Calculate".
->The application will display:
  Matrix A and Matrix B
  Maximin and Minimax values
  Saddle Point result (if found)

Requirements
.)Java JDK 8 or higher
.)Any Java IDE or terminal environment capable of compiling and running Swing applications

Notes
Only integer inputs are supported
Provides clear error messages for invalid or incomplete inputs
Useful for students studying Game Theory concepts such as:
    *Zero-sum games
    *Maximin and Minimax strategies
    *Saddle Points
