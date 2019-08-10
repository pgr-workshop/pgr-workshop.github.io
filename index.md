---
layout: page
title: Perception as generative reasoning:
structure, causality, probability
subtitle: NeurIPS 2019 workshop
---

### Overview
Many perception tasks can be cast as ‘inverse problems’ where the input signal is  the outcome of a causal process and 
perception is to invert that process. For example in visual object perception, the image is caused by an object and 
perception is to infer which object gave rise to that image. Following an analysis-by-synthesis approach, modeling the 
forward and causal direction of the data generation process is a natural way to capture the underlying scene structure, 
which typically leads to broader generalisation and better sample efficiency. Such a forward model can be applied to solve 
the inverse problem (inferring the scene structure from an input image) using Bayes rule, for example. This workflow stands
in contrast to common approaches in deep learning, where typically one first defines a task, and then optimises a deep 
model end-to-end to solve it. In this workshop we propose to revisit ideas from the generative approach and advocate for 
learning-based analysis-by-synthesis methods for perception and inference. In addition, we pose the question of how ideas
from these research areas can be combined with and complement modern deep learning practices.


The main questions we want to address in the workshop are:

1. What are the advantages and challenges of the generative approach? 
Modeling the forward and causal direction of the data vs. learning a task-specific predictor.

1. Generative reasoning: How can learned generative models be used for inference and perception? 
Search, Amortized inference vs. online inference, stochasticity and gradients, etc.

1. What are important ideas used in different (less learning-based) fields such as graphics, 
which are still missing from, and potentially useful for, modern learning methods for perception?

1. How can we incorporate different structural assumptions such as hierarchy and graph structure in
modern learning methods?


The main goal of this workshop is to bring together researchers from a wide range of research areas and 
to consider how traditional ideas can be used to improve current (deep) machine learning (ML) models. As such, 
the ideal outcomes of this workshop would be: a) to familiarise the newer generation of ML researchers with some 
of the earlier but extremely promising  research concepts that could be of relevance to their current projects and, 
crucially, to provide intuition for how these older ideas fit into newer frameworks. b) To start a conversation 
between researchers from a variety of areas which are all related in some way to structure and causality and to c) 
thereby inspire future ML approaches that ideally lead to new research directions and collaborations across research fields.


### Invited speakers

[Geoffrey Hinton](http://www.cs.toronto.edu/~hinton/) -  Professor at the Computer Science Department, University of Toronto (Canada) as well as VP and Engineering Fellow at Google. 

