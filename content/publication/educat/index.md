---
title: "Unsupervised Editing for Counterfactual Stories"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Chun Gan
- Sijie Cheng
- Hao Zhou
- Yanghua Xiao
- Lei Li

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2022-02-22"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-01-01"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *The 36th AAAI Conference on Artificial Intelligence (**AAAI**)*, 2022 (oral)
# publication_short: AAAI 2022

abstract: Creating what-if stories requires reasoning about prior statements and possible outcomes of the changed conditions. One can easily generate coherent endings under new conditions, but it would be challenging for current systems to do it with minimal changes to the original story. Therefore, one major challenge is the trade-off between generating a logical story and rewriting with minimal-edits. In this paper, we propose EDUCAT, an editing-based unsupervised approach for counterfactual story rewriting. EDUCAT includes a target position detection strategy based on estimating causal effects of the what-if conditions, which keeps the causal invariant parts of the story. EDUCAT then generates the stories under fluency, coherence and minimal-edits constraints. We also propose a new metric to alleviate the shortcomings of current automatic metrics and better evaluate the trade-off. We evaluate EDUCAT on a public counterfactual story rewriting benchmark. Experiments show that EDUCAT achieves the best trade-off over unsupervised SOTA methods according to both automatic and human evaluation. 

# Summary. An optional shortened abstract.
summary: Creating counterfactual story endings (what-if stories) with unsupervised editing.

tags: [Reasoning, Text Generation]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Code
#   url: 

url_pdf: 'https://arxiv.org/abs/2112.05417'
url_code: 'https://github.com/jiangjiechen/EDUCAT'
url_dataset: ''
url_poster: 'https://jiangjiechen.github.io/content/slides/educat/AAAI22-educat-poster.pdf'
url_project: ''
url_slides: 'https://jiangjiechen.github.io/content/slides/educat/AAAI22-educat.pdf'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Workflow of iterative editing for counterfactual stories.'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
