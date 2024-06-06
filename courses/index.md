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

In this course, we will study generative models that view the world under the lens of probability.
In such a worldview, we can think of any kind of
observed data, say $$\mathcal{D}$$, as a finite set of samples from an
underlying distribution, say $$p_{\mathrm{data}}$$. At its very core, the
goal of any generative model is then to approximate this data
distribution given access to the dataset $$\mathcal{D}$$. The hope is that
if we are able to *learn* a good generative model, we can use the
learned model for downstream *inference*.
