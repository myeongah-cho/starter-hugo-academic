---
title: "Unsupervised video anomaly detection via normalizing flows with implicit latent features"
authors:
- admin
- Taeoh Kim
- Woo Jin Kim
- Suhwan Cho
- Sangyoun Lee

date: "2022-04-01T00:00:00Z"
doi: "10.1016/j.patcog.2022.108703"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-04-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*ELSEVIER Pattern Recognition (<u>IF: 8.52</u>)*"
publication_short: "*ELSEVIER Pattern Recognition (<u>IF: 8.52</u>)*"

abstract: In contemporary society, surveillance anomaly detection, i.e., spotting anomalous events such as crimes or accidents in surveillance videos, is a critical task. As anomalies occur rarely, most training data consists of unlabeled videos without anomalous events, which makes the task challenging. Most existing methods use an autoencoder (AE) to learn to reconstruct normal videos; they then detect anomalies based on their failure to reconstruct the appearance of abnormal scenes. However, because anomalies are distinguished by appearance as well as motion, many previous approaches have explicitly separated appearance and motion informationfor example, using a pre-trained optical flow model. This explicit separation restricts reciprocal representation capabilities between two types of information. In contrast, we propose an implicit two-path AE (ITAE), a structure in which two encoders implicitly model appearance and motion features, along with a single decoder that combines them to learn normal video patterns. For the complex distribution of normal scenes, we suggest normal density estimation of ITAE features through normalizing flow (NF)-based generative models to learn the tractable likelihoods and identify anomalies using out-of-distribution detection. NF models intensify ITAE performance by learning normality through implicitly learned features. Finally, we demonstrate the effectiveness of ITAE and its feature distribution modeling on six benchmarks, including databases that contain various anomalies in real-world scenarios.

# Summary. An optional shortened abstract.
summary: ' '

tags:
- Journals
featured: true

links:
- name: open access
  url: https://www.sciencedirect.com/science/article/abs/pii/S0031320322001844
url_pdf: ''
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
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
