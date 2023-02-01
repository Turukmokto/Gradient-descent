# Gradient-descent
1. Implement gradient descent with a constant step. Investigate convergence at different step sizes.

2. Match the step change function to improve convergence. For example exponential or stepped.

3. Implement some one-dimensional search method (dichotomy, Fibonacci method, golden section method) and gradient descent based on it. Compare efficiency in terms of the number of calculations of the minimized function and its gradients.

4. Make a one-dimensional search taking into account Wolfe's conditions and investigate the efficiency.

5. Analyze the gradient descent trajectory for several quadratic functions: come up with two or three quadratic two-dimensional functions on which the method will work, draw graphs with level lines functions and method trajectories.

6. Explore how the number of iterations required for gradient descent depends on convergence, on the following two parameters:

(a) the condition number K < 1 of the function being optimized

(b) the dimension of the space of n optimized variables.

To do this, for the given parameters n and K, randomly generate
quadratic problem of size n with condition number K and run on it
gradient descent with some fixed required accuracy. Measure
the number of iterations T(n, K) that the method needed to make before convergence
(successful exit by stopping criterion).
