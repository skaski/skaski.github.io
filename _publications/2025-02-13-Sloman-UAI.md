---
title: "Proxy-informed Bayesian transfer learning with unknown sources"
collection: publications
category: conferences
permalink: /publication/2025-02-13-Sloman-UAI
excerpt: 'Opens doors towards coping with negative transfer.'
date: 2025-02-13
venue: 'UAI'
paperurl: 'https://arxiv.org/abs/2411.03263'
citation: 'Sabina J. Sloman, Julien Martinelli, Samuel Kaski (2025) &quot;Proxy-informed Bayesian transfer learning with unknown sources,&quot; in <i>Proc. UAI 2025,</i> accepted for publication.'
---

Abstract: Generalization outside the scope of one's training data
requires leveraging prior knowledge about the effects that transfer,
and the effects that don't, between different data sources. Transfer
learning is a framework for specifying and refining this knowledge
about sets of source (training) and target (prediction) data. A
challenging open problem is addressing the empirical phenomenon of
negative transfer, whereby the transfer learner performs worse on the
target data after taking the source data into account than before. We
first introduce a Bayesian perspective on negative transfer, and then
a method to address it. The key insight from our formulation is that
negative transfer can stem from misspecified prior information about
non-transferable causes of the source data. Our proposed method,
proxy-informed robust method for probabilistic transfer learning
(PROMPT), does not require prior knowledge of the source data (the
data sources may be "unknown"). PROMPT is thus applicable when
differences between tasks are unobserved, such as in the presence of
latent confounders. Moreover, the learner need not have access to
observations in the target task (cannot "fine-tune"), and instead
makes use of proxy (indirect) information. Our theoretical results
show that the threat of negative transfer does not depend on the
informativeness of the proxy information, highlighting the usefulness
of PROMPT in cases where only noisy indirect information, such as
human feedback, is available.
