---
title: "Parallel MCMC Without Embarrassing Failures"
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Daniel A. De Souza
  - Diego Mesquita
  - admin
  - Luigi Acerbi

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

show_date: false
date: "01 Jan 2022"
#doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "01 Jan 2023"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *ICML 2022*
publication_short: In *ICML 2022*

abstract: "Embarrassingly parallel Markov Chain Monte Carlo (MCMC) exploits parallel computing to scale Bayesian inference to large datasets by using a two-step approach. First, MCMC is run in parallel on (sub)posteriors defined on data partitions. Then, a server combines local results. While efficient, this framework is very sensitive to the quality of subposterior sampling. Common sampling problems such as missing modes or misrepresentation of low-density regions are amplified – instead of being corrected – in the combination phase, leading to catastrophic failures. In this work, we propose a novel combination strategy to mitigate this issue. Our strategy, Parallel Active Inference (PAI), leverages Gaussian Process (GP) surrogate modeling and active learning. After fitting GPs to subposteriors, PAI (i) shares information between GP surrogates to cover missing modes; and (ii) uses active sampling to individually refine subposterior approximations. We validate PAI in challenging benchmarks, including heavy-tailed and multi-modal posteriors and a real-world application to computational neuroscience. Empirical results show that PAI succeeds where previous methods catastrophically fail, with a small communication overhead."

# Summary. An optional shortened abstract.
#summary: "We propose a framework to compose iterative generative processes: GFlowNets and diffusion models."

tags:
- Distributed inference

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
url_pdf: 'https://proceedings.mlr.press/v151/de-souza22a/de-souza22a.pdf'
#url_code: 'https://github.com/timgaripov/compositional-sculpting'
#url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_poster: 'https://neurips.cc/media/PosterPDFs/NeurIPS%202023/70075.png?t=1701794689.2649195'
#url_project: ''
#url_slides: 'https://neurips.cc/media/neurips-2023/Slides/70075.pdf'
#url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_video: 'https://neurips.cc/virtual/2023/poster/70075'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

