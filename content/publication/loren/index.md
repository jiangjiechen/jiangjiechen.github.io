---
title: "LOREN: Logic-Regularized Reasoning for Interpretable Fact Verification"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Qiaoben Bao
- Changzhi Sun
- Xinbo Zhang
- Jiaze Chen
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
publishDate: "2022-01-01"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *The 36th AAAI Conference on Artificial Intelligence (**AAAI**)*, 2022 (oral)
# publication_short: AAAI 2022

abstract: Given a natural language statement, how to verify its veracity against a large-scale textual knowledge source like Wikipedia? Most existing neural models make predictions without giving clues about which part of a false claim goes wrong. In this paper, we propose LOREN, an approach for interpretable fact verification. We decompose the verification of the whole claim at phrase-level, where the veracity of the phrases serves as explanations and can be aggregated into the final verdict according to logical rules. The key insight of LOREN is to represent claim phrase veracity as three-valued latent variables, which are regularized by aggregation logical rules. The final claim verification is based on all latent variables. Thus, LOREN enjoys the additional benefit of interpretability -- it is easy to explain how it reaches certain results with claim phrase veracity. Experiments on a public fact verification benchmark show that LOREN is competitive against previous approaches while enjoying the merit of faithful and accurate interpretability. 

# Summary. An optional shortened abstract.
summary: Interpretable fact verification with phrasal decomposition and logic regularization.

tags: [Reasoning]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Code
#   url: 

url_pdf: 'https://arxiv.org/abs/2012.13577'
url_code: 'https://github.com/jiangjiechen/LOREN'
url_dataset: ''
url_poster: 'https://jiangjiechen.github.io/content/slides/loren/AAAI22-loren-poster.pdf'
url_project: 'https://huggingface.co/spaces/Jiangjie/loren-fact-checking'
url_slides: 'https://jiangjiechen.github.io/content/slides/loren/AAAI22-loren.pdf'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'LOREN not only makes the final verification but also finds the culprit phrase that causes the claim’s falsity.'
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
