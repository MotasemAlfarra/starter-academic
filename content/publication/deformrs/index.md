---
title: "DeformRS: Certifying Input Deformations with Randomized Smoothing"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Adel Bibi
- Naeemullah Khan
- Philip H. S. Torr 
- Bernard Ghanem

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2022-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *AAAI Conference on Artificial Intelligence [oral]*
publication_short: In *AAAI'22 [oral]*

abstract: Deep neural networks are vulnerable to input deformations in the form of vector fields of pixel displacements and to other parameterized geometric deformations e.g. translations, rotations, etc. Current input deformation certification methods either (i) do not scale to deep networks on large input datasets, or (ii) can only certify a specific class of deformations, e.g. only rotations. We reformulate certification in randomized smoothing setting for both general vector field and parameterized deformations and propose DeformRS-VF and DeformRS-Par, respectively. Our new formulation scales to large networks on large input datasets. For instance, DeformRS-Par certifies rich deformations, covering translations, rotations, scaling, affine deformations, and other visually aligned deformations such as ones parameterized by Discrete-Cosine-Transform basis. Extensive experiments on MNIST, CIFAR10 and ImageNet show that DeformRS-Par outperforms existing state-of-the-art in certified accuracy, e.g. improved certified accuracy of 6% against perturbed rotations in the set [-10,10] degrees on ImageNet.

# Summary. An optional shortened abstract.
summary: We extend randomized smoothing to certify image deformations such as rotation, translation, scaling, and affine.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: https://arxiv.org/pdf/2107.00996.pdf

url_pdf: https://arxiv.org/pdf/2107.00996.pdf
url_code: https://github.com/MotasemAlfarra/DeformRS
url_dataset: ''
url_poster: https://drive.google.com/file/d/1uRR4f_kcK8qj-jsT5da8N9vz1Dwoc3WN/view?usp=sharing
url_project: ''
url_slides: https://docs.google.com/presentation/d/13Lk_naMgchVoXE7oaQ6IQnn-Bx8fm9hZ/edit?usp=sharing&ouid=103008625988261101687&rtpof=true&sd=true
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


