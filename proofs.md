---
layout: page
title: Main Proofs
description: This page includes a main result and sketch from each lecture.
---

# Main Proofs and Sketches
{: .no_toc }
This page includes the main proof from each lecture that (in my
opinion) would be most valuable to understand how to reproduce by heart. By
design, each lecture contains a proof that pulls together most of the important
ideas in that lecture's notes, and being able to prove the main result yourself
(without referring back to the notes) would be a good indication that you have a
good grasp of the material in that lecture.

Each proof below includes an outline of the main "ingredients" in proving each
result, in bullet points.

It might be helpful to use this page to gauge your understanding of a set of
lecture notes when reviewing them. To systematically use this page, the
following "drill" might help:

1. Read over the theorem statement and identify the premises (the "if" parts)
   and the conclusion (the "then" part). Write them clearly on some piece of
   paper.
2. Read over the proof of the theorem statement in the lecture notes, and try to
   "chunk" or compartmentalize the big ideas in the proof into single sentences.
   You'll notice that a lot of the "filler" of a proof includes mechanical
   details that you might instinctively do if you knew the big idea guideposts
   (i.e. cancelling terms out, expanding squares, etc.). Write out your "chunked"
   understanding of the proof on your piece of paper.
3. Compare your "chunks" for the proof to the ingredients I have listed below.
   Synthesize your own understanding with these ingredients and write down a
   short summary (in your own words) of the key steps in the proof, ommitting
   any "filler" that you are confident that you can do yourself by instinct.
4. Try writing out the proof with *only* this synthesized summary as a guide.
   Make sure you don't skip steps and can justify each line. If you get really
   stuck, refer back to the acutal proof in the lecture notes as an "answer key."
5. Finally, try writing out the proof without referring to either the
   synthesized summary or the lecture notes. If you can do this, you can be
   pretty confident that you've learned the proof by heart!

I'll upload a video example of me doing this for one of these proofs so the
process is more clear.

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Lecture 1.1: Vectors, matrices, and least squares (Tues May 27)
**Theorem (OLS, rank = d, n >= d, Linear Algebra Proof).** Found on page 69 of 1.1 slides.
Ingredients:
1. **"Pythagorean Theorem."** Any other vector in columnspace of X gives a larger error.
2. **Orthogonality.** y_hat - y is orthogonal to columnspace of X.
3. **Invertibility of X^T X.** Property that if X is full rank, then X^T X is invertible to solve normal equations.

Technically, you learned the formal proof of each of these ingredients in Lecture 1.2, so, in reviewing, you should
make sure you use the formal statements from Lecture 1.2.

## Lecture 1.2: Subspaces, bases, and orthogonality (Thurs May 29)
**Theorem (Projection with orthogonal matrices and ONB).** Found on page 89 of 1.2 slides.
Ingredients:
1. **OLS Theorem from 1.1.** This gives the form of the minimizer.
2. **Semi-orthogonal matrix and properties of ONB.** Orthonormal vectors inner product to 1 with themselves and inner product to 0 with other orthonormal vectors.
3. **Definition of projection.** A projection matrix is a *linear transformation* that computes the closest point for a subspace you care about.

## Lecture 2.1: Singular Value Decomposition (Tues Jun 3, 2025)
**Theorem (OLS, minimum norm least squares solution).**  Found on page 89 of 2.1 slides.
Ingredients:
1. **Definition of pseudoinverse.** Use the correct definition of pseudoinverse for full SVD and compact SVD.
2. **Definition of SVD.** Try to prove this using both the compact and full SVD. Understand which matrices are orthogonal/semi-orthogonal in both cases.
3. **Proof strategy: showing a minimizer.** To show something is a a minimizer, show that your choice is smaller than the thing you want to minimize when plugging in any other choice (same strategy as OLS Theorem above).

## Lecture 2.2 Eigendecomposition and Positive Semidefinite Matrices (Thurs Jun 5, 2025)
**Algorithm (Improved Facial Recognition with Eigenfaces).** Found on page 72 of 2.2 slides.
Ingredients:
1. **Covariance matrix.** Use the definition of the (unnormalized) covariance matrix for X^T X. 
2. **Basis of eigenvectors and spectral theorem.** Spectral theorem applies to symmetric matrices. 
3. **Definition of projection.** Use the projection result from Lecture 1.2 with this specific eigenvector ONB.

Note that this is not really a theorem with a proof, so there's nothing really to prove. Just make sure you can formally
write down what this algorithm is and understand how the eigenvectors come into play.

## Lecture 3.1: Differential Calculus (Tues Jun 10, 2025)
**Theorem (OLS, rank = d, n >= d, Calculus Proof).** Found on page 118 of 3.1 slides.
Ingredients:
1. **Gradient rules.** Gradient of quadratic form, gradient of linear functional, and gradient of constant function.
2. **First-order condition.** Set the gradient equal to zero and solve to get normal equations.
3. **Second-order condition.** Take the Hessian and use that it is positive definite (due to the **Invertibility of X^T X** from Lecture 1.1).

Technically, we didn't prove the first-order condition and second-order condition yet at this stage (this will be proven
in Lecture 4.1). You can assume they work (or, once you get to Lecture 4.1, try to prove them from heart).

## Lecture 3.2: Linearization, Gradient Descent, and Taylor's Theorem (Thurs Jun 12, 2025)
**Theorem (Descent Lemma).** Found on page 164 of 3.2 slides.
Ingredients:
1. **First-order Taylor's Theorem.** Apply first-order Taylor's Theorem to the current step of GD and the next step.
2. **Use linear algebra on the first-order approximation.** Simplify using linear algebra, keeping in mind the usual trick: if we want to show that something is smaller than something else, show that you're adding a nonnegative quantity.
3. **Smoothness to bound the quadratic form.** The quadratic form in Taylor's Theorem gets bounded by the bound we get from smoothness and the eigenvalue. This is how we get the choice of learning rate.