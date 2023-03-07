---
title: "ReLAX"
summary: A Reinforcement Learning Agent for Explaining Arbitrary Predictive Models
date: "2022-10-17"

reading_time: false  # Show estimated reading time?
share: true  # Show social sharing links?
profile: false  # Show author profile?
comments: false  # Show comments?
math: true

# Optional header image (relative to `static/img/` folder).
header:
  caption: "ReLAX"
  image: "relax.png"
---

ReLAX is the first counterfactual explanation method for _any_ black-box machine learning model, based on reinforcement learning (RL). In a nutshell, it formulates the problem of generating **counterfactual examples** as a Markov Decision Process (MDP) with a discrete-continuous hybrid action space. This resembles the behavior of an RL agent that, given any input instance $\boldsymbol{x}$, produces its corresponding optimal counterfactual example $\tilde{\boldsymbol{x}}^*$ by repeatedly picking one of the features to change (i.e., a discrete action) and applying a slight perturbation to it (i.e., a continuous action).