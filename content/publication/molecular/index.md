---
title: "Towards Faster and More Compact Foundation Models for Molecular Property Prediction"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Yasir Ghunaim
- Andres Villa
- Gergo Ignacz
- Gyorgy Szekely
- admin
- Bernard Ghanem

# Author notes (optional)
author_notes: ''

date: "2025-07-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-07-07T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *CVPR Workshops*
publication_short: In *CVPRW*

abstract: Advancements in machine learning for molecular property prediction have improved accuracy but at the expense of higher computational cost and longer training times. Recently, the Joint Multi-domain Pre-training (JMP) foundation model has demonstrated strong performance across various downstream tasks with reduced training time over previous models. Despite JMP's advantages, finetuning it on molecular datasets ranging from small-scale to large-scale requires considerable time and computational resources. In this work, we investigate strategies to enhance efficiency by reducing model size while preserving performance. To better understand the model's efficiency, we analyze the layer contributions of JMP and find that later interaction blocks provide diminishing returns, suggesting an opportunity for model compression. We explore block reduction strategies by pruning the pre-trained model and evaluating its impact on efficiency and accuracy during fine-tuning. Our analysis reveals that removing two interaction blocks results in a minimal performance drop, reducing the model size by 32% while increasing inference throughput by 1.3 x. These results suggest that JMP-L is over-parameterized and that a smaller, more efficient variant can achieve comparable performance with lower computational cost. Our study provides insights for developing lighter, faster, and more scalable foundation models for molecular and materials discovery.

# Summary. An optional shortened abstract.
summary: We propose a compression scheme for Foundation models used in molecular property prediction.

tags: []

# Display this page in the Featured widget?
featured: False

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: https://opt-ml.org/papers/2020/paper_10.pdf

url_pdf: https://openaccess.thecvf.com/content/CVPR2025W/LXCV/papers/Ghunaim_Towards_Faster_and_More_Compact_Foundation_Models_for_Molecular_Property_CVPRW_2025_paper.pdf
url_code: github. com/Yasir-Ghunaim/efficient-jmp
url_dataset: ''
url_poster: ''
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


