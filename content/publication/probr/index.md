---
title: "Probabilistic Graph Reasoning for Natural Proof Generation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Changzhi Sun
- Xinbo Zhang
- admin
- Chun Gan
- Yuanbin Wu
- Jiaze Chen
- Hao Zhou
- Lei Li

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2021-07-30"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-08-30"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *The 59th Annual Meeting of the Association for Computational Linguistics (**ACL**) - Findings*, 2021
# publication_short: Findings of ACL 2021

abstract: In this paper, we investigate the problem of reasoning over natural language statements. Prior neural based approaches do not explicitly consider the inter-dependency among answers and their proofs. In this paper, we propose PROBR, a novel approach for joint answer prediction and proof generation. PROBR defines a joint probabilistic distribution over all possible proof graphs and answers via an induced graphical model. We then optimize the model using variational approximation on top of neural textual representation. Experiments on multiple datasets under diverse settings(fully supervised, few-shot and zero-shot evaluation) verify the effectiveness of PROBR, e.g., achieving 10%-30% improvement on QA accuracy in few/zero-shot evaluation. 

# Summary. An optional shortened abstract.
summary: A novel approach for joint answer prediction and proof generation.

tags: [Reasoning]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Code
#   url: 

url_pdf: 'https://aclanthology.org/2021.findings-acl.277.pdf'
url_code: 'https://github.com/changzhisun/PRobr'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://jiangjiechen.github.io/content/slides/probr/ACL21-findings-probr.pdf'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'An example of reasoning over natural language statements.'
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
