---
title: "Preference learning of latent decision utilities with a human-like model of preferential choice"
collection: publications
category: conferences
permalink: /publication/2024-12-11-DePeuter-NeurIPS
excerpt: 'Better results in expert-in-the-loop tasks with an amortized cognitive model.'
date: 2024-12-16
venue: 'NeurIPS'
paperurl: 'https://proceedings.neurips.cc/paper_files/paper/2024/hash/df559d92fba6dc86dec1a2be59ebfce3-Abstract-Conference.html'
citation: 'Sebastiaan De Peuter, Shibei Zhu, Yujia Guo, Andrew Howes, Samuel Kaski (2024) &quot; Preference learning of latent decision utilities with a human-like model of preferential choice,&quot; in <i>Advances in Neural Information Processing Systems</i> 37:123608-123636. Curran Associates, Inc.'
---

Abstract: Preference learning methods make use of models of human
choice in order to infer the latent utilities that underlie human
behavior. However, accurate modeling of human choice behavior is
challenging due to a range of context effects that arise from how
humans contrast and evaluate options. Cognitive science has proposed
several models that capture these intricacies but, due to their
intractable nature, work on preference learning has, in practice, had
to rely on tractable but simplified variants of the well-known
Bradley-Terry model. In this paper, we take one state-of-the-art
intractable cognitive model and propose a tractable surrogate that is
suitable for deployment in preference learning. We then introduce a
mechanism for fitting the surrogate to human data and extend it to
account for data that cannot be explained by the original cognitive
model. We demonstrate on large-scale human data that this model
produces significantly better inferences on static and actively
elicited data than existing Bradley-Terry variants. We further show in
simulation that when using this model for preference learning, we can
significantly improve utility in a range of real-world tasks.
