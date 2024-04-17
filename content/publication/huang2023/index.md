---
title: "Learning Robust Statistics for Simulation-based Inference under Model Misspecification"
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Daolang Huang
  - Ayush Bharti
  - Amauri Souza
  - Luigi Acerbi
  - admin

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

show_date: false
date: "13 Feb 2024"
#doi: '10.48550/arXiv.2311.03002'

# Schedule page publish date (NOT publication's date).
publishDate: "13 Feb 2024"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *NeurIPS 2023*
publication_short: In *NeurIPS 2023*

abstract: "Simulation-based inference (SBI) methods such as approximate Bayesian computation (ABC), synthetic likelihood, and neural posterior estimation (NPE) rely on simulating statistics to infer parameters of intractable likelihood models. However, such methods are known to yield untrustworthy and misleading inference outcomes under model misspecification, thus hindering their widespread applicability. In this work, we propose the first general approach to handle model misspecification that works across different classes of SBI methods. Leveraging the fact that the choice of statistics determines the degree of misspecification in SBI, we introduce a regularized loss function that penalizes those statistics that increase the mismatch between the data and the model. Taking NPE and ABC as use cases, we demonstrate the superior performance of our method on high-dimensional time-series models that are artificially misspecified. We also apply our method to real data from the field of radio propagation where the model is known to be misspecified. We show empirically that the method yields robust inference in misspecified scenarios, whilst still being accurate when the model is well-specified."

# Summary. An optional shortened abstract.
#summary: "We propose a framework to compose iterative generative processes: GFlowNets and diffusion models."

tags:
- Simulation-based inference
- Model misspecification

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
url_pdf: 'https://proceedings.neurips.cc/paper_files/paper/2023/file/16c5b4102a6b6eb061e502ce6736ad8a-Paper-Conference.pdf'
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

