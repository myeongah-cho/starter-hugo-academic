---
title: 'Saliency Detection via Global Context Enhanced Feature Fusion and Edge Weighted Loss'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Chaewon Park
  - Minhyeok Lee
  - admin
  - Sangyoun Lee

# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2022-10-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2023-06'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Image Processing*
publication_short: In *ICIP 22*

abstract: UNet-based methods have shown outstanding performance in salient object detection (SOD), but are problematic in two aspects. 1) Indiscriminately integrating the encoder feature, which contains spatial information for multiple objects, and the decoder feature, which contains global information of the salient object, is likely to convey unnecessary details of non-salient objects to the decoder, hindering saliency detection. 2) To deal with ambiguous object boundaries and generate accurate saliency maps, the model needs additional branches, such as edge reconstructions, which leads to increasing computational cost. To address the problems, we propose a context fusion decoder network (CFDN) and near edge weighted loss (NEWLoss) function. The CFDN creates an accurate saliency map by integrating global context information and thus suppressing the influence of the unnecessary spatial information. NEWLoss accelerates learning of obscure boundaries without additional modules by generating weight maps on object boundaries. Our method is evaluated on four benchmarks and achieves state-of-the-art performance. We prove the effectiveness of the proposed method through comparative experiments.

# Summary. An optional shortened abstract.
summary: ' '

tags:
  - Conferences

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: open access
  url: https://ieeexplore.ieee.org/document/9897797

url_pdf: 'https://arxiv.org/pdf/2110.06550.pdf'
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
