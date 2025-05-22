---
title: Linear Algebra II (singular value decomposition and eigendecomposition)
---
Jul 8
: [Lecture: Singular Value Decomposition]({{ site.baseurl }}/assets/slides/2.1_svd.pdf)
    : [3D SVD (unprojected)]({{ site.baseurl }}/assets/figs/3d_svd.html), [3D SVD (u1, u2)]({{ site.baseurl }}/assets/figs/3d_svd_u1u2.html), [3D SVD (u1)]({{ site.baseurl }}/assets/figs/3d_svd_u1.html), [Orthogonal Complement]({{ site.baseurl }}/assets/figs/ortho_comp.html), [Class Photo Singular Values]({{ site.baseurl }}/assets/figs/rank_k_values.html), [MML 4.2, 4.4, 4.5](https://mml-book.github.io/book/mml-book.pdf), [Daniel Hsu's Computational Linear Algebra (CLA) course notes on SVD](https://www.cs.columbia.edu/~djhsu/coms3251-f22/notes/svd.pdf), [Daniel Hsu's CLA interactive example of "best-fitting 1d subspace"](https://www.cs.columbia.edu/~djhsu/coms3251-f22/bfl.html)
: **DUE**{: .label .label-blue } **Project first evaluation due**

Jul 9
: [PS 2]({{ site.baseurl }}/assets/files/ps2.pdf) released, due July 22 11:59 PM ET (*updated from July 18, 11:59 PM ET*)
  : [ps2.pdf]({{ site.baseurl }}/assets/files/ps2.pdf), [ps2_template.zip]({{ site.baseurl }}/assets/files/ps2_template.zip), [ps2.ipynb]({{ site.baseurl }}/assets/files/ps2.ipynb), [ps2_tex.zip]({{ site.baseurl }}/assets/files/ps2_tex.zip)

Jul 10
: [Lecture: Eigendecomposition and PSD Matrices]({{ site.baseurl }}/assets/slides/2.2_eigen.pdf)
  : [Positive Definite Quad. Form]({{ site.baseurl }}/assets/figs/pd_gd.html), [Positive Semidefinite Quad. Form]({{ site.baseurl }}/assets/figs/psd_gd.html), [Indefinite Quad. Form (bad initialization)]({{ site.baseurl }}/assets/figs/indef_gd_bad.html), [Indefinite Quad. Form (good initialization)]({{ site.baseurl }}/assets/figs/indef_gd_good.html), [Quadratics are dominated by the degree-2 terms]({{ site.baseurl }}/assets/figs/quad242_stack.html), [MML 4.2, 4.4, 4.5](https://mml-book.github.io/book/mml-book.pdf), [3Blue1Brown on eigenvalues/eigenvectors](https://www.youtube.com/watch?v=PFDu9oVAE-g)

Jul 11
: **DUE**{: .label .label-blue } **PS 1 due**

LS (Story thus far)
: Lecture 2.1 & 2.2: [The problem of least squares regression is unified under the pseudoinverse.]({{ site.baseurl }}/story_ls/ls2_1.html)

GD (Story thus far)
: Lecture 2.1 (nothing new): [Gradient descent with a "bowl-shaped" function gets us to the minimum.]({{ site.baseurl }}/story_gd/gd1_1.html)
: Lecture 2.2: On quadratic forms, it seems that gradient descent on three different types of shapes has different behavior: [positive definite]({{ site.baseurl }}/assets/figs/pd_gd.html), [positive definite]({{ site.baseurl }}/assets/figs/psd_gd.html), and [indefinite]({{ site.baseurl }}/assets/figs/indef_gd_bad.html).