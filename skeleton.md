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