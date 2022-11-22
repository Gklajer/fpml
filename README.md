# Fundamental Principles of Machine Learning

Gitlab for the course Fundamental Principles of Machine Learning (FPML or TC0) in the CS Masters (M1 year), in the track *Artificial Intelligence* of the Paris Saclay University

The e-campus address is (for the quizz):

https://ecampus.paris-saclay.fr/course/view.php?id=92339#section-7

# IMPORTANT: PRE-REQUISITES !

**PRE1 and PRE2 as prerequisites, and PRE4 is strongly recommended**. Note that **PRE1 and PRE2 are mandatory, i.e. you must attend them to be allowed to follow TC0/FPML**, except if you can argue that you are already very fluent in statistics (PRE1) and linear algebra (PRE2) (in that case, e-mail me).
**This class** (or an equivalent) **is a prerequisite for almost all other [AI] classes**.

# Catch up for Nov 11th missed class

- To catch up on Friday 11th nov, we can try to find a date that suits everyone, here: https://www.when2meet.com/?17729512-WxKDI


# What we did in class

## session 1 - GD+Linear Regression (+organizational stuff)

During the first session, we did (i give the paths to files from the gitlab):

- read together "the rules": 0-organization-rules-intro/0-organization-rules.pdf
- The main Lecture material was: 1-Regressions: lecture1-ML-vocab+LinReg.pdf (we reached page 10, pages 11 and 12 are addressed in the tutorial, so it's ok, the rest will be seen later)
- Still lecture material: 1-GradientDescent/Gradient Descent-demo-compute2gradients.ipynb  : I explained in detail GD and its pitfalls, in particular in 1D. We did not compute the 2D case but ou can do it at home.

In tutorial, we did (may depend slightly on the group you are in):

- 1-Regressions: TD-Regressions.pdf -> we did the 1.1.1, 1.1.2, maybe the 1.1.3 (it's not very different from those before if you understand how to vectorize everything),
- in terms of notebooks, you filled the TP1.1-LinearRegression-GradientDescent.ipynb (either skipping the naive version and going directly for trick of the ones, or not), some people did also the TP1.2-LinReg-d-dimensional.ipynb (which is very similar to TP1.1)

A few students did also attack the TP1.3-LinReg-3rd-order-Polynomial.ipynb

## session 2 -

Lecture: we covered 2-Perceptron.pdf until page 16 included.

Tutorial:
- we covered pen-and-paer exercise 2.1.1, Perceptron – classics (from TD-Classifications-subject.pdf).
- we coded a good piece of what is asked in TP2.1-Perceptron.ipynb, i.e. up to 2.1 for everyone, and a number of people also so that "it works" on MNIST, i.e completed the part "2.2 Testing on more realistic data: MNIST (restricted to 2 classes)". One needs to encode the y's in {-1,+1}. Note that the dataset is a bit too small and here we did not split in train/test/validation, we can overfit.

We did not touch TP2.2-MultiClass-Classification.ipynb

## Corrections to session 2 (and before) are online !!

## session 3 - tentative plan

tentative plan:

Lecture: overfitting + regularizations

Tutorial:
- Exercices 3.1 to, 3.3, i.e., explicitly: 3.1.a, 3.1.b, 3.2, then 3.3.a, 3.3.b (all this is pen and paper)
- Then question 3.3.c is actually a pointer to 3.3.c-TP-toy example Lasso.ipynb
