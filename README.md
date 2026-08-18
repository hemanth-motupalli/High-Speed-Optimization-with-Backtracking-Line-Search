# High-Speed Optimization with Backtracking Line Search

## Overview
This repository focuses on implementing and benchmarking advanced numerical optimization algorithms. The project evaluates the efficiency of Gradient Descent, Newton's Method, and the Quasi-Newton BFGS algorithm, specifically enhancing their convergence rates through the integration of a Backtracking Line Search (Armijo condition).

## Key Features
* **Custom Optimizer Implementations:** Built Gradient Descent, Newton's Method, and BFGS algorithms from scratch using NumPy.
* **Backtracking Line Search:** Integrated dynamic step-size calculation to ensure sufficient objective decrease per iteration.
* **Hessian Scaling Analysis:** Explored the impact of diagonal scaling matrices on conditioning and convergence speed.
* **Scalability Benchmarking:** Tested the BFGS algorithm on high-dimensional non-convex functions (up to $n=10000$ variables), comparing iteration counts and execution times.

## Tech Stack
* **Language:** Python
* **Libraries:** NumPy, Matplotlib

## Repository Structure
* `Optimization_Algorithms.ipynb`: The Jupyter/Colab notebook containing the algorithm implementations and benchmarking tests.
* `Optimization_Report.pdf`: A detailed technical report outlining the mathematical formulations, convergence analysis, and visualization of the results.
* `Problem_Statement.md`: A summary of the objective functions and the specific algorithmic tests performed.
