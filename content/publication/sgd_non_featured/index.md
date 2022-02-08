---
title: "Adaptive Learning of the Optimal Batch Size of SGD"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Slavomir Hanzely
- Alyazeed Albasyoni
- Bernard Ghanem
- Peter Richtarik

# Author notes (optional)
author_notes: ''

date: "2020-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Workshop on Optimization for Machine Learning*
publication_short: In *NeurIPSW'20*

abstract: Recent advances in the theoretical understanding of SGD led to a formula for the optimal batch size  minimizing the number of effective data passes, i.e., the number of iterations times the   batch size. However, this formula is of no practical value as it depends on the knowledge of the variance of the stochastic gradients evaluated at the optimum.  In this paper we design a practical SGD method capable of learning the optimal   batch size adaptively throughout its iterations for strongly convex and smooth functions. Our method does this provably, and in our experiments with synthetic and real data robustly exhibits nearly optimal behaviour; that is, it works as if the optimal  batch size was known a-priori. Further,  we generalize our method to several new  batch strategies not considered in the literature before, including a sampling suitable for distributed implementations.

# Summary. An optional shortened abstract.
summary: We desaign an algorithm that adaptively adjusts the batch size for SGD.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: https://opt-ml.org/papers/2020/paper_10.pdf

url_pdf: https://opt-ml.org/papers/2020/paper_10.pdf
url_code: ''
url_dataset: ''
url_poster: https://drive.google.com/file/d/1p_6yeQ3oMVZ1J0J8G5jdd1HfxtVBFkre/view?usp=sharing
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
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


