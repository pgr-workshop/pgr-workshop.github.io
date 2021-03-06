---
layout: page
title: Perception as generative reasoning
subtitle: <b>Structure, Causality, Probability</b><br><br>NeurIPS 2019 workshop. Friday Dec. 13, Vancouver.
---

<!--Submit your questions for the speakers and the panel [HERE](https://docs.google.com/forms/d/e/1FAIpQLSfEWOlTyjzbbbOB7r0665ReqYsBjoPiYFFUnZetz6_mnjq09A/viewform?usp=sf_link)!
-->
Check out the videos of the workshop sessions in the [schedule](schedule) page, and all the [accepted papers](accepted_papers)!

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
Search, Amortised inference vs. online inference, stochasticity and gradients, etc.

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

<!--[Geoffrey Hinton](http://www.cs.toronto.edu/~hinton/) -  Emeritus Professor at the Computer Science Department, University of Toronto (Canada) as well as VP and Engineering Fellow at Google. 
[Fei-Fei Li](http://vision.stanford.edu/index.html) - Professor at the Computer Science Department at Stanford and Director of the Stanford AI Lab.
-->
[Sanja Fidler](https://www.cs.utoronto.ca/~fidler/) - Assistant Professor at the University of Toronto and Director of AI at NVIDIA (Canada). 

<!--[Jiajun Wu](https://jiajunwu.com/) - Ph.D. Student at the Department of Electrical Engineering & Computer Science, MIT (USA).-->
[Josh Tenenbaum](https://web.mit.edu/cocosci/josh.html) - Professor at the Department of Brain and Cognitive Sciences, MIT (USA).

[Tatiana Lopez-Guevara](http://zepolitat.co/) - PhD Student at Edinburgh Centre for Robotics (UK).

[Niloy Mitra](http://www0.cs.ucl.ac.uk/staff/n.mitra/) - Professor at the Department of Computer Science, University College London (UK). 

[Danilo J. Rezende](https://twitter.com/deepspiker) - Research Scientist, DeepMind (UK).

### Call for papers
**Submission deadline:** 13 September 2019  
**Author notification:** 1 October 2019

We invite authors to submit papers on topics related to the workshop via the [CMT portal](https://cmt3.research.microsoft.com/PGRSCP2019).
Papers should be in the latest [NeurIPS format](https://neurips.cc/Conferences/2019/PaperInformation/StyleFiles) with a maximum of 4 pages (excluding references and supplementary material). We ask authors to use the supplementary material only for minor details that do not fit in the main paper. The review process will be double blind so papers should be anonymised appropriately.


### Organising committee


<div style="float: left; width: 150px">
  <img src="https://github.com/pgr-workshop/pgr-workshop.github.io/blob/master/img/danro.png?raw=true" width="130px" href="https://danrsm.github.io/" alt="Dan Rosenbaum">
  <a href="https://danrsm.github.io/">Dan Rosenbaum</a>
  (DeepMind)
</div><div style="float: left; width: 150px">
  <img src="https://github.com/pgr-workshop/pgr-workshop.github.io/blob/master/img/marta2.png?raw=true" width="130px" href="https://www.martagarnelo.com" alt="Marta Garnelo">
  <a href="https://www.martagarnelo.com">Marta Garnelo</a>
  (DeepMind)
</div>
<div style="float: left; width: 150px">
  <img src="https://github.com/pgr-workshop/pgr-workshop.github.io/blob/master/img/Pete_headshot.jpg?raw=true" width="130px" alt="Peter Battaglie">
  Peter Battaglia
  (DeepMind)
</div><div style="float: left; width: 150px">
  <img src="https://github.com/pgr-workshop/pgr-workshop.github.io/blob/master/img/kelsey.png?raw=true" width="130px" href="https://web.mit.edu/krallen/www/" alt="Kelsey Allen">
  <a href="https://web.mit.edu/krallen/www/">Kelsey Allen </a>
  (MIT)
</div>
<div style="float: left; width: 150px">
  <img src="https://github.com/pgr-workshop/pgr-workshop.github.io/blob/master/img/ilker2.png?raw=true" width="130px" href="http://cncl.yale.edu/" alt="Ilker Yildirim">
  <a href="http://cncl.yale.edu/">Ilker Yildirim </a>
  (Yale)
</div>
<!--
| <img src="https://github.com/pgr-workshop/pgr-workshop.github.io/blob/master/img/danro.png?raw=true" width="130" href="https://danrsm.github.io/"> | <img src="https://github.com/pgr-workshop/pgr-workshop.github.io/blob/master/img/marta2.png?raw=true" width="130" href="https://www.martagarnelo.com"> |<img src="https://github.com/pgr-workshop/pgr-workshop.github.io/blob/master/img/peter.png?raw=true" width="130"> | <img src="https://github.com/pgr-workshop/pgr-workshop.github.io/blob/master/img/kelsey.png?raw=true" width="130" href="http://web.mit.edu/krallen/www/"> | <img src="https://github.com/pgr-workshop/pgr-workshop.github.io/blob/master/img/ilker2.png?raw=true" width="130" href="http://cncl.yale.edu/"> |
|:-----:|:-----:|:-----:|:------:|:-----:|
| <a href="https://danrsm.github.io/">Dan Rosenbaum</a> <br>(DeepMind)| <a href="https://www.martagarnelo.com">Marta Garnelo</a> <br>(DeepMind)| Peter Battaglia <br>(DeepMind) | <a href="https://cbmm.mit.edu/about/people/allen"> Kelsey Allen </a> <br>(MIT) | <a href="http://cncl.yale.edu/">Ilker Yildi/emeritus-professors-2/rim </a><br>(Yale)|
-->



