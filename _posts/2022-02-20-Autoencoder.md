---
layout: single
classes : wide
author_profile: true
title: Auto encoder
toc: False
toc_label : Table of contents
toc_icon: "list"
canonical_url: "https://srimouli04.github.io/autoencoder"
excerpt: "Vanilla Auto encoder"
toc_sticky : false

header-includes: |
    \usepackage{tikz,pgfplots}
    \usepackage{fancyhdr}
    \pagestyle{fancy}
    \fancyhead[CO,CE]{This is fancy}
    \fancyfoot[CO,CE]{So is this}
    \fancyfoot[LE,RO]{\thepage}

---

An autoencoder simulates the given training data's density function to reconstruct the input. An autoencoder consists of an encoder that maps the data \(x\) to the latent space \(z\), and a decoder that maps a sample from \(z\) to reconstruct the output \^{x}. It is a feed-forward network with back-propagation used to reduce the L2 loss between the output and input.

The latent space z must have a lower dimensional feature representation than the input space \(x\) in order for \(z\) to be pushed to capture significant causes of variation in the data via training. The autoencoder may be used to seed a supervised learning model with superior features learnt from the encoder. It is used to reduce dimensionality by learning a reduced dimensional representation of the latent variable \(z\). The density function of the latent space \(z\) is not provided by the autoencoder. We can use an autoencoder to reconstruct, but we cannot sample from the latent distribution to generate fresh samples.