---
title: 'Sample efficiency in RL'
date: 2026-02-25
permalink: /research/sampleefficiency/
catagories: [blog]
---


As part of the StatML CDT, during the first year we are tasked with completing a sequence of mini-projects aimed at providing an introduction to 
graduate-level research. For my first mini-project, I worked on comparing the sample efficiciency[^1] of model-based and model-free methods in 
offline Reinforcement Learning, building on the results from <a href="https://arxiv.org/pdf/2407.15007"> Foster et. al. (2024)<a>. We show formally
that model-based methods can be more sample efficient than model-free for certain classes of problems. Notably, our results hold in a general-purpose, function-approximation setting[^2] and hence
are more applicable to modern RL methods than those that are specified to the tabular case. 



[^1] This is essentially the number of samples needed to learn a sufficiently good policy.
[^2] Please read the paper for further details! 
