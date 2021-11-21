---
title: "Rethinking Clustering for Robustness"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Juan C. Perez
- Adel Bibi
- Ali Thabet
- Pablo Arbeláez
- Bernard Ghanem

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2021-10-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-10-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *British Machine Vision Conference*
publication_short: In *BMVC'21*

abstract: This paper studies how encouraging semantically-aligned features during deep neural network training can increase network robustness. Recent works observed that  Adversarial Training leads to robust models, whose learnt features appear to correlate with human perception. Inspired by this connection from robustness to semantics, we study the complementary connection: from semantics to robustness. To do so, we provide a robustness certificate for distance-based classification models (clustering-based classifiers). Moreover, we show that this certificate is tight, and we leverage it to propose ClusTR (Clustering Training for Robustness), a clustering-based and adversary-free training framework to learn robust models. Interestingly, ClusTR outperforms adversarially-trained networks by up to 4\% under strong PGD attacks.

# Summary. An optional shortened abstract.
summary: We analyze the effect of encouraging the learnt features from DNN to be more semantically meaningful through clustering on the PGD-Robustness of the DNN.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: https://arxiv.org/pdf/2006.07682v2.pdf

url_pdf: https://arxiv.org/pdf/2006.07682v2.pdf
url_code: https://github.com/clustr-official-account/Rethinking-Clustering-for-Robustness
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Figure'
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

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
