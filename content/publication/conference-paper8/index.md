---
title: 'Crvos: Clue Refining Network For Video Object Segmentation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Suhwan Cho
  - admin
  - Tae-young Chung
  - Heansung Lee
  - Sangyoun Lee

# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2020-10-01T00:00:00Z'
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
publication_short: In *ICIP 20*

abstract: The encoder-decoder based methods for semi-supervised video object segmentation (Semi-VOS) have received extensive attention due to their superior performances. However, most of them have complex intermediate networks which generate strong specifiers to be robust against challenging scenarios, and this is quite inefficient when dealing with relatively simple scenarios. To solve this problem, we propose a real-time network, Clue Refining Network for Video Object Segmentation (CRVOS), that does not have any intermediate network to efficiently deal with these scenarios. In this work, we propose a simple specifier, referred to as the Clue, which consists of the previous frame’s coarse mask and coordinates information. We also propose a novel refine module which shows the better performance compared with the general ones by using a deconvolution layer instead of a bilinear upsampling layer. Our proposed method shows the fastest speed among the existing methods with a competitive accuracy. On DAVIS 2016 validation set, our method achieves 63.5 fps and J&F score of 81.6%.

# Summary. An optional shortened abstract.
summary: ' '

tags:
  - Conferences

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: open access
  url: https://ieeexplore.ieee.org/abstract/document/9191143

url_pdf: 'https://arxiv.org/pdf/2002.03651.pdf'
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
