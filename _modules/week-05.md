---
title: Probability and Statistics I (basic probability theory and statistical estimation)
---
Jul 29
: [Lecture: Basic Probability Theory, Models, and Data]({{ site.baseurl }}/assets/slides/5.1_probability.pdf)
    : [Regression setup w/ randomness]({{ site.baseurl }}/assets/figs/regression_noise.html), [MML 6.1-6.4](https://mml-book.github.io/book/mml-book.pdf), [Blitzstein and Hwang's Ch. 9 on Conditional Expectation](https://drive.google.com/file/d/1VmkAAGOYCTORq1wxSQqy255qLJjTNvBI/edit)
: **DUE**{: .label .label-blue } **PS 3 due**

Jul 31
: [Lecture: Bias, Variance, and Statistical Estimators]({{ site.baseurl }}/assets/slides/5.2_estimation.pdf)
    : [Regression (d = 2) with test point]({{ site.baseurl }}/assets/figs/2d_regression_test.html), [SGD with batch size 1]({{ site.baseurl }}/assets/figs/sgd_batch1.html), [SGD with batch size 10]({{ site.baseurl }}/assets/figs/sgd_batch10.html)
: [Final paper reading evaluation]({{ site.baseurl }}{% link project.md %}) released. Evaluation due August 12 11:59 PM ET 

Aug 1
: [PS 5]({{ site.baseurl }}/assets/files/ps5.pdf) released, due Aug 13th, 11:59 PM ET (no programming portion)
  : [ps5.pdf]({{ site.baseurl }}/assets/files/ps5.pdf), [ps5_template.zip]({{ site.baseurl }}/assets/files/ps5_template.zip), [ps5_tex.zip]({{ site.baseurl }}/assets/files/ps5_tex.zip)

LS (Story thus far)
: Lecture 5.1: Modeled the regression problem with a [linear model with random errors]({{ site.baseurl }}/assets/figs/regression_noise.html). Found that OLS' conditional expectation is the true linear model and its variance scales with the variance of the random errors.
: Lecture 5.2: OLS is the lowest variance *unbiased* linear estimator (Gauss-Markov Theorem). Derived expression for the risk ([generalization error]({{ site.baseurl }}/assets/figs/2d_regression_test.html)) of OLS.

GD (Story thus far)
: Lecture 5.1: Nothing new here.
: Lecture 5.2: Closed the story of gradient descent by defining [*stochastic gradient descent*]({{ site.baseurl }}/assets/figs/sgd_batch1.html), where we use unbiased estimators of the gradient instead of the full gradient over all the data. 
