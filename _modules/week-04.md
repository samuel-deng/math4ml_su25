---
title: Calculus and Optimization II (optimization and convexity)
---
Jun 17
: [Lecture: Optimization and the Lagrangian]({{ site.baseurl }}/assets/slides/4.1_optimization.pdf)
    : [Constrained least squares (ridge regression)]({{ site.baseurl }}/story_ls/ls4_1.html), [MML 7.1 - 7.2](https://mml-book.github.io/book/mml-book.pdf)
: [PS 4]({{ site.baseurl }}/assets/files/ps4.pdf) released (due June 27 11:59 PM ET)
  : [ps4.pdf]({{ site.baseurl }}/assets/files/ps4.pdf), [ps4_student.zip]({{ site.baseurl }}/assets/files/ps4_student.zip), [ps4.ipynb]({{ site.baseurl }}/assets/files/ps4.ipynb)

Jun 19
: Class rescheduled to Friday, June 20th due to Juneteenth

Jun 20
: [Lecture: Convexity and convex optimization]({{ site.baseurl  }}/assets/slides/4.2_convexity.pdf) (Changed time and location: 12:45pm - 4pm in CSB 451)
    : [MML 7.3](https://mml-book.github.io/book/mml-book.pdf), [Convexity Definition in 3D]({{ site.baseurl }}/assets/figs/convex3d_def1.html), [Convexity First-order Definition in 3D]({{ site.baseurl }}/assets/figs/convex3d_def2.html), [Boyd and Vandenberghe's Convex Optimization Chapters 1 - 3](https://stanford.edu/~boyd/cvxbook/)

Jun 20
: **DUE**{: .label .label-blue } **PS 3 due**

LS (Story thus far)
: Lecture 4.1: In some applications, it may be favorable to [*regularize* the least squares objective]({{ site.baseurl }}/story_ls/ls4_1.html) by trading off minimizing the objective with the norm of the weights.
: Lecture 4.2: The least squares objective is a [convex function]({{ site.baseurl }}/assets/figs/convex3d_def1.html) (also: [first-order definition]({{ site.baseurl }}/assets/figs/convex3d_def2.html)); applying [gradient descent takes us to a global minimum](https://samuel-deng.github.io/assets/lec/running_example.html)

GD (Story thus far)
: Lecture 4.1: Nothing new here.
: Lecture 4.2: Applying [gradient descent to beta-smooth, *convex* functions takes us to a global minimum](https://samuel-deng.github.io/assets/lec/running_example.html). One such function is the least squares objective.
