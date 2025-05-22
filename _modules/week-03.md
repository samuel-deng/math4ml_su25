---
title: Calculus and Optimization I (differentiation and Taylor Series)
---
Jul 15
: [Lecture: Differentiation and vector calculus]({{ site.baseurl }}/assets/slides/3.1_derivatives.pdf)
    : ["Peaks" Function]({{ site.baseurl }}/assets/figs/localglobal3d.html), [Derivative Ex. 1]({{ site.baseurl }}/assets/figs/partial1.html),
    [Derivative Ex. 2]({{ site.baseurl }}/assets/figs/partial2.html), [Derivative Ex. 3]({{ site.baseurl }}/assets/figs/partial3.html), [MML 5.1 - 5.5](https://mml-book.github.io/book/mml-book.pdf), [The Matrix Cookbook](https://www.math.uwaterloo.ca/~hwolkowi/matrixcookbook.pdf)

Jul 17
: [Lecture: Taylor Series, Linearization, and Gradient Descent]({{ site.baseurl }}/assets/slides/3.2_taylor.pdf)
    : [GD Example 1 (big eta)]({{ site.baseurl }}/assets/figs/3.2/gd1_etabig.html), [GD Example 1 (small eta)]({{ site.baseurl }}/assets/figs/3.2/gd1_etasmall.html), [GD Example 2 (big eta)]({{ site.baseurl }}/assets/figs/3.2/gd2_etabig.html), [GD Example 2 (small eta)]({{ site.baseurl }}/assets/figs/3.2/gd2_etasmall.html), [Linearization in 3D]({{ site.baseurl }}/assets/figs/3.2/linearization3d.html), [Polynomial 1]({{ site.baseurl }}/assets/figs/3.2/poly3d1.html), [Polynomial 2]({{ site.baseurl }}/assets/figs/3.2/poly3d2.html), [Beta-smooth function]({{ site.baseurl }}/assets/figs/3.2/smooth1.html), [3Blue1Brown video on Taylor Series](https://www.youtube.com/watch?v=3d6DsjIBzJ4&t=223s)

Jul 18
: [PS 3]({{ site.baseurl }}/assets/files/ps3.pdf) released, due July 29, 11:59 PM ET
  : [ps3.pdf]({{ site.baseurl }}/assets/files/ps3.pdf), [ps3_template.zip]({{ site.baseurl }}/assets/files/ps3_template.zip), [ps3.ipynb]({{ site.baseurl }}/assets/files/ps3.ipynb), [ps3_tex.zip]({{ site.baseurl }}/assets/files/ps3_tex.zip)

LS (Story thus far)
: Lecture 3.1, 3.2: We can derive the exact same OLS theorem from linear algebra section from just the tools of optimization and viewing the notion of [least squares error as an "objective function."]({{ site.baseurl }}/assets/figs/pd_ls.html)

GD (Story thus far)
: Lecture 3.1: We can now write down the *algorithm* for gradient descent. Intuitively, [positive semidefinite]({{ site.baseurl }}/assets/figs/psd_gd.html) or [positive definite]({{ site.baseurl }}/assets/figs/pd_gd.html) quadratic forms seem good for gradient descent.
: Lecture 3.2: Using Taylor's approximations and Taylor's theorem for the first-order approximation (linearization), we can provide intuition and a formal guarantee that gradient descent makes the function values decrease. The behavior of gradient descent depends on the learning rate eta: [eta too big will result in erratic behavior]({{ site.baseurl }}/assets/figs/3.2/gd2_etabig.html) but [small enough eta]({{ site.baseurl }}/assets/figs/3.2/gd1_etasmall.html) results in stable convergence.