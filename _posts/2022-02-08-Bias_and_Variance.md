---
layout: single
classes : wide
author_profile: true
title: Bias and Variance Trade-off
toc: true
toc_label : Table of contents
toc_icon: "cog"
canonical_url: "https://srimouli04.github.io/Bias_and_Variance_Trade-off"
excerpt: "The pros and cons of bias and variance trade off"

---

# Bias and Variance Trade-off

It's critical to understand prediction mistakes whenever we talk about model prediction (bias and variance). The capacity of a model to minimise bias and variation is subject to a tradeoff. Gaining a good comprehension of these inaccuracies will assist us not just in developing correct models, but also in eliminating the errors of overfitting and underfitting.

<b>What exactly is bias?</b>
Bias is the discrepancy between our model's average prediction and the correct value that we are trying to predict. A model with a large bias overlooks the training examples and trivialises the model. It always results in a high level of inaccuracy on training and testing data.

<b>What exactly is variance?</b>
The variability of model prediction for a specific data point or value tells us about the dispersion of our data. A model with a large variance aims to train data and does not adapt to data it has not seen before. As a result, though such models perform well on training data, they have significant error rates on test data.

## Mathematically
Let's call the variable we're attempting to predict Y and the other variables X. We presume there is a connection between the two in the sense that

Y=f(X) + e

Where e is the error term and it’s normally distributed with a mean of 0.
We will make a model f^(X) of f(X) using linear regression or any other modeling technique.
So the expected squared error at a point x is