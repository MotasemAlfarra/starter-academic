---
title: "Gabor Layers Enhance Network Robustness"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Juan C. Perez
- Guillaume Jeanneret
- Adel Bibi
- Ali Thabet
- Bernard Ghanem
- Pablo Arbeláez

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"

date: "2020-08-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *European Conference in Computer Vision*
publication_short: In *ECCV'20*

abstract: We revisit the benefits of merging classical vision concepts with deep learning models. In particular, we explore the effect on robustness against adversarial attacks of replacing the first layers of various deep architectures with Gabor layers, i.e. convolutional layers with filters that are based on learnable Gabor parameters. We observe that architectures enhanced with Gabor layers gain a consistent boost in robustness over regular models and preserve high generalizing test performance, even though these layers come at a negligible increase in the number of parameters. We then exploit the closed form expression of Gabor filters to derive an expression for a Lipschitz constant of such filters, and harness this theoretical result to develop a regularizer we use during training to further enhance network robustness. We conduct extensive experiments with various architectures (LeNet, AlexNet, VGG16 and WideResNet) on several datasets (MNIST, SVHN, CIFAR10 and CIFAR100) and demonstrate large empirical robustness gains. Furthermore, we experimentally show how our regularizer provides consistent robustness improvements.

# Summary. An optional shortened abstract.
summary: We replace the first convolutional layer in deep neural networks with a Gabor layer to enhance networks robustness.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: https://arxiv.org/pdf/1912.05661.pdf

url_pdf: https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123540426.pdf
url_code: https://github.com/BCV-Uniandes/Gabor_Layers_for_Robustness
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: https://drive.google.com/file/d/14A5NSjmAv54UPBs0T8CcQcZ6QyKBoYZQ/view?usp=sharing
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


