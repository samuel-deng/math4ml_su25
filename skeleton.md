---
layout: page
title: Course Skeleton
description: This is a course outline for the entire course, updated as we go.
---
# Course Skeleton
{: .no_toc }
This is lecture-by-lecture skeleton of the course meant to organize and bullet
point what we've learned so far in each class. It is not meant to replace notes
or going to class; it is here as a resource to help you, the student, have a bird's
eye view of the course's main ideas, definitions, and results.

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Lecture 1.1 (Mon July 1, 2024)
- **Definition (vector).**
  - "vector-vector multiplication."
    - **Definition (dot product/Euclidean inner product).**
      - Example of an **inner product.** 
      - notion of angle.
      - whenever we have an inner product, we have a **norm** (notion of length).
- **Definition (matrix).**
  - "matrix-vector multiplication."
    - linear combination view
    - system of equations view
  - "matrix-matrix multiplication."
    - inner product view (entry-by-entry)
    - matrix vector view (d different matrix-vector multiplications)
    - outer product view (r different rank-1 matrices added up)
  - **Definition (matrix inverse).** 
  - **Definition (transpose of a matrix).**
- **Definition (span).**
  - span(col(X)) is the columnspace of a matrix X.
- **Definition (linear independence).**
- **Definition (rank).**
  - number of linearly independent columns/rows
- **Problem: Regression.**
  - problem setup: n training examples, d "measurements" or "features."
  - our approach: find a linear model, *w.*
  - find *w* by the principle of *least squares regression.*
  - **Definition (sum of squared residuals).**
- **Prop: rank(X^T X) = rank(X).**
  - will prove next time
- **Theorem: Ordinary least squares solution.**
  - ingredient 1: pythagorean theorem and orthogonality.
  - ingredient 2: invertibility
  - solve the normal equations.
- **Story 1: least squares regression**
  - Got a solution to least squares regression by using geometric intuition and solving the normal equations.
- **Story 2: gradient descent**
  - The *sum of squared residuals* looks like a "bowl."

## Lecture 1.2 (Wed July 3, 2024)
- *Note:* to fit an intercept, add a "dummy" dimension of all 1's to go from d to d+1.
- **Definition (subspace).** 
- **Definition (basis).**
  - linear independence, span
- **Definition (columnspace).**
- **Definition (rank).**
- missing parts of **Theorem (OLS)**
  - **Theorem: invertibility of X^T X**
    - ingredient 1: definition of rank/linear independence
    - ingredient 2: positive definiteness of inner product
  - **Theorem: Pythagorean theorem**
    - ingredient 1: all the properties of inner products
    - ingredient 2: definition of orthogonality
  - **Theorem: projection minimizes distance**
    - ingredient: Pythagorean theorem
- **Definition (projection).**
  - equivalent to OLS
- **Definition (linearity).**
  - matrices as linear transformations and vice versa (HW problem)
  - one such linear transformation: projection
- **Definition (unit vector).**
- **Definition (orthonormal basis).**
- **Definition (orthogonal matrix).**
  - for rectangular matrices: **Definition (semi-orthogonal matrix).**
- **Theorem: Ordinary least squares with orthonormal basis.**
  - main theorem in this lecture -- simplifies OLS solution greatly (no inverses).
- **Story 1: least squares regression**
  - Filled in the "geometric intuition" with **Theorem: invertibility of X^T X** and **Theorem: projection minimizes distance**
  - Projection is equivalent to OLS.
  - When we have an orthonormal basis, we get a much simpler solution to OLS.
- **Story 2: gradient descent**
  - Nothing new: the *sum of squared residuals* looks like a "bowl."

## Lecture 2.1 (Mon July 8, 2024)
- **Definition (orthogonal complement).**
- **Properties (projection matrices).**
  - **Prop (Orthogonal decomposition).**
  - **Prop (Projection and orthogonal complement matrices)**
  - **Prop (Projecting twice doesn't do anything).**
  - **Prop (Projections are symmetric).**
  - **Prop (1D Projection formula).**
  - Proofs left as exercises -- ask Sam if you can't figure one of them out.
- **Problem: best-fitting 1D subspace.**
  - Use all the properties of projection matrices to get the final form.
  - Final form gives 1st singular vector and singular value.
- **Definition (Full SVD).**
  - **Definition (left singular vectors).** Give a basis for the columnspace.
  - **Definition (right singular vectors).** Give a basis for the rowspace (columnspace of X transpose).
  - **Definition (singular values).** Exactly *r* (rank of X) positive singular values.
- **Definition (Compact SVD).**
- **Theorem (rank-k approximation).**
  - "chop off" the SVD at k << r to get an approximation of a matrix.
- **Definition (pseudoinverse).**
  - "generalization" of the inverse using the SVD.
- **Theorem (OLS with pseudoinverse).**
  - Use the pseudoinverse as if it were the actual inverse to get the OLS solution, w
- **Theorem (minimum norm solution).**
  - Using the pseudoinverse gives us the minimum norm solution when d > n and rank(X) = n (infinitely many exact solutions).
- **Story 1: least squares regression**
  - The pseudoinverse unified all situations where we want a least squares solution (when d > n or n > d).
- **Story 2: gradient descent**
  - Nothing new: the *sum of squared residuals* looks like a "bowl."

## Lecture 2.2 (Wed July 10, 2024)
- **Definition (eigenvector).**
- **Definition (eigenvalue).**
- **Prop (Eigendecomposition of diagonalizable matrices).**
  - When are matrices diagonalizable?
  - Connection with the SVD.
- **Definition (Positive Semidefinite Matrices).**
  - Three definitions
    - All eigenvalues are nonnegative.
    - Associated quadratic form is nonnegative.
    - Can be "factored" into X^T X
- **Theorem (Spectral Theorem).** All symmetric matrices are diagonalizable.
- Application of eigenvectors/eigenvalues: PCA (principal components analysis).
- Quick analysis of errors in least squares with eigenvectors/eigenvalues.
- **Definition (Quadratic Forms).** Closely related to symmetric matrices.
  - Three possibilities
    - Positive definite
    - Positive semidefinite
    - Indefinite
- **Story 1: least squares regression**
  - Eigenvalues/eigenvectors allow us to analyze the errors in least squares regression.
- **Story 2: gradient descent**
  - Positive semidefinite and positive definite quadratic forms seem ripe for gradient descent.

## Lecture 3.1 (Mon July 15, 2024)
- **Definition (difference quotient).**
- **Definition (single-variable derivative).**
- Main idea: differential calculus allows us to replace nonlinear functions with linear approximations.
- **Definition (directional derivative).**
- **Definition (partial derivative).**
- **Definition (gradient).** Only for scalar-valued functions.
- **Definition (Jacobian).** For general vector-valued functions.
- **Definition (open ball/neighborhood).** The points local to a point.
- **Definition (total derivative/differentiable).** Notion of a multivariable derivative.
- **Definition (smoothness).** Continuously differentiable, the class C^1.
- **Theorem (Sufficient criterion for differentiability).** 
  - If a function is smooth, then it is differentiable and its derivative *is* its Jacobian/gradient.
- **Theorem (directional derivatives from total derivative).**
  - If a function is differentiable, we can get all directional derivatives from matrix-vector product with derivative.
- Big picture: if a function is smooth, then its derivative is its Jacobian/gradient (which we get from taking the partial derivatives).
  - Directional derivatives come from matrix-vector product with the Jacobian/gradient.
  - We'll primarily concern ourselves with smooth functions.
- **Definition (Hessian).**
- **Theorem (equality of mixed partials).** All C^2 functions have symmetric Hessians.
- **Theorem (OLS from optimization).**
- **Algorithm (gradient descent).**
- **Story 1: least squares regression**
  - We can obtain the same OLS theorem using only the tools of optimization/calculus.
- **Story 2: gradient descent**
  - We can now properly write out the algorithm for gradient descent now that we know what a gradient is.

## Lecture 3.2 (Wed July 17, 2024)
- **Definition (first-order approximation/linearization).**
- **Definition (polynomial).**
- **Definition (Taylor Series).** Defined at a point, x_0.
  - *pth order Taylor approximation*
    - We will mostly concern ourselves with first-order and second-order approximations.
  - *pth order Taylor polynomial*
- **Definition (Remainder from Taylor Series).**
  - The "leftover" after chopping off the Taylor series at some degree.
- **Theorem (Taylor's Theorem: Peano's Form).**
  - Quantifying the remainder/error asymptotically.
- **Theorem (Taylor's Theorem: Lagrange's Form).**
  - Quantifying the remainder/error exactly.
- **Algorithm (Gradient Descent).**
  - Finally defined gradient descent.
- **Definition (beta-smooth functions/matrices).**
  - Bound on the maximum eigenvalue.
- **Theorem (Gradient descent for beta-smooth functions).**
  - For beta-smooth functions, gradient descent with a small enough step size makes the function value smaller at each iteration.
  - Ingredients:
    - Lagrange's form of Taylor's Theorem (1st order approximation).
    - beta-smooth function definition.
- **Story 1: least squares regression**
  - Nothing too new here -- just reviewed obtaining OLS solution via optimization.
- **Story 2: gradient descent**
  - Formally wrote the algorithm and gave the first convergence proof of gradient descent for beta-smooth functions.

## Lecture 4.1 (Mon July 22, 2024)
- **Definition (optimization problem)**
  - **Definition (objective function)**.
  - **Definition (constraint set)**.
- **Definition (neighborhood/open ball)**.
- **Definition (interior point)**.
- Types of minima:
  - **Definition (local minimum)**. AKA unconstrained local minimum.
  - **Definition (constrained local minimum)**
  - **Definition (global minimum)**.
- **Theorem (Necessary conditions for unconstrained local minimum).**
  - First-order condition.
  - Second-order condition.
- **Theorem (Sufficient conditions for unconstrained local minimum).**
  - First-order condition.
  - Second-order condition.
- **Definition (Equality constrained optimization).**
- **Definition (regular point).**
- **Definition (Lagrangian).**
- **Theorem (Lagrange Multiplier Theorem).**
  - Necessary conditions for local minima in equality-constrained optimization.
- **Definition (inequality constrained optimization).**
- **Theorem (KKT Theorem).**
  - **Definition (complementary slackness)**
- **Definition (Ridge Regression).**
- **Theorem (Ridge Regression Estimator).**
- **Story 1: least squares regression**
  -  In some applications, it may be favorable to regularize the least squares objective by trading off minimizing the objective with the norm of the weights.
- **Story 2: gradient descent**
  - Nothing new here (we still can only guarantee *local minima*).

## Lecture 4.2 (Wed July 24, 2024) 
- **Definition (Convex Optimization Problem).**
- **Definition (line segment).**
- **Definition (convex set).**
  - Example: lines
  - Example: hyperplane
  - Example: halfspace
- **Definition (convex function).**
  - Example: quadratic forms
  - Example: affine functions
  - Example: exponential functions
- Three characterizations of convex functions.
  - Original definition (secants always above the graph).
  - First-order definition (gradient is always under the graph).
  - Second-order definition (Hessian is PSD).
- **Theorem (Optimality for convex optimization).**
  - All local minima are global minima.
- **Theorem (Convergence of GD for smooth, convex functions).**
  - Convergence of GD to global minimum.
- **Theorem (GD applied to OLS).**
  - Algorithm for OLS.
  - Verifying OLS is a convex optimization problem.
- **Story 1: least squares regression**
  - The least squares objective is a convex function; applying gradient descent takes us to a global minimum.
- **Story 2: gradient descent**
  - Applying gradient descent to beta-smooth, convex functions takes us to a global minimum. One such function is the least squares objective.

## Lecture 5.1 (Mon July 29, 2024)
- **Definition (probability space).**
  - **Definition (Sample Space).**
  - **Definition (Event).**
  - **Definition (Probability Measure).**
- **Definition (conditional probability).**
  - Law of total probability
  - Bayes rule.
- **Definition (Random Variable).**
 - **Definition (discrete RVs).**
 - **Definition (probability mass function).**
- **Definition (distribution/law of an RV).**
  - **Definition (Cumulative distribution function CDF).**
  - **Definition (Probability mass function PMF)** for discrete RVs.
  - **Definition (Probability density function PDF)** for continuous RVs.
- **Definition (joint distributions).**
  - **Definition (marginal distribution).**
  - **Definition (conditional distribution).**
- **Definition (independence).**
  - Independent and identically distributed.
- Summary statistics of a random variable:
  - **Definition (expectation).**
    - Conditional expectation given events.
    - Conditional expectation given a random variable.
  - **Definition (variance).**
  - **Definition (covariance).**
- **Definition (random vector).**
  - Expectation of a random vector.
  - Covariance matrix of a random vector.
- Regression setup with randomness.
  - Linear model with mean-zero, independent noise epsilon.
- **Theorem (statistical properties of OLS).**
- **Story 1: least squares regression**
  - Modeled the problem with linear model with random errors. Found that OLS' conditional expectation is the true linear model and its variance scales with the variance of the random errors.
- **Story 2: gradient descent**
  - Nothing new here.

## Lecture 5.2 (Wed, July 31, 2024)
- Statistics vs. probability theory.
- **Theorem (Weak Law of Large Numbers).**
  - Ingredients:
    - **Theorem (Markov's Inequality).**
    - **Theorem (Chebyshev's Inequality).**
- **Definition (sample average).**
- **Definition (statistical estimator).**
  - Estimand.
  - Estimator.
- **Definition (bias of estimators).**
- **Definition (variance of estimators).**
- **Definition (Mean squared error).**
- **Theorem (Bias-variance decomposition).**
- **Theorem (Statistical properties of OLS).**
  - With bias and variance.
- **Algorithm (Stochastic Gradient Descent).**
  - Single-sample SGD.
  - Mini-batch SGD.
- **Theorem (Gauss-Markov Theorem).**
  - Loewner order.
- **Theorem (statistical analysis of risk).**
  - Proof needs **Definition (trace).**
- **Story 1: least squares regression**
  - Demonstrated that OLS is the lowest variance *unbiased* linear estimator (Gauss-Markov Theorem). Derived expression for the risk (generalization error) of OLS.
- **Story 2: gradient descent**
  - Closed the story of gradient descent by defining *stochastic gradient descent*, where we use unbiased estimators of the gradient instead of the full gradient over all the data. 

## Lecture 6.1 (Mon August 5, 2024)
- **Definition (Gaussian Distribution).**
  - Properties:
    - General to standard.
    - Standard to general.
    - Sums of Gaussians.
- **Theorem (Central Limit Theorem).**
  - Ingredients:
    - **Definition (Moment generating function).**
    - **Definition (Convergence in distribution).**
- "Named" Discrete Distributions
  - Point mass distribution.
  - Discrete uniform distribution.
  - Bernoulli distribution.
  - Binomial distribution.
  - Geometric distribution.
  - Poisson distribution.
- "Named" Continuous Distributions
  - Uniform distribution.
  - Gaussian distribution.
  - Chi-squared distribution.
  - Exponential distribution.
- **Definition (Maximum likelihood estimation).**
  - Parameter space, parametric model.
  - Likelihood function.
  - Log-likelihood function.
- **Theorem (OLS and MLE).**
- **Story 1: least squares regression**
  - Demonstrated that, under another paradigm for machine learning (maximum likelihood estimation), the OLS estimator corresponds to MLE on the Gaussian error model.
- **Story 2: gradient descent**
  - Nothing new here.

## Lecture 6.2 (Wed August 7, 2024)
- **Definition (Multivariate Gaussian distribution)**
- **Theorem (Distribution of OLS under Gaussian Errors)**
- **Theorem (Factorization of MVN)**
  - Requires: diagonal covariance
- **Geometry of the MVN**
  - Shape of MVN comes from the eigendecomposition of the covariance matrix.
- **Theorem (Nondiagonal MVNs from Linear Transformations).**
- **Other properties of MVN**
  - Linear combinations are MVN.
  - Uncorrelated implies independent.
  - Marginal distributions are MVN.
  - Conditional distributions are MVN.
- **Story 1: Least squares regression**
  - The distribution of the OLS estimator itself is multivariate normal if we are in the Gaussian error model.
- **Story 2: gradient descent**
  - Nothing new here.