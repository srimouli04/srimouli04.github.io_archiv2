---
layout: single
classes : wide
author_profile: true
title: Bias and Variance Trade-off
toc: true
toc_label : Table of contents
toc_icon: "list"
canonical_url: "https://srimouli04.github.io/Bias_and_Variance_Trade-off"
excerpt: "The pros and cons of bias and variance trade off"
toc_sticky : false

header-includes: |
    \usepackage{tikz,pgfplots}
    \usepackage{fancyhdr}
    \pagestyle{fancy}
    \fancyhead[CO,CE]{This is fancy}
    \fancyfoot[CO,CE]{So is this}
    \fancyfoot[LE,RO]{\thepage}

---


It's critical to understand prediction mistakes whenever we talk about model prediction (bias and variance). The capacity of a model to minimise bias and variation is subject to a tradeoff. Gaining a good comprehension of these inaccuracies will assist us not just in developing correct models, but also in eliminating the errors of overfitting and underfitting.

## What exactly is bias? 

Bias is the discrepancy between our model's average prediction and the correct value that we are trying to predict. A model with a large bias overlooks the training examples and trivialises the model. It always results in a high level of inaccuracy on training and testing data.

## What exactly is variance?

The variability of model prediction for a specific data point or value tells us about the dispersion of our data. A model with a large variance aims to train data and does not adapt to data it has not seen before. As a result, though such models perform well on training data, they have significant error rates on test data.

Formally, the variance of a random variable X is defined as 

$$Var[X] = E[(X - E[X])^2] $$

an alternate expression for the variance:

$$
\begin{align*}
& E[(X - E[X])^2] \\
&= E[X^2 - 2E[X]X + E[X]^2] \\
&= E[X^2] - 2E[X]E[X] + E[X]^2 \\
&= E[X^2] - E[X]^2
\end{align*}
$$


## Mathematical View

Let's call the variable we're aiming to predict Y and the other variables X. We presume there is a correlation between the two in the sense that

$$ y = f(x) + e $$

$$\bar{y}(\mathbf{x}) = E_{y \vert \mathbf{x}} \left[Y\right] = \int\limits_y y \, \Pr(y \vert \mathbf{x}) \partial y.$$

Where e is the error term and it’s normally distributed with a mean of 0.
We will make a model $$\hat {f}(x)$$ of f(X) using linear regression or any other modeling technique.
So the expected squared error at a point x is

## References

1. [ Bias-Variance Tradeoff - Cornell university lecture notes](https://www.cs.cornell.edu/courses/cs4780/2018fa/lectures/lecturenote12.html)

2. [Understanding-the-bias-variance-tradeoff by Seema Singh](https://towardsdatascience.com/understanding-the-bias-variance-tradeoff-165e6942b229)

3. [Machine Learning-Bias And Variance In Depth Intuition](https://www.youtube.com/watch?v=BqzgUnrNhFM)

4. [CS228 class notes](https://ermongroup.github.io/cs228-notes/preliminaries/probabilityreview/)