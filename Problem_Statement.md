# Problem Statement: Optimization Algorithm Benchmarking

## Objective
The primary goal is to implement and evaluate first-order and second-order numerical optimization algorithms, specifically focusing on the performance improvements provided by Backtracking Line Search and Hessian scaling.

## Test Functions
1. **Quadratic Function (Ill-Conditioned):**
   $f(x) = x_1^2 + 4x_1x_2 + 1600x_2^2$
   *Goal:* Analyze the Hessian condition number and compare standard Gradient Descent against Scaled Gradient Descent.

2. **Sum of Square Roots (Strictly Convex):**
   $q(x) = \sqrt{x_1^2 + 4} + \sqrt{x_2^2 + 4}$
   *Goal:* Evaluate Newton's Method with a fixed step size versus Newton's Method augmented with Backtracking Line Search.

3. **Generalized Rosenbrock Function (Non-Convex, High-Dimensional):**
   $f(x) = \sum_{i=1}^{n-1} [4(x_i^2 - x_{i+1})^2 + (x_i - 1)^2]$
   *Goal:* Benchmark the execution time and iteration count of the Quasi-Newton BFGS algorithm for $n \in \{1000, 2500, 5000, 7500, 10000\}$.
