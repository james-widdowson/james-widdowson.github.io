---
title: 'Sample efficiency in RL'
date: 2026-02-25
permalink: /research/sampleefficiency/
catagories: [blog]
---


As part of the StatML CDT, during the first year we are tasked with completing a sequence of mini-projects aimed at providing an introduction to 
graduate-level research. 
<!--more-->
For my first mini-project, I worked on comparing the sample efficiciency<sup>[1](#footnote1)</sup> of model-based and model-free methods in 
offline Reinforcement Learning, building on the results from <a href="https://arxiv.org/pdf/2407.15007"> Foster et. al. (2024)</a>. We show formally
that model-based methods can be more sample efficient than model-free for certain classes of problems. Notably, our results hold in a general-purpose, function-approximation setting<sup>[2](#footnote2)</sup> and hence
are more applicable to modern RL methods than those that are specified to the tabular case. The paper is linked below for those interested: happy reading!

<a href="/files/1st_miniproject.pdf">Model-free and model-based Reinforcement Learning in the offline setting</a>


<a name='footnote1'>1</a>: This is essentially the number of samples needed to learn a sufficiently good policy.

<a name='footnote2'>2</a>: Please read the paper for further details! 
