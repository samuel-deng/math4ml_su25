---
layout: page
title: Project
description: This is the page for the course project.
---
# Paper Reading Project
{: .no_toc }

1. TOC
{:toc}

The project of this course will be to *attempt* to read a research paper in machine learning. Emphasis on *attempt*: there is no expectation that you will understand every single detail in the paper. However, you might be pleasantly surprised that you understand a bit more than you would’ve at the beginning of the course just by strengthening your mathematical foundations.

There are three parts to this project:

1. **Choose a paper.** *Within the first week.* Take a look at the list of research papers below and choose a paper based on the title and abstract. You're free to choose whatever might look interesting to you. If you need help deciding, feel free to email the instructor or TA or post on Ed.
2. **Beginning of course evaluation.** *Before the second week.* You will attempt to read the whole paper. Research papers can be intimidating if you’ve never read one before (and even if you’ve read hundreds!) so we will provide some guidance on how to read a scientific paper in machine learning. Then, you will provide a critical evaluation of the paper to the best of your current ability based on the template below. This will be graded on completion and effort -- we emphasize that it does *not* matter how much you actually know or understand from the paper, just that you put a concerted effort into completing the evaluation and grappling with the paper.
3. **End of course evaluation.** *Final week.* At the end of the course, you will read the paper again. You will fill out a similar critical evaluation of the paper, per the same template, with a couple added questions. Again, you will be graded not on your understanding (though we hope it's improved the second time around!) but, rather, your concerted effort in writing an evaluation that shows that you've read and grappled with the paper to the best of *your* ability.

This project will be graded on the clarity and quality of the evaluation, but we stress that we will not focus on how much you “get” the paper. As long as you do the work of grappling with the paper and filling out the evaluation to the best of *your* ability, regardless of your understanding, you should get full marks, grade-wise. The emphasis of this project is on your own growth — hopefully, you’ll find that by the end of the course your chosen paper isn’t quite as perplexing as it may have seemed in the beginning.

## Paper Reading Guidelines
Here are some tips that I've found helpful when reading papers to get you started. Reading papers in machine learning can be difficult, even
after you've read hundreds! It's a totally normal part of the process to be confused.

- *Read non-linearly.* Research papers aren't meant to be read linearly. Usually, I read papers in three passes. For the purposes of your assignment, you really only need to get to the depth of the second pass, but you're welcome to try to third pass the paper if you feel inspired.
  - First pass: In this pass, I read the abstract, the introduction, the problem setup, and the conclusion. I skim the rest, taking note of any important-looking diagrams or theorems but I don't get into the weeds of understanding them fully. This should take about 30-45 minutes. By the end of this step, I usually have an idea of the main problem of the paper, a faint idea of the solution, but none of the details in how they solve it.
  - Second pass: In this pass, I read over the paper fully, but I skip any proofs, just noting the main results of the paper as I go along. In this pass, I make sure I understand the statements of theorems and formal math in the paper, possibly by testing special cases and just thinking about the definitions, but I avoid scrutinizing the proofs. This should take 2-3 hours. By the end of this step, I can usually articulate what the main results are mathematically, maybe with some initial intuition, but I wouldn't be able to prove anything in the paper if you asked me to. Sometimes, stopping here is fine -- for many papers, it's just important that you know the main results as "black boxes" for your own research.
  - Third pass: In this pass, I read over the paper fully *again*, but now I scrutinize each line of the proofs. In this pass, I make sure I can essentially reprove the main results if I covered them up. This can be pretty time consuming -- it can take a couple days to a week to (for hard papers) even a month. By the end of this step, I should be able to *reproduce* the main results of the paper, or at least a simple version of the main results. 
- *Read with pen and paper in hand.* It's often helpful to write things out, write out missing steps, and draw diagrams. Always make sure you're able to annotate or write on scratch paper when reading a paper. It should be an active process, unlike, say, reading a novel.
- *Small examples and trivial cases.* Using that pen and paper, one thing I've found extremely helpful is to treat mathematical statements like finding bugs in a program -- test out simple inputs and edge cases to understand how theorems and lemmas work. Instantiating with the simplest nontrivial example for many statements allows you to get a more concrete grasp on the statement.
- *Black box results.* In many cases, you don't need to know *every single* detail behind the proof of a theorem or derivation of a result. In research, many theorems and results could be used as "black boxes." You only have limited time, so ask: will knowing the proof inside out for this result benefit me? Or is the important thing the statement itself?
- *Read with purpose.* It's a lot easier to read papers when you know exactly what you're looking for. Oftentimes, if you read a paper for a specific *reason* (say, you need a theorem for your own research or you want to implement a specific algorithm), you come at the paper with a lens that cuts out noise and saves you time. 
- *Use other resources.* No one says that you need to only rely on the text of the paper! Oftentimes, you can find talks from the authors of the paper or blog posts online that attempt to explain the content. Use these to your advantage -- hearing a good talk can often be illuminating, especially if the authors are good speakers.

Here's some more advice from folks much wiser than I am:
- Tim Roughgarden's [Reading in Algorithms Paper-reading Survival Kit](https://cs.stanford.edu/~rishig/courses/ref/paper-reading-technical.pdf)
- Srinivasan Keshav's [How to read a paper](http://ccr.sigcomm.org/online/files/p83-keshavA.pdf)

## List of Papers
- [A Probabilistic Interpretation of Canonical Correlation Analysis]({{ site.baseurl }}/project/Bach_Jordan.pdf) by Francis R. Bach and Michael I. Jordan.
- [Two models of double descent for weak features]({{ site.baseurl }}/project/Belkin_et_al.pdf) by Mikhail Belkin, Daniel Hsu, and Ji Xu
- [A Neural Probabilistic Language Model]({{ site.baseurl }}/project/Bengio_et_al.pdf) by Yoshua Bengio, Rejean Ducharme, Pascal Vincent, and Christian Jauvin
- [Latent Dirichlet Allocation]({{ site.baseurl }}/project/Blei_et_al.pdf) by David M. Blei, Andrew Y. Ng, and Michael I. Jordan
- [Combining Labeled and Unlabeled Data with Co-Training]({{ site.baseurl }}/project/Blum_Mitchell.pdf) by Avrim Blum and Tom Mitchell
- [Man is to Computer Programmer as Woman is to Homemaker? Debiasing Word Embeddings]({{ site.baseurl }}/project/Bolukbasi_et_al.pdf) by Tolga Bolukbasi, Kai-Wei Chang, James Zou, Venkatesh Saligrama, and Adam Kalai
- [Random Forests]({{ site.baseurl }}/project/Breiman.pdf) by Leo Breiman
- [Support-Vector Networks]({{ site.baseurl }}/project/Cortes_Vapnik.pdf) by Corinna Cortes and Vladimir Vapnik
- [Nearest Neighbor Pattern Classification]({{ site.baseurl }}/project/Cover_Hart.pdf) by Thomas M. Cover and Peter E. Hart
- [Indexing by Latent Semantic Analysis]({{ site.baseurl }}/project/Deerwester_et_al.pdf) by Scott Deerwester, Susan T. Dumais, and Richard Harshman
- [Experiments with a New Boosting Algorithm]({{ site.baseurl }}/project/Freund_Schapire.pdf) by Yoav Freund and Robert E. Schapire
- [Generative Adversarial Nets]({{ site.baseurl }}/project/Goodfellow_et_al.pdf) by Ian J. Goodfellow, Jean Pouget-Abadie, Mehdi Mirza, Bing Xu, David Warde-Farley, Sherjil Ozair, Aaron Courville, and Yoshua Bengio
- [Collaborative Filtering for Implicit Feedback Datasets]({{ site.baseurl }}/project/Hu_et_al.pdf) by Yifan Hu, Yehuda Koren, and Chris Volinsky
- [Adam: A Method for Stochastic Optimization]({{ site.baseurl }}/project/Kingma_Ba.pdf) by Diederik P. Kingma and Jimmy Lei Ba
- [Authoritative Sources in a Hyperlinked Environment]({{ site.baseurl }}/project/Kleinberg.pdf) by Jon M. Kleinberg
- [ImageNet Classiﬁcation with Deep Convolutional Neural Networks]({{ site.baseurl }}/project/Krizhevsky_et_al.pdf) by Alex Krizhevsky, Ilya Sutskever, and Geoffrey E. Hinton
- [Improving Language Understanding by Generative Pre-Training]({{ site.baseurl }}/project/Radford_et_al.pdf) by Alec Radford, Karthik Narasimhan, Tim Salimans, and Ilya Sutskever
- [EM Algorithms for PCA and SPCA]({{ site.baseurl }}/project/Roweis.pdf) by Sam Roweis
- [Learning representations by back-propagating errors]({{ site.baseurl }}/project/Rumelhart_et_al.pdf) by David E. Rumelhart, Geoffrey E. Hinton, and Ronald J. Williams
- [Regression Shrinkage and Selection via the Lasso]({{ site.baseurl }}/project/Tibshirani.pdf) by Robert Tibshirani
- [A Theory of the Learnable]({{ site.baseurl }}/project/Valiant.pdf) by Leslie G. Valiant
- [Distance Metric Learning for Large Margin Nearest Neighbor Classiﬁcation]({{ site.baseurl }}/project/Weinberger_Saul.pdf) by Kilian Q. Weinberger and Lawrence K. Saul

## First Evaluation Outline
For the first evaluation of the paper, submit a LaTeX document that follows these guidelines. The formatting is mostly
up to you; just make sure that the document is neat and your name and UNI are on the document somewhere.

**Length:** Your evaluation should be 1-2 pages in length total. If you go a bit over 2 pages, that's fine.

**Due:** This report is due Tuesday, June 3 11:59 PM ET on Gradescope. Late days may be used on this assignment.

In your document, answer each of the prompts below with a paragraph. 

**Prompt 1 (Problem Setup):** What problem is the paper trying to solve? Try to explain in plain English in your own words. What parts of the mathematical formalization of that problem are confusing to you? Which parts make sense? What real world problems might fall into this problem setup or model? Usually, papers have a "Model" or "Problem Setup" section that describes this. 

**Prompt 2 (Problem Solution):** How does this paper seem to solve this problem? Try to explain in plain English in your own words. What parts of the solution of the problem are confusing to you? What's a concept (if any) in the mathematics of the solution that you don't understand? Usually, papers will state their solutions in the form of a main algorithm or theorem. Look for the main result in the paper. Usually, papers have a "Main Theorem" subsection or "Algorithm" section as a signpost for this.

**Prompt 3 (One Tricky Statement):** Choose one mathematical statement, theorem, or display expression/equation (the mathematical expressions/equations that are on their own line) in the paper that you don't understand fully. Try to describe what each part of the expression you chose is to the best of your ability (each variable or object; use the best of your judgment for this). What do you think you would need to learn in order to understand this definition better?

**Prompt 4 (Simple Cases):** One way to understand a mathematical statement or theorem is to try simple cases. Think of this as debugging some code by trying out inputs to your program. Instantiate the variables in your statement/theorem with small numbers or easy to manipulate quantities (up to your discretion). Describe how you did this, and describe what the statement looks like with those special cases. Is there any part of it that this clarifies? What parts are still confusing or don't yield to this strategy?

**Prompt 5 (Reflection):**  What do you *think* you need to learn to understand this paper better? Also: why would you like to understand this paper better? It's good to have a motivation when reading papers because they're hard. Admittedly, though, due to the artificial nature of this exercise, just "I chose a random paper, didn't have time to change it, and now I'm stuck with it" is fine motivation.

**Prompt 6 (Your Own Ideas):** Research is iterative -- these papers are, in some sense, "classics" and accepted knowledge in the field, but at some point they were at the frontier of our knowledge. Can you brainstorm any way to push the frontier? Is there a problem in this setup they missed, an idea that this paper sparks for you, or an application domain you might apply these techniques and results to? It's okay if you can't be completely formal with this; no wrong ideas for this question.