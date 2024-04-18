---
title: "Noise-Aware Statistical Inference with Differentially Private Synthetic Data"
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Ossi Räisä
  - Joonas Jälkö
  - admin
  - Antti Honkela

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

show_date: false
date: "20 Aug 2023"
#doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "20 Aug 2023"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *AISTATS 2023*
publication_short: ''

abstract: "While generation of synthetic data under differential privacy (DP) has received a lot of attention in the data privacy community, analysis of synthetic data has received much less. Existing work has shown that simply analysing DP synthetic data as if it were real does not produce valid inferences of population-level quantities. For example, confidence intervals become too narrow, which we demonstrate with a simple experiment. We tackle this problem by combining synthetic data analysis techniques from the field of multiple imputation (MI), and synthetic data generation using noise-aware (NA) Bayesian modeling into a pipeline NA+MI that allows computing accurate uncertainty estimates for population-level quantities from DP synthetic data. To implement NA+MI for discrete data generation using the values of marginal queries, we develop a novel noise-aware synthetic data generation algorithm NAPSU-MQ using the principle of maximum entropy. Our experiments demonstrate that the pipeline is able to produce accurate confidence intervals from DP synthetic data. The intervals become wider with tighter privacy to accurately capture the additional uncertainty stemming from DP noise."

# Summary. An optional shortened abstract.
#summary: "We propose a framework to compose iterative generative processes: GFlowNets and diffusion models."

tags:
- Privacy-preserving learning

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
url_pdf: 'https://proceedings.mlr.press/v206/raisa23a/raisa23a.pdf'
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

