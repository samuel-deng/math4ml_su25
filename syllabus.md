---
layout: page
title: Syllabus
description: >-
    Course syllabus and information.
nav_order: 2
---

# Syllabus
{:.no_toc}
This page contains the most updated syllabus for the course for the Summer A session of 2025.

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## What is this course?

This is an elective course meant to strengthen the mathematical fundamentals for students wishing to pursue further study in machine learning. The serious study of machine learning requires a student to be proficient in several prerequisite subjects: (i) linear algebra, (ii) multivariable calculus, and (iii) probability and statistics. This course assumes that the student has already taken courses in these subjects at the undergraduate level (it is not a replacement), but would like to be more comfortable with their mathematical maturity in any of these areas before approaching a formal course in machine learning at the level of, say, COMS 4771.

We will not give comprehensive treatment of each of these areas; instead, we will present the main results that are most relevant to the analysis and design of machine learning models. Alongside the theory, we will also motivate each topic with numerous applications and examples relevant to machine learning so they are more familiar when encountered in future study. The course will place a strong emphasis on giving a deep, multifaceted understanding of two particular concepts central to modern machine learning: linear regression and gradient descent.

Topics will include (but are not limited to): vector spaces, projections, singular value decomposition, eigenvalues and eigenvectors (linear algebra), vector calculus, continuous optimization, convex optimization (calculus and optimization), review of basic probability, statistical estimation, maximum likelihood estimation, and the multivariate Gaussian (probability and statistics).

### Structure of the course
This is a course with a loose story. The course is structured around two main ideas that underlie modern machine learning: least squares regression and gradient descent. Very informally, least squares regression is a classic way of modeling problems in machine learning (the “what”), and gradient descent is the workhorse algorithm that drives much of modern machine learning (the “how”). Every week, we’ll develop and motivate these two ideas in lecture with the tools and concepts you learn from each part of the course. As the class goes on, you’ll develop different perspectives on these two ideas from, first, what we learn in linear algebra, then calculus and optimization, and, finally, probability and statistics. The hope is that, by the end of the course, you’ll have a deep understanding of both these ideas in ML while also having two concrete “applications” to motivate all the abstract mathematical tools and concepts you learn in the course.

**If you'd like to see the original rationale for creating this course: [Rationale]({{ site.baseurl }}/assets/files/rationale.pdf).**

## Who, What, When, Where?

- **Instructor:** Samuel Deng ([samdeng@cs.columbia.edu](mailto:samdeng@cs.columbia.edu)).
- **Teaching Assistant:** Keir Dorchen (*kd2878 "at" columbia "dot" edu*).
- **Dates and times:** Tuesdays and Thursdays 5:30pm - 8:40pm ET.
- **Location:** 402 Chandler. My office hours will be in the DSI Suite in Conference Room 417 (enter Mudd at the 4F campus level, make a left in the opposite direction of the CS department towards Chef Mike's Pizza Pi).
- **Office Hours:** See the [Calendar]({{ site.baseurl }}{% link calendar.md %}) and watch for announcements on Ed for any changes.
  - Sam: Tuesdays 2pm - 4pm ET; Thursdays 2pm - 4pm ET, both in DSI 417 in Mudd. Zoom will be available on Thursday office hours (the link wil be available on Ed).
    - First three office hours (5/29, 6/3, 6/5) will have different location (see [Calendar]({{ site.baseurl }}{% link calendar.md %}) for updates).
    - Please come to my (Sam's) office hours once, if only to introduce yourself! 
    - If you can't make my office hours at any time this semester, I'll be happy to schedule a time to meet through email.
  - Keir: Wednesdays 1pm - 2pm ET; Fridays 1pm - 2pm ET in CSB 453.

## Prerequisites

This course is not meant to be a replacement for the undergraduate level courses that are already prerequisites to machine learning:
- Multivariable calculus at an undergraduate level (e.g., Math 1201, Math 1205).
- Linear algebra at an undergraduate level (e.g., Math 2010, COMS 3251).
- Probability theory (with calculus) at an undergraduate level (e.g., Stats 2015, Stats 1201). 
- Discrete mathematics at an undergraduate level (e.g., COMS 3203).

Instead, this course assumes familiarity with the above prerequisites and our main goal will be to focus on building up to advanced topics, techniques, and applications from the above subjects that may have been glossed over in an introductory course that will be useful in further study of machine learning. That being said, we *do not* assume that you are an expert in any of the above prerequisites to take this course; we hope that the additional practice you receive in this course gets you a little closer to that.

This course will also integrate some basic numerical Python programming to allow students to get comfortable with numerical computing packages such as `numpy` and `pandas` before using them more intensively in a future machine learning course. Because of this, we *recommend* previous exposure to basic Python programming, but this is not strictly required if you are willing to learn the basics as the course progresses. Previous exposure to programming (possibly in a different language) should be sufficient for this. The required programming for this course will be relatively light.

### Formal Prerequisites
**Required prerequisites:** These are *hard* prerequisites for the course:
- Linear Algebra, at the undergraduate level (e.g. Math 2010, COMS 3251).
- Discrete mathematics at the undergraduate level (e.g., COMS 3203).
  - Should have covered proofs and at least discrete probability up to random variables andd joint distributions (COMS 3203 does this).
- Single-variable calculus at the undergraduate level.
- Some programming course at the introductory level.

The above courses are strictly required to take this course.

**Suggested prerequisites:** These are the *soft* prerequisites for the course. These courses are not strictly required, but anticipate needing to engage in some self study if you haven't taken the following courses before:
- Multi-variable calculus at an undergraduate level (e.g. Math 1201, Math 1205).
- A full course on Probability and statistics at an undergraduate level (e.g. Stats 2015, Stats 1201).

If you are unsure if you meet the prerequisites above, please email the instructor.

## Resources and Links

There will be no official textbook for this course. Some optional reading will come from the textbook *Mathematics for Machine Learning* by Marc Peter Deisenroth, A. Aldo Faisal, and Chen Soon Ong, but all of the lecture content is from scratch. All slides will be published before each lecture in [Course Content]({{ site.baseurl }}{% link content.md %}) so students can follow along during lecture. Optional readings will occasionally be posted. Required readings are "integrated" within the problems sets; all the problem sets will be exposition-proof-exposition style, so you can follow along with the derivation while filling in interesting details yourself.

Though this class assumes that you’ve taken courses in each of the following areas, you may want to brush up. Along with *Mathematics for Machine Learning* by Marc Peter Deisenroth, A. Aldo Faisal, and Chen Soon Ong, here are a few more undergraduate-level resources for the following subjects.

### Linear Algebra
- *Linear Algebra and Applications* by Gilbert Strang
- [Gilbert Strang's MIT Course on Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/)
- *Linear Algebra Done Wrong* by Sergei Treil, available free as [PDF here](https://www.math.brown.edu/streil/papers/LADW/LADW.html)
- [Daniel Hsu's course notes for Computational Linear Algebra](https://www.cs.columbia.edu/~djhsu/CLA/)
- [3Blue1Brown's Essence of Linear Algebra videos](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)

### Multivariable Calculus
- [MIT OpenCourseware course on multivariable calculus](https://ocw.mit.edu/courses/18-02sc-multivariable-calculus-fall-2010/)
- *Vector Calculus, Linear Algebra, and Differential Forms: A Unified Approach* by Barbara Burke Hubbard and John H. Hubbard.
- *Vector Calculus* by Susan Jane Colley

### Probability Theory and Statistics
- [*Introduction to Probability for Data Science*](https://probability4datascience.com/) by Stanley H. Chan
- [*Introduction to Probability for Computing*](http://www.cs.cmu.edu/~harchol/Probability/book.html) by Mor Harchol-Balter
- [*Introduction to Probability*](https://projects.iq.harvard.edu/stat110/home) by Joseph K. Blitzstein and Jessica Hwang.
- *A First Course in Probability*  by Sheldon Ross.
- *Probability and Statistics for Engineers and Scientists* by Ronald E. Wadpole.

Additional resources can be found in the Resources section of the [Course Content]({{ site.baseurl }}{% link content.md %})
page, to be updated as the class progresses.

## Assignments and Grading Policy
This course will be evaluated on the basis of five weekly problem sets, a class participation grade, and a final project. For the Summer A session, there are no exams because of the accelerated schedule.

In the full course offering, we anticipate three exams for each third of the course (one exam for linear algebra, one exam for calculus and optimization, and one exam for probability theory).

### Problem Sets

To give you practice and reinforce the concepts learned in class, there will be five weekly problem sets. The problem sets will usually have about four to five theoretical problems with an additional coding exercise to reinforce the concepts and develop basic fluency in machine learning packages such as `numpy`, `pandas`, and `sklearn`. The problems will be proof-based, but we will aim to develop your mathematical maturity in reading and writing proofs throughout the course. 

Each problem set will be released on Tuesdays and will cover the material taught in lecture on Tuesday and Thursday that week. They will be **due the following Friday at 11:59pm ET,** which gives 11 days to complete each problem set. All problem sets should be submitted to [Gradescope](https://www.gradescope.com/courses/801399) as a PDF file, generated from LaTeX using the provided template files. Detailed homework submission instructions can be found in [HW Submission Instructions]({{ site.baseurl }}{% link homework.md %}).

This course is intended to prepare students for further courses in machine learning, which all require  typesetting (at least at Columbia). LaTeX is also a useful skill to have for future courses or research, and LaTeX documents just look clean. **Because of this, we will require that your assignments be typed in LaTeX to give you practice**; the problem sets in COMS 4771 are hard enough without needing to wrestle LaTeX typesetting issues! Resources and a submission template will be provided to learn LaTeX and gently onboard students. 

[Overleaf](https://www.overleaf.com) is the standard online platform for typesetting LaTeX, a bit like Google Docs. You are welcome to generate your LaTeX submissions however you'd like; we only need your PDF. [Here's a quick resource to get you up to speed for typesetting in LaTeX](https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes).

*Because of the accelerated summer schedule, less focus will be put on the coding aspect of the course as to not overwhelm students, particularly in the pilot version.*

Students are all expected to adhere to the Academic Honesty policy of the Computer Science Department; this policy can be found in full [here](https://www.cs.columbia.edu/academic/academic-honesty/). Please contact the instructor with any questions.

### References Policy
Any result that we've established in the class lecture notes can be referenced and used without proof for any problem on the problem sets. In order to use a result from class, cite the lecture that the result was from. Because this class takes linear algebra, multivariable calculus, and probability and statistics as prerequisites, any standard results from these courses may also be used on homework problems. You may use any textbook for these subjects to work the problems, but you must cite the textbook if you do.

You may consult certain outside materials, specifically lecture notes and videos of other classes, any textbooks, and research papers. You may not consult any other materials. For all outside materials used, you must provide a detailed acknowledgement of the precise materials used, in the appropriate homework problem. Whether or not you consult outside materials, you must always write up your solutions in your own words. If your homework writeup resembles any outside source in a way which suggests that you have violated the above policy, you may be suspected of academic dishonesty.

### Large Language Model (LLM) Policy
I assume that you are taking this elective course because you would like to strengthen your *own* mathematical foundations and become more skilled at the fundamentals of machine learning. Becoming strong at such fundamentals *requires* continual struggle with the material, just like how there is no substitute for physical practice for a concert pianist or successful athlete. In future courses, such as COMS 4771, there will be in-class exams that determine a large majority of your grade, so knowing and obtaining a deep understanding of these concepts by heart through continued practice is necessary. In my experience, the best way to really learn the material is to make sure all your thinking is done on your own (or with living, breathing peers who can express confusion and uncertainty). Because of this, for your own good, I *strongly suggest* you resist the temptation of using an LLM to solve your assignments at all. Offloading practicing scales or shooting three-pointers to a professional doesn't do anything for your own skill! And, hey, in the process of solving these problems yourself, you might even start to gain the knowledge specifically required to understand how these very large language models work.

Of course, there's no way for the instructor to really know whether you used an LLM. Due to this, please at least refrain from using LLMs to seek a verbatim answer on problem sets for your own good. If you must, you may query LLMs for prerequisite material you may have forgotten or to "explain" concepts in a simpler way. In any case, just as with outside materials, if you do decide to use an LLM for the assignments, you must cite the LLM you queried (e.g., ChatGPT, Claude, Gemini, etc.) and the specific prompt(s) you used for the problem.

### Late Policy
Every student has a total of 6 late days for the course. Late time is rounded *up* to the nearest day and is measured from submission time on Gradescope. **No homework will be accepted after 11:59 PM ET three late days after the initial due date**. This rule is here to allow us to post solutions to each of the problem sets in a timely manner. No further late days will be given for the course, so please plan accordingly. Late days may also be used for the course project.

 If you need an **emergency** exception to the late work policy, please email me before the due date with your reason(s) and a new proposed due date. I'm happy to discuss accommodations. 

### Regrade Policy
If you believe that a problem of yours has been graded incorrectly, submit a regrade request on Gradescope with a clear argument detailing why you believe
the grade is incorrect **within 7 days after the assignment is graded.** We will respond to your regrade request within a week. All regrades are final.

### Participation Grade
Because the summer session is a small class that will allow active discussion, there will be a participation grade for the course. This is also a dense and fast-paced course (especially in the summer), so the participation grade is also to incentivize you to actively show up to class each session and clarify in-person any confusions you might have about the material, although classes will be recorded *in case* you cannot make a class. Showing up to every class is *strongly recommended* (and is an easily maximized part of your grade)!

Showing up to each lecture will contribute 1 point to your 12 point total participation grade (there are 12 total lectures in the summer session). To get full participation, you need only show up to every lecture, which gives you a 12/12. To keep track of this, in the first week, I will circulate a sign-in sheet. After the first week, I should know everyone by name and face, so I will tally the attendance myself. If you *must* miss a lecture, there will be a recording available, but you will not receive the participation credit for that corresponding lecture.

### Course Project
The project of this course will be to *attempt* to read a research paper in machine learning. Emphasis on *attempt*: there is no expectation that you will understand every single detail in the paper. However, you might be pleasantly surprised that you understand a bit more than you would’ve at the beginning of the course just by strengthening your mathematical foundations.

There are three parts to this project:

1. **Choose a paper.** *Within the first week.* Take a look at the list of research papers below and choose a paper based on the title and abstract. You're free to choose whatever might look interesting to you. If you need help deciding, feel free to email the instructor or TA or post on Ed.
2. **Beginning of course evaluation.** *Before the second week.* You will attempt to read the whole paper. Research papers can be intimidating if you’ve never read one before (and even if you’ve read hundreds!) so we will provide some guidance on how to read a scientific paper in machine learning. Then, you will provide a critical evaluation of the paper to the best of your current ability based on the template below. This will be graded on completion and effort -- we emphasize that it does *not* matter how much you actually know or understand from the paper, just that you put a concerted effort into completing the evaluation and grappling with the paper.
3. **End of course evaluation.** *Final week.* At the end of the course, you will read the paper again. You will fill out a similar critical evaluation of the paper, per the same template, with a couple added questions. Again, you will be graded not on your understanding (though we hope it's improved the second time around!) but, rather, your concerted effort in writing an evaluation that shows that you've read and grappled with the paper to the best of *your* ability.

This project will be graded on the clarity and quality of the evaluation, but we stress that we will not focus on how much you “get” the paper. As long as you do the work of grappling with the paper and filling out the evaluation to the best of *your* ability, regardless of your understanding, you should get full marks, grade-wise. The emphasis of this project is on your own growth — hopefully, you’ll find that by the end of the course your chosen paper isn’t quite as perplexing as it may have seemed in the beginning.

### Grading Scheme
Your final grade in the course will be determined by the following formula:

*15% * (5 homeworks) + 13% * final project + 12% * participation = 100%*,

with the following hard grade cutoffs:
- A: 93.0% and above
- A-: 90.0 - 92.9%
- B+: 87.0 - 89.9%
- B: 83.0 - 86.9%
- B-: 80.0 - 82.9%
- C+: 77.0 - 79.9%
- C: 73.0 - 76.9%
- C-: 70.0 - 72.9%
- D: 60.0 - 69.9%

## Course Outline (Summer Schedule)
The course will be split into three main parts, for each “pillar” of mathematics that underlies machine learning. Throughout the course, we will aim to alternate between theory and application. In particular, the course will focus on developing two concepts that are central to machine learning: *least squares regression* and *gradient descent*. By the end of the course, the hope is that you have a varied and nuanced understanding of each of these concepts as well as scaffolding to "hang your hat on" for each of the disparate mathematical ideas we've learned/reviewed throughout the course. Other applications relevant to machine learning will also be introduced throughout.

Although each third of the course will focus on a certain mathematical theme, they will not be disjoint – each week will build on the one before, so we strongly encourage attending and carefully reviewing each lecture as the semester proceeds.

This is a course outline for a six week summer version. Because of the accelerated schedule, less focus will be put on the coding aspect of the course as to not overwhelm students, particularly in the pilot version.

*This is a preliminary outline of the class topics! For an updated outline and corresponding lecture materials, see [Course Content]({{ site.baseurl }}{% link content.md %}).*

### Linear Algebra
  - **Week 1-1 (Vectors, matrices, and least squares).** Vectors, matrices, basic linear algebra operations, inverses, rank, linear independence, span.
    - Least squares: introduce the basic ML problem of least squares regression in matrix-vector notation.
    - Gradient descent: introduce the "bowl-shaped" functional form of least-squares.
  - **Week 1-2 (Subspaces, bases, and orthogonality).** Subspaces, bases, inner products, orthogonality, orthogonal bases, and projection.
    - Least squares: relationship of projection to least squares. Least squares with an orthonormal basis simplifies things.
  - **Week 2-1 (Singular value decomposition).** Derivation of the singular value decomposition through the best-fitting subspace problem. Rank-k approximation. Pseudoinverse.
    - Least squares: unify ordinary least squares solution with the tool of the pseudoinverse, a "generalization" of inverses to rectangular matrices.
  - **Week 2-2 (Eigenthings and positive semidefinite matrices).** Eigendecomposition, eigenvalues, and eigenvectors. Spectral theorem. Relationship to the SVD. Definition of positive semidefinite/positive definite matrices and quadratic forms.
    - Gradient descent: (non-rigorous) teaser that gradient descent on different quadratic surfaces have different behavior: positive definite, positive semidefinite, and indefinite.

### Calculus and Optimization
  - **Week 3-1 (Differentiation and vector calculus).** Single-variable differentiation review. Multivariable differentiation. Total, directional, partial derivatives. Gradient. Hessian.
    - Least squares: obtain the same least squares theorem from the first lecture, but through the method of optimization and viewing the least squares objective as an "error function."
    - Gradient descent: armed with the notion of a gradient, we can now write down the basic algorithm for gradient descent.
  - **Week 3-2 (Taylor Series, Linearization, and Gradient Descent).** Linearization/first-order Taylor approximation. Taylor series. Analytic functions. Smoothness. Second-order Taylor approximation. Taylor's Theorem (Lagrange and Peano's forms). Gradient descent and proof for smooth functions.
    - Gradient descent: using intuition from Taylor approximations and Taylor's theorem we provide a proof that gradient descent is guaranteed to make function values decrease for smooth functions. This illuminates the dependence of GD on the learning rate.
  - **Week 4-1 (Optimization and the Lagrangian).** Constrained optimization problem setup. Lagrangian and the method of Lagrange multipliers. Unconstrained optima and local optimization. Equality-constrained optimization. Inequality-constrained optimization. KKT Theorem. Ridge regression and the minimum norm solutions.
    - Least squares: in some applications, it is favorable to *regularize* the least squares objective by trading off minimizing the objective with the norm of the weights.
  - **Week 4-2 (Convex optimization).** Convex sets. Convex functions. Different definitions of convex functions for different differentiability classes. "Algebra" (closure properties) of convex sets and functions. Convex optimization problems. Local minima are global minima theorem. Proof that gradient descent converges to global minimum for smooth, convex functions.
    - Least squares: recognize that the objective for least squares was a ("bowl-shaped") convex function all along. Relationship to positive definite quadratic forms.
    - Gradient descent: apply gradient descent to least squares, recognizing that we can now formally describe it as a convex, smooth function. Prove that on such functions, gradient descent converges to a global minimum.

### Probability and Statistics
  - **Week 5-1 (Basic probability theory, models, and data)**. Probability spaces and random variables. Distributions, joint, conditional, and marginal distributions of several random variables. CDFs, PMFs, and PDFs. Expectation, variance, and covariance. Conditional expectation. Random vectors. Data as random and the statistical model of machine learning. Modeling assumptions.
    - Least squares: modeled the familiar regression problem as a linear model with random errors. Prove that OLS' conditional expectation is the true linear model and its variance scales with the variance of the random errors.
  - **Week 5-2 (Bias, variance, and statistical estimators).** Law of large numbers. Statistical estimators. Bias, variance, and mean squared error of a statistical estimator. Stochastic gradient descent. Gauss-Markov Theorem for OLS. Statistical analysis of the "risk" of OLS.
    - Least squares: prove the Gauss-Markov theorem, that OLS is the lowest variance, unbiased estimator out of all linear estimators. Derive expression for the risk/generalization error of OLS.
    - Gradient descent: close our story of gradient descent with stochastic gradient descent, where unbiased estimates of the gradient are used instead of the full gradient over all the data. This makes gradient descent computationally feasible in modern applications.
  - **Week 6-1 (The Central Limit Theorem, "Named" Distributions, and Maximum Likelihood Estimation).** Gaussian distribution. Central Limit Theorem and proof of CLT through moment generating functions. Named distributions (e.g. uniform, Poisson, Bernoulli, Binomial, etc.). Maximum likelihood estimation (MLE). Connection between MLE and OLS.
    - Least squares: under the maximum likelihood estimation paradigm of machine learning, the OLS estimator corresponds to MLE on the Gaussian error model.
  - **Week 6-2 (Multivariate Gaussian and Course Overview).** Multivariate Gaussian PDF. OLS under Gaussian error model and relationship to multivariate Gaussian. Geometry of the multivariate Gaussian. Affine transformation, factorization, and other properties of the multivariate Gaussian. Review of the course, overview of our central "story" of least squares and gradient descent, and how all the math we learned fits in the story.
    - Least squares: under the Gaussian error model, the distribution of the OLS estimator is itself multivariate Gaussian.

## Collaboration Policy
Learning is best done in collaboration with peers. To this end, you will be allowed to collaborate with other students on the problem sets in groups **up to three students (including yourself)**. All collaborators must write the names and UNIs of their group at the top of each problem set (the template will have a space for you to do so). All collaborators must also *type up everything in their own words*. You are free to discuss, whiteboard, and brainstorm with your collaborators. However, when it comes to sitting down and solving the actual problem, you must do it yourself, away from your collaborators. If your homework writeup resembles that of another student in a way which suggests that you have violated the above policy, you may be suspected of academic dishonesty.

For the final project, only individual work is allowed. The final project is meant to track your own individual growth in mathematical maturity (which may have improved from collaborating with other students!), so you should aim to do all parts of it yourself.

## Auditor Policy
Auditors are welcome to join the class for now -- just email me and I'll set you up with the course resources. 

If you're auditing this class, you're more than welcome to come to all lectures, come to any office hours, and ask questions on Ed. You're also more than welcome to submit feedback about the course at any time on the website. However, grading will not be available to you -- we will **not** be able to grade your problem sets (although you should attempt them to learn the material!). Please do not submit your problem sets to Gradescope.

## Course Philosophy and Feedback
The goal of this course is to reinforce and deepen important mathematical fundamentals, gain better intuition of these mathematical tools, and develop confidence in mathematical maturity. All of these require work that may sometimes seem daunting, but I believe that any student is capable of growing in the course, so long as they continually grapple with the concepts and do the work. This may, at times, be difficult, but struggle is a totally normal part of the process. I was in your shoes, at one point (and still am!), and I can assure you that many of these concepts seem really difficult until they inevitably, after plugging away for a while, become natural. I hope you, the student, come away with this feeling as well.

By the nature of this course, students will come from widely different levels of background, and it is my job to make sure that no student is left behind or glossed over because of this. To this end, if there’s anything I can do to help you learn better, do not hesitate to contact me directly or leave anonymous feedback.

This is also a new course, so any feedback would be much appreciated to iterate and improve it! If you have any feedback at all about the course or my teaching of the course, please submit through this [anonymous feedback form](https://forms.gle/fYbJrUCgPyvJeM93A).