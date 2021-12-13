---
layout: post
title: "Missing Link In Machine Learning : Representing Cause and Effect"
date: 2021-12-07
---

Being able to explain and trust the outcome of an AI driven business decision is a crucial aspect of the data science journey. The key to artifical intelligence is about having common sense reasoning abilities. Causal perspective is necessary as a further step in elevating machine intellligence to capture underlying relationships and incorporate recurrent feedback for robust inference as  it benefits  domain adaptation. We need to move away from association to causation as questions that motivate most business use-cases are causal in nature. Machine learning algorithms lean on the assumption of independent and identically distributed data, abbreviated as i.i.d that has its roots in statistical learning theory framework. 

This means that if i were to split my dataset into training and test then i am assuming the data distribution is not different and there are no dependencies.  It does not mean that random variables need to have same or similar probability. Statistical analysis is typified by regression, estimation and hypothesis techniques of a given distribution. We then infer association among variables and estimate the probabilities of past and future events. Causal analysis however goes a step further to examine and infer the probabilities under changing conditions, that is changes induced by treatments and external interventions. The core idea governing causality can be understood via the following terms : 

Change in X implies a change in Y, not vice-versa. It is directional NOT bi-directional

X → Y

factor X is referred to as the treatment 

factor Y is the outcome we are interested in

Lets suppose that D is binary treatment taking values of 0 or 1, then the average treatment effect is 

Di =

1 if unit i received the treatment
0 otherwise.

The fact that one can only observe Y = 0 or Y = 1 as potential outcomes in the real world makes establishing 

causality hard. 

Take for example there is a question in the marketing domain to understand if user generated contents 

cause product sales? Can we really say that with more positive reviews and ratings, customers opt for a 

purchase?

Not really. Imagine if there are other features unknown to a marketing campaign, such as unobserved 

product quality that may be pushing sales and reviews? 

 


The path to explainable and generalizable AI is meant to be at the level of functional understanding of the model rather than a low level algorithmic understanding of it. Causal 

reasoning is interpreted to have a stronger effect on human thinking than non-causal information. The human mind is trained to ask : 

1) why did the algorithm do that? 
2) can it trust the results generated from the model? 

 
