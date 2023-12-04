---
title: 'Look Around for Anomalies: Weakly-Supervised Anomaly Detection via Context-Motion Relational Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Tae-young Chung
  - Taeoh Kim
  - Sangyoun Lee

# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2019-06-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2023-06'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Biometrics*
publication_short: In *ICB 19*

abstract: NIR-to-VIS face recognition is identifying faces of two different domains by extracting domain-invariant features. However, this is a challenging problem due to the two different domain characteristics, and the lack of NIR face dataset. In order to reduce domain discrepancy while using the existing face recognition models, we propose a ’Relation Module’ which can simply add-on to any face recognition models. The local features extracted from face image contain information of each component of the face. Based on two different domain characteristics, to use the relationships between local features is more domain-invariant than to use it as it is. In addition to these relationships, positional information such as distance from lips to chin or eye to eye, also provides domain-invariant information. In our Relation Module, Relation Layer implicitly captures relationships, and Coordinates Layer models the positional information. Also, our proposed Triplet loss with conditional margin reduces intra-class variation in training, and resulting in additional performance improvements.Different from the general face recognition models, our add-on module does not need to pre-train with the large scale dataset. The proposed module fine-tuned only with CASIA NIR-VIS 2.0 database. With the proposed module, we achieve 14.81% rank-1 accuracy and 15.47% verification rate of 0.1% FAR improvements compare to two baseline models.

# Summary. An optional shortened abstract.
summary: ' '

tags:
  - Conferences

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: open access
  url: https://ieeexplore.ieee.org/abstract/document/8987306

url_pdf: 'https://arxiv.org/pdf/2208.02417.pdf'
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
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
