---
title: "SimCS: Simulation for Domain Incremental Online Continual Segmentation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Zhipeng Cai
- Adel Bibi
- Bernard Ghanem
- Matthias Müller

# Author notes (optional)
author_notes: ''


date: "2023-12-04T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-12-04T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *AAAI Conference on Artificial Intelligence*
publication_short: In *AAAI'24*

abstract: Continual Learning is a step towards lifelong intelligence where models continuously learn from recently collected data without forgetting previous knowledge. Existing continual learning approaches mostly focus on image classification in the class-incremental setup with clear task boundaries and unlimited computational budget. This work explores Online Domain-Incremental Continual Segmentation~(ODICS), a real-world problem that arises in many applications, \eg, autonomous driving. In ODICS, the model is continually presented with batches of densely labeled images from different domains; computation is limited and no information about the task boundaries is available. In autonomous driving, this may correspond to the realistic scenario of training a segmentation model over time on a sequence of cities. We analyze several existing continual learning methods and show that they do not perform well in this setting despite working well in class-incremental segmentation. We propose SimCS, a parameter-free method complementary to existing ones that leverages simulated data as a continual learning regularizer. Extensive experiments show consistent improvements over different types of continual learning methods that use regularizers and even replay.

# Summary. An optional shortened abstract.
summary: We leverage simulated data to mitigate forgetting in domain incremental continual segmentation.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: https://arxiv.org/pdf/2107.00996.pdf

url_pdf: https://arxiv.org/pdf/2211.16234.pdf
url_code: ''
url_dataset: ''
url_poster: ''
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


