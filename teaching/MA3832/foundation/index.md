---
layout: post
title: Introduction
---

Intelligent agents are constantly generating, acquiring, and processing
data. This data could be in the form of *images* that we capture on our
phones, *text* messages we share with our friends, *graphs* that model
interactions on social media, *videos* that record important events,
etc. Natural agents excel at discovering patterns, extracting
knowledge, and performing complex reasoning based on the data they observe. How
can we build artificial learning systems to do the same?

Learning
--------

We will be primarily interested in parametric approximations to the data
distribution, which summarize all the information about the dataset $$\mathcal{D}$$ in
a finite set of parameters. In contrast with non-parametric models,
parametric models scale more efficiently with large datasets but are
limited in the family of distributions they can represent.

In the parametric setting, we can think of the task of learning a
generative model as picking the parameters within a family of model
distributions that minimizes some notion of distance[^1] between the
model distribution and the data distribution.
 
<img src="learning_1.png" alt="drawing" width="200" class="center"/>

## Footnotes

[^1]: As we shall see later, functions that do not satisfy all
    properties of a distance metric are also used in practice, e.g., KL
    divergence.

[^2]: Technically, a probabilistic discriminative model is also a
    generative model of the labels conditioned on the data. However, the
    usage of the term generative models is typically reserved for high
    dimensional data.
