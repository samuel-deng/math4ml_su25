---
title: Calculus and Optimization II (optimization and convexity) -- SAM OUT OF TOWN
---
Jul 22
: [Lecture: Optimization and the Lagrangian]({{ site.baseurl }}/assets/slides/4.1_optimization.pdf) (recording in three parts in Video Library)
    : [Constrained least squares (ridge regression)]({{ site.baseurl }}/story_ls/ls4_1.html), [MML 7.1 - 7.2](https://mml-book.github.io/book/mml-book.pdf)
: **DUE**{: .label .label-blue } **PS 2 due**
    

Jul 24
: [Lecture: Convexity and convex optimization]({{ site.baseurl }}/assets/slides/4.2_convexity.pdf) (recording in one part in Video Library)
    : [MML 7.3](https://mml-book.github.io/book/mml-book.pdf), [Convexity Definition in 3D]({{ site.baseurl }}/assets/figs/convex3d_def1.html), [Convexity First-order Definition in 3D]({{ site.baseurl }}/assets/figs/convex3d_def2.html), [Boyd and Vandenberghe's Convex Optimization Chapters 1 - 3](https://stanford.edu/~boyd/cvxbook/)
: [PS 4]({{ site.baseurl }}/assets/files/ps4.pdf) released, due Aug 6th, 11:59 PM ET
  : [ps4.pdf]({{ site.baseurl }}/assets/files/ps4.pdf), [ps4_template.zip]({{ site.baseurl }}/assets/files/ps4_template.zip), [ps4.ipynb]({{ site.baseurl }}/assets/files/ps4.ipynb), [ps4_tex.zip]({{ site.baseurl }}/assets/files/ps4_tex.zip)

LS (Story thus far)
: Lecture 4.1: In some applications, it may be favorable to [*regularize* the least squares objective]({{ site.baseurl }}/story_ls/ls4_1.html) by trading off minimizing the objective with the norm of the weights.
: Lecture 4.2: The least squares objective is a [convex function]({{ site.baseurl }}/assets/figs/convex3d_def1.html) (also: [first-order definition]({{ site.baseurl }}/assets/figs/convex3d_def2.html)); applying [gradient descent takes us to a global minimum]({{ site.baseurl }}/assets/figs/3.2/gd1_etasmall.html).

GD (Story thus far)
: Lecture 4.1: Nothing new here.
: Lecture 4.2: Applying [gradient descent to beta-smooth, *convex* functions takes us to a global minimum]({{ site.baseurl }}/assets/figs/3.2/gd1_etasmall.html). One such function is the least squares objective.
