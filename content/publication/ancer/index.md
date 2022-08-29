---
title: "ANCER: Anisotropic Certification via Sample-wise Volume Maximization"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Francisco Eiras
- M. Pawan Kumar
- Philip H. S. Torr
- Puneet K. Dokania
- Bernard Ghanem
- Adel Bibi

# Author notes (optional)
author_notes: 
- "Equal contribution"
- "Equal contribution"

date: "2022-08-28T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-08-28T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Transactions on Machine Learning Research*
publication_short: In *TMLR*

abstract: Randomized smoothing has recently emerged as an effective tool that enables certification of deep neural network classifiers at scale. All prior art on randomized smoothing has focused on isotropic ℓp certification, which has the advantage of yielding certificates that can be easily compared among isotropic methods via ℓp-norm radius. However, isotropic certification limits the region that can be certified around an input to worst-case adversaries, i.e., it cannot reason about other "close", potentially large, constant prediction safe regions. To alleviate this issue, (i) we theoretically extend the isotropic randomized smoothing ℓ1 and ℓ2 certificates to their generalized anisotropic counterparts following a simplified analysis. Moreover, (ii) we propose evaluation metrics allowing for the comparison of general certificates - a certificate is superior to another if it certifies a superset region - with the quantification of each certificate through the volume of the certified region. We introduce ANCER, a practical framework for obtaining anisotropic certificates for a given test set sample via volume maximization. Our empirical results demonstrate that ANCER achieves state-of-the-art ℓ1 and ℓ2 certified accuracy on both CIFAR-10 and ImageNet at multiple radii, while certifying substantially larger regions in terms of volume, thus highlighting the benefits of moving away from isotropic analysis. 

# Summary. An optional shortened abstract.
summary: We extend randomized smoothing to anisotropic distributions and optimize the anisotropic smoothing parameters per input point in randomized smoothing.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: https://arxiv.org/pdf/2107.00996.pdf

url_pdf: https://arxiv.org/pdf/2107.04570.pdf
url_code: https://github.com/MotasemAlfarra/ANCER
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


