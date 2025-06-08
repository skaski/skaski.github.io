---
title: "Compositional sculpting of iterative generative processes"
collection: publications
category: conferences
permalink: /publication/2023-12-15-Garipov-NeurIPS
excerpt: 'Opens doors to defining compositions of iterative generative processes and sampling from these compositions.'
date: 2023-12-16
venue: 'NeurIPS'
paperurl: 'https://proceedings.neurips.cc/paper_files/paper/2023/hash/29dd9e016b7b2f15ceb0ea93dbf1fa53-Abstract-Conference.html'
citation: 'Timur Garipov, Sebastiaan De Peuter, Ge Yang, Vikas Garg, Samuel Kaski, Tommi Jaakkola (2023) &quot;Compositional sculpting of iterative generative processes,&quot; in <i>Advances in Neural Information Processing Systems</i> 36:12665-12702. Curran Associates, Inc.'
---

Abstract: High training costs of generative models and the need to
fine-tune them for specific tasks have created a strong interest in
model reuse and composition.A key challenge in composing iterative
generative processes, such as GFlowNets and diffusion models, is that
to realize the desired target distribution, all steps of the
generative process need to be coordinated, and satisfy delicate
balance conditions.In this work, we propose Compositional Sculpting: a
general approach for defining compositions of iterative generative
processes. We then introduce a method for sampling from these
compositions built on classifier guidance.We showcase ways to
accomplish compositional sculpting in both GFlowNets and diffusion
models. We highlight two binary operations - the harmonic mean and the
constrast between pairs, and the generalization of these operations to
multiple component distributions.We offer empirical results on image
and molecular generation tasks. Project codebase:
https://github.com/timgaripov/compositional-sculpting.
