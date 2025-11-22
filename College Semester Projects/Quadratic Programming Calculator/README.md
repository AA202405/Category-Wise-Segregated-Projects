Quadratic Programming Solver

This application provides a graphical interface for formulating, solving, and visualizing Quadratic Programming (QP) problems using Karush–Kuhn–Tucker (KKT) conditions. 
It is designed for students and practitioners who wish to understand QP concepts through an interactive and visual tool.

Features
1)Supports both Minimization and Maximization problems
2)GUI-based input for all matrices and vectors
3)Handles problems with up to 4 variables and 4 constraints
4)Visualizes constraints and optimal solution in 2D (for 2-variable systems)
5)Includes a built-in help window with usage instructions
6)Clean, user-friendly interface built with Python and Tkinter

How to Use
.)Enter the number of variables (n) and constraints (m).
.)Click "Generate Matrices" to create the required input fields.
.)Fill in the following:
    Matrix Q (quadratic coefficients)
    Vector c (linear coefficients)
    Matrix A and Vector b (constraints in the form Ax ≤ b)
.)Select the optimization mode (Minimize or Maximize).
.)Click "Solve & Plot" to compute the solution and visualize it (when applicable).

Notes
*Plotting and graphical visualization are available only for 2-variable problems.
*The solver uses the Karush–Kuhn–Tucker (KKT) system to determine the optimal point.
*Suitable for academic use, demonstrations, and understanding the fundamentals of quadratic programming.
*Developed using Python, Tkinter, and Matplotlib.
