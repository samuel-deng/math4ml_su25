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

## Lecture 1.1: Vectors, matrices, and least squares (Tues May 27)
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

## Lecture 1.2: Subspaces, bases, and orthogonality (Thurs May 29)
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

## Lecture 2.1: Singular Value Decomposition (Tues Jun 3, 2025)
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