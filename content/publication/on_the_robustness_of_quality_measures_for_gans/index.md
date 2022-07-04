---
title: "On the Robustness of Quality Measures for GANs"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Juan C. Pérez
- Anna Frühstück
- Philip H. S. Torr 
- Peter Wonka
- Bernard Ghanem

# Author notes (optional)
author_notes:
- ''

date: "2022-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *European Conference in Computer Vision*
publication_short: In *ECCV'22*

abstract: This work evaluates the robustness of quality measures of generative models such as Inception Score (IS) and Fréchet Inception Distance (FID). Analogous to the vulnerability of deep models against a variety of adversarial attacks, we show that such metrics can also be manipulated by additive pixel perturbations.Our experiments indicate that one can generate a distribution of images with very high scores but low perceptual quality.Conversely, one can optimize for small imperceptible perturbations that, when added to real world images, deteriorate their scores.Furthermore, we extend our evaluation to generative models themselves, including the state of the art network StyleGANv2.We show the vulnerability of both the generative model and the FID against additive perturbations in the latent space.Finally, we show that the FID can be robustified by directly replacing the Inception model by a robustly trained Inception. We validate the effectiveness of the robustified metric through extensive experiments, which show that it is more robust against manipulation.

# Summary. An optional shortened abstract.
summary: We assess the adversarial robustness of Inception Score and Frechet Inception Distance (FID) and propose a robustified version of FID.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: https://arxiv.org/pdf/2107.00996.pdf

url_pdf: https://arxiv.org/pdf/2201.13019.pdf
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


