---
title: "Relational Deep Feature Learning for Heterogeneous Face Recognition"
authors:
- admin
- Taeoh Kim
- Ig-Jae Kim
- Kyungjae Lee
- Sangyoun Lee

date: "2021-07-01T00:00:00Z"
doi: "10.1109/TIFS.2020.3013186"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Information Forensics and Security (<u>IF: 7.18</u>)*"
publication_short: "*IEEE TIFS (<u>IF: 7.18</u>)*"

abstract: Heterogeneous Face Recognition (HFR) is a task that matches faces across two different domains such as visible light (VIS), near-infrared (NIR), or the sketch domain. Due to the lack of databases, HFR methods usually exploit the pre-trained features on a large-scale visual database that contain general facial information. However, these pre-trained features cause performance degradation due to the texture discrepancy with the visual domain. With this motivation, we propose a graph-structured module called Relational Graph Module (RGM) that extracts global relational information in addition to general facial features. Because each identity’s relational information between intra-facial parts is similar in any modality, the modeling relationship between features can help cross-domain matching. Through the RGM, relation propagation diminishes texture dependency without losing its advantages from the pre-trained features. Furthermore, the RGM captures global facial geometrics from locally correlated convolutional features to identify long-range relationships. In addition, we propose a Node Attention Unit (NAU) that performs node-wise recalibration to concentrate on the more informative nodes arising from relation-based propagation. Furthermore, we suggest a novel conditional-margin loss function ( C -softmax) for the efficient projection learning of the embedding vector in HFR. The proposed method outperforms other state-of-the-art methods on five HFR databases. Furthermore, we demonstrate performance improvement on three backbones because our module can be plugged into any pre-trained face recognition backbone to overcome the limitations of a small HFR database.

# Summary. An optional shortened abstract.
summary: ' '

tags:
- Journals
featured: true

links:
- name: open access
  url: https://ieeexplore.ieee.org/document/9153000
url_pdf: 'https://arxiv.org/pdf/2003.00697.pdf'
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
