---
layout: page
title: Course Content
description: Listing of course modules and topics.
---

# Course Content
{:.no_toc}
This page includes all the content for the course thus far. We will update this page with all lecture materials, readings, and homework
as the class goes on.

1. TOC
{:toc}

## Schedule and Main Content

This class has six main modules, two for each "pillar" of machine learning: linear algebra, calculus  and optimization,
and probability and statistics. All class files will be available here. For a more detailed outline of the course thus 
far, see the [Course Skeleton]({{ site.baseurl }}{% link skeleton.md %}).

- Lecture slides can be found by clicking on the lecture title for the appropriate day.
- All the materials and reading on the right column is **optional**, but reading (a subset of) these materials before each lecture might help digesting the content during lecture.
- Problem sets will be posted here, as well as their solutions.

This is a tentative schedule and is subject to change. Readings, slides, and assignments will be posted as the class goes on. 

**Optional readings.** *MML* refers to [*Mathematics for Machine Learning*](https://mml-book.github.io/) by Marc Peter Deisenroth, A. Aldo Faisal, and Cheng 
Soon Ong. *VMLS* refers to [*Introduction to Applied Linear Algebra - Vectors, Matrices, and Least Squares*](https://web.stanford.edu/~boyd/vmls/) by Stephen Boyd
and Lieven Vandenberghe.

**Story of the course.** As the lectures go on, the goal will be to develop two main ideas from machine learning: *least squares regression (LS)* and
*gradient descent (GD)*. During each lecture, we will build these ideas with the mathematical tools from that lecture; at the same time,
we'll gradually develop a "picture" of LS and GD as the course goes on. An evolving 3D rendering of each "picture" will be linked
in each module below.

**Problem sets.** The problem sets will usually look relatively long, but much of it is exposition -- the problems in this course are
mostly structured to guide you through the discovery or derivation of some result or perspective on a concept. As such, the problem
sets serve the double purpose of some "required reading" interspersed with problems for you to fill in the gaps.

**Lecture pace.** It's really easy, in my experience, to get lost in a math lecture when lots of derivations or proofs are involved. At the
same time, though, it can often be intimidating to speak up for fear of asking a "dumb question" (no such thing!). To this end, during
every lecture, I'll have a fully anonymous interactive poll to keep an eye on how people are feeling during lecture and I'll check it intermittently,
especially during proofs. When prompted to regsiter, just click "Skip for now." [The poll link is here.](https://pollev.com/samdeng)

**Unit reviews.** At the end of each "pillar" of the course, we will hold an optional unit review session to make sure that everyone is on the same page before moving onto the next session. These will be informal recitations where we recap the [Course Skeleton]({{ site.baseurl }}{% link skeleton.md %}) to get a big picture view and, more importantly, answer any questions and confusion you might have. The dates/times/locations will be posted here and on the [Calendar]({{ site.baseurl }}{% link calendar.md %}).

{% for module in site.modules %}
{{ module }}
{% endfor %}

## Resources
I'll update this with additional resources as the class progresses. Feel free to use these or ignore completely. If you
know of any additional resources that you think would be helpful for the class, let me know and I'll add it here!

### LaTeX
- [Overleaf](https://www.overleaf.com), the Google Docs for LaTeX. Can be used for all the assignments in this class.
- Overleaf's guide to [learn LaTeX in 30 minutes](https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes#Display_math_mode)
- David Xiao's [Beginner's guide to LaTeX](https://www.cs.princeton.edu/courses/archive/spr10/cos433/Latex/latex-guide.pdf)
- Eddie Kohler's [LaTeX usage notes](https://www.read.seas.harvard.edu/~kohler/latex.html). These might be worth a browse to rectify common stylistic problems with using LaTeX.
- [Detexify](https://detexify.kirelabs.org/classify.html), an applet to get the LaTeX command for any handwritten symbol.

In general, Googling an issue you're having with LaTeX usually provides a plethora of solutions.

### Python
- [Whirlwind Tour of Python](https://github.com/jakevdp/WhirlwindTourOfPython) should have most everything you need to get up to speed with the programming required in this course.
- A condensed version of this *Whirlwind Tour of Python* can be found here: [python_crashcourse.ipynb]({{ site.baseurl }}/assets/figs/2d_regression.html).
- Here is a [video]() going through this crash course in case you want to get up to speed in video format.

### Linear Algebra Prerequisites
If you need to refresh any linear algebra, these may be good resources.

- *Linear Algebra and Applications* by Gilbert Strang
- [Gilbert Strang's MIT Course on Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/)
- *Linear Algebra Done Wrong* by Sergei Treil, available free as [PDF here](https://www.math.brown.edu/streil/papers/LADW/LADW.html)
- [Daniel Hsu's course notes for Computational Linear Algebra](https://www.cs.columbia.edu/~djhsu/CLA/)
- [3Blue1Brown's Essence of Linear Algebra videos](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)

### Multivariable Calculus Prerequisites
If you need to refresh any multivariable calculus, these may be good resources.

- [MIT OpenCourseware course on multivariable calculus](https://ocw.mit.edu/courses/18-02sc-multivariable-calculus-fall-2010/)
- *Vector Calculus, Linear Algebra, and Differential Forms: A Unified Approach* by Barbara Burke Hubbard and John H. Hubbard.
- *Vector Calculus* by Susan Jane Colley

### Probability Theory and Statistics Prerequisites
If you need to refresh any probability and statistics, these may be good resources.

- [*Introduction to Probability for Data Science*](https://probability4datascience.com/) by Stanley H. Chan
- *A First Course in Probability*  by Sheldon Ross.
- [*Introduction to Probability*](https://drive.google.com/file/d/1VmkAAGOYCTORq1wxSQqy255qLJjTNvBI/edit) by Joseph K. Blitzstein and Jessica Hwang.
- *Probability and Statistics for Engineers and Scientists* by Ronald E. Wadpole.