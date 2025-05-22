---
layout: page
title: HW Submission
description: Homework submission instructions.
---
# Homework Submission Instructions

Submission for all the problem sets is handled through [Gradescope](https://www.gradescope.com/courses/801399). Each 
problem set should have about four to five written problems and one programming problem. Each problem set will be
released with a template file named `ps#_template.zip` and a Jupyter notebook file named `ps#.ipynb`. We'll also
upload the source code for the LaTeX of the problem set PDF in a file titled `ps#_tex.zip`, in case you'd like to
refer to the source for the problem set. If additional files are needed, that will be indicated on the problem set.

Problem sets will be made available in [Course Content]({{ site.baseurl }}{% link content.md %}) and announced on Ed. Per
the [Syllabus]({{ site.baseurl }}{% link syllabus.md %}), each student has 6 late days total throughout the summer session,
and **no homework will be accepted after 11:59 PM ET three late days after the initial due date**.

## Written Part
For all the written homework problems, **typesetting in LaTeX is required** (see [Syllabus]({{ site.baseurl }}{% link syllabus.md %})
for the rationale). On Gradescope, there will be a `PS #` assigment, where you'll submit a single `.pdf` file compiled from LaTeX.

A template file `ps#_template.zip` will be provided for each problem set, but it is not required that you use this template.
It should make things easier, but it's optional to use. If you decide to typeset with your own template, be sure to include
the following information *on the first page of your PDF*:

- Name
- UNI
- Problem Set Number
- Collaborator(s), if any

Failure to do so will result in a point deduction.

If you're using the template, download `ps#_template.zip` from [Course Content]({{ site.baseurl }}{% link content.md %}). If
working on Overleaf, you can work from this template by clicking `New Project` then `Upload Project`. Your answers will
go in the `pset.tex` file. You should put your name and UNI where indicated in the `.tex` file, as well as the names
and UNIs of your collaborators, if you had any. Per the [Syllabus]({{ site.baseurl }}{% link syllabus.md %}), you may
collaborate with up two other students. Although collaboration is encouraged, when it comes to writing up your submission,
*you must write up the solutions yourself, in your own words*, away from your group members. If any submission is found
in violation of this policy, that will be counted as an instance of academic misconduct.

If you're working with a group, make sure all group members' names and UNIs are indicated on the first page of your submitted PDF.
Each group member should make a separate submission.

In the Gradescope submission system, for each problem, you will need to "select pages" in the files you have uploaded that
contain your answer for that problem. (If there are multiple pages for a single problem, make sure to select them all!)
Some problems will have subparts; in that case, the Gradescope assignment will also have subparts, so please be sure to
assign the subparts properly. Failure to do properly select pages for a problem will result in a zero grade for that problem.

If you need further assistance, [Gradescope's help section is here.](https://help.gradescope.com/article/ccbpppziu9-student-submit-work#submitting_to_your_assignment).

## Programming Part
All programming assignments are done in Python, in the form of a Jupyter notebook. On Gradescope, there will be a `PS # Programming`
assignment, where you'll submit a single `.ipynb` file that is just modified from the `ps#.ipynb` supplied to you.

To start one of the programming assignments, download the Jupyter notebook file `ps#.ipynb`. 
There will be cells of the notebook that say `### YOUR CODE HERE ###`. You should write code in those cells and leave the other cells alone.

The same collaborator policy applies to the programming parts. If you are working in a group:

Under *Collaborator(s)* in the first text cell of the notebook, include the names and UNIs of your group members.

These programming assignments have all been tested using [Google Colab](https://colab.research.google.com/), our online
platform of choice for working with these Python notebooks. Because of that, it is recommended that you also use Colab 
to complete your homework, as each notebook has been test run to completion on Colab. That being said, it's not 
absolutely necessary, and if you're comfortable using your local machine or some other platform to work with these 
notebooks, that's also fine. Just be warned that it might be more difficult to debug dependencies on your machine, and 
you are responsible for making sure that the notebook operates just as it should if you did it all on Google Colab.

If you're working in Google Colab:
- Click "File" > "Upload notebook" and upload `ps#.ipynb`.
- To submit, make sure all cells were run and you have saved the assignment with all cells run. An easy way to do this is to click "Runtime" > "Restart and Run All." If everything runs without a hitch, you can save the notebook and export it with: "File" > "Download" > "Download .ipynb." Upload only the .ipynb file to Gradescope under `PS # Programming` and you are done!

The programming parts are relatively light and are mostly there to illustrate and reinforce the ideas from
class. Grading for these programming parts will be done by inspection of your `.ipynb` notebooks, so please make sure
that all the figures load and all the cells run in your notebook, the "Runtime" > "Restart and Run All" workflow before
submission should make sure of this.