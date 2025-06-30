---
title: Probability and Statistics I (basic probability theory and statistical estimation)
---
Jun 24
: [Lecture: Basic Probability Theory, Models, and Data]({{ site.baseurl }}/assets/slides/5.1_probability.pdf)
    : [Regression setup w/ randomness]({{ site.baseurl }}/assets/figs/regression_noise.html), [MML 6.1-6.4](https://mml-book.github.io/book/mml-book.pdf), [Blitzstein and Hwang's Ch. 9 on Conditional Expectation](https://drive.google.com/file/d/1VmkAAGOYCTORq1wxSQqy255qLJjTNvBI/edit), [Leo Breiman's "Two Cultures" paper](https://www2.math.uu.se/~thulin/mm/breiman.pdf), [Carlos Fernandez-Granda's Probability for Data Science Overview](https://www.ps4ds.net/videos/probability.html)
: [PS 5]({{ site.baseurl }}/assets/files/ps5.pdf) released (due July 4 11:59 PM ET), no programming part
  : [ps5.pdf]({{ site.baseurl }}/assets/files/ps5.pdf), [ps5_student.zip]({{ site.baseurl }}/assets/files/ps5_student.zip)
: [Final paper reading evaluation]({{ site.baseurl }}{% link project.md %}) released. Evaluation due July 8 11:59 PM ET 

Jun 26
: [Lecture: Bias, Variance, and Statistical Estimators]({{ site.baseurl }}/assets/slides/5.2_estimation.pdf)
    : [Regression (d = 2) with test point]({{ site.baseurl }}/assets/figs/2d_regression_test.html), [SGD with batch size 1]({{ site.baseurl }}/assets/figs/sgd_batch1.html), [SGD with batch size 10]({{ site.baseurl }}/assets/figs/sgd_batch10.html)

Jun 27
: **DUE**{: .label .label-blue } **PS 4 due**
: Unit 2 Calculus Review Session (in video library)
    : [Handwritten notes]({{ site.baseurl }}/assets/files/unit2_review.pdf)

LS (Story thus far)
: Lecture 5.1: Modeled the regression problem with a [linear model with random errors]({{ site.baseurl }}/assets/figs/regression_noise.html). In this model, OLS is *itself* a random variable, so we will analyze its statistical properties.
: Lecture 5.2: Found two key statistical properties of OLS: OLS' expectation is the true linear model and its variance scales with the variance of the random errors.

GD (Story thus far)
: Lecture 5.1 and 5.2: Nothing new here.
