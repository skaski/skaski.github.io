---
title: "Tackling covariate shift with node-based Bayesian neural networks"
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Trung Q Trinh
  - Markus Heinonen
  - Luigi Acerbi
  - admin

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

show_date: false
date: "01 Jan 2022"
#doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "01 Jan 202s"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *ICML 2022*
publication_short: In *ICML 2022*

abstract: "Bayesian neural networks (BNNs) promise improved generalization under covariate shift by providing principled probabilistic representations of epistemic uncertainty. However, weight-based BNNs often struggle with high computational complexity of large-scale architectures and datasets. Node-based BNNs have recently been introduced as scalable alternatives, which induce epistemic uncertainty by multiplying each hidden node with latent random variables, while learning a point-estimate of the weights. In this paper, we interpret these latent noise variables as implicit representations of simple and domain-agnostic data perturbations during training, producing BNNs that perform well under covariate shift due to input corruptions. We observe that the diversity of the implicit corruptions depends on the entropy of the latent variables, and propose a straightforward approach to increase the entropy of these variables during training. We evaluate the method on out-of-distribution image classification benchmarks, and show improved uncertainty estimation of node-based BNNs under covariate shift due to input perturbations. As a side effect, the method also provides robustness against noisy training labels."

# Summary. An optional shortened abstract.
#summary: "We propose a framework to compose iterative generative processes: GFlowNets and diffusion models."

tags:
- Covariate shift
- Bayesian neural networks

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
url_pdf: 'https://proceedings.mlr.press/v162/trinh22a/trinh22a.pdf'
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

