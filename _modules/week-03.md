---
title: Calculus and Optimization I (differentiation and Taylor Series)
---
Jun 10
: [Lecture: Differentiation and vector calculus]({{ site.baseurl
}}/assets/slides/3.1_derivatives.pdf)
    : ["Peaks" Function]({{ site.baseurl }}/assets/figs/localglobal3d.html), [Derivative Ex. 1]({{ site.baseurl }}/assets/figs/partial1.html),
    [Derivative Ex. 2]({{ site.baseurl }}/assets/figs/partial2.html), [Derivative Ex. 3]({{ site.baseurl }}/assets/figs/partial3.html), [MML 5.1 - 5.5](https://mml-book.github.io/book/mml-book.pdf), [The Matrix Cookbook](https://www.math.uwaterloo.ca/~hwolkowi/matrixcookbook.pdf), [Annotated Slides]({{ site.baseurl  }}/assets/slides/3.1_derivatives_annotated.pdf)
: [PS 3]({{ site.baseurl }}/assets/files/ps3.pdf) released (due June 20 11:59 PM ET)
  : [ps3.pdf]({{ site.baseurl }}/assets/files/ps3.pdf), [ps3_student.zip]({{ site.baseurl }}/assets/files/ps3_student.zip), [ps3.ipynb]({{ site.baseurl }}/assets/files/ps3.ipynb)

Jun 12
: [Lecture: Gradient Descent, Linearization, and Taylor Series]({{ site.baseurl }}/assets/slides/3.2_taylor.pdf)
    : [3Blue1Brown video on Taylor Series](https://www.youtube.com/watch?v=3d6DsjIBzJ4&t=223s), [MML 5.8](https://mml-book.github.io/book/mml-book.pdf), [3Blue1Brown video on Gradient Descent and Neural Networks](https://www.youtube.com/watch?v=IHZwWFHWa-w)

Jun 13
: **DUE**{: .label .label-blue } **PS 2 due**

LS (Story thus far)
: Lecture 3.1: We can derive the exact same OLS theorem from linear algebra section from just the tools of optimization and viewing the notion of [least squares error as an "objective function."]({{ site.baseurl }}/assets/figs/pd_ls.html)

GD (Story thus far)
: Lecture 3.1: We can now write down the *algorithm* for gradient descent. Intuitively, [positive semidefinite]({{ site.baseurl }}/assets/figs/psd_gd.html) or [positive definite]({{ site.baseurl }}/assets/figs/pd_gd.html) quadratic forms seem good for gradient descent.
: Lecture 3.2: Using Taylor's theorem for the first-order approximation (linearization), we can provide intuition and a formal guarantee that gradient descent makes the function values decrease. The behavior of gradient descent depends on the learning rate eta: [eta too big will result in erratic behavior]({{ site.baseurl }}/assets/figs/running_example_etabig.html) but [small enough eta]({{ site.baseurl }}/assets/figs/running_example.html) results in stable convergence. This eta setting depends intimately on the second order information, or ["smoothness" of the function]({{ site.baseurl }}/assets/figs/running_example_nonsmooth.html)
