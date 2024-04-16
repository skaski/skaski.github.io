---
title: "Estimating treatment effects from single-arm trials via latent-variable modeling"
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Manuel Haussmann
  - Tran Minh Son Le
  - Viivi Halla-aho
  - Samu Kurki
  - Jussi Leinonen
  - Miika Koskinen
  - admin
  - Harri Lähdesmäki

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

show_date: false
date: "01 March 2024"
doi: '10.48550/arXiv.2311.03002'

# Schedule page publish date (NOT publication's date).
publishDate: "01 March 2024"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *AISTATS 2024*
publication_short: In *AISTATS 2024*

abstract: Randomized controlled trials (RCTs) are the accepted standard for treatment effect estimation but they can be infeasible due to ethical reasons and prohibitive costs. Single-arm trials, where all patients belong to the treatment group, can be a viable alternative but require access to an external control group. We propose an identifiable deep latent-variable model for this scenario that can also account for missing covariate observations by modeling their structured missingness patterns. Our method uses amortized variational inference to learn both group-specific and identifiable shared latent representations, which can subsequently be used for {\em (i)} patient matching if treatment outcomes are not available for the treatment group, or for {\em (ii)} direct treatment effect estimation assuming outcomes are available for both groups. We evaluate the model on a public benchmark as well as on a data set consisting of a published RCT study and real-world electronic health records. Compared to previous methods, our results show improved performance both for direct treatment effect estimation as well as for effect estimation via patient matching.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
 - name: "A new way to do controlled experiments in medicine: simulate the control"
   url: "https://fcai.fi/news/2024/4/11/a-new-way-to-do-controlled-experiments-in-medicine-simulate-the-control"
url_pdf: 'https://arxiv.org/pdf/2311.03002.pdf'
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_video: 'https://youtube.com'

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

