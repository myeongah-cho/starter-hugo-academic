---
title: 'A Heterogeneous Face Recognition Via Part Adaptive And Relation Attention Module'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Rushuang Xu
  - admin
  - Sangyoun Lee

# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2021-09-01T00:00:00Z'
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
publication_short: In *ICIP 21*

abstract: In the face recognition application scenario, we need to process facial images captured in various conditions, such as at night by near-infrared (NIR) surveillance cameras. The illumination difference between NIR and visible-light (VIS) images causes a domain gap, and the variations in pose and emotion also make facial matching more difficult. Since heterogeneous face recognition (HFR) has difficulties in domain discrepancy, many studies have focused on extracting domain-invariant features, such as facial part relational information. However, when pose variation occurs, the facial component position changes and a different part relation is extracted. In this paper, we propose a part relation attention module that crops facial parts obtained through a semantic mask and performs relational modeling using each of these representative features. Furthermore, we suggest component adaptive triplet loss using adaptive weights for each part to reduce the intra-class distance regardless of the domain as well as pose. Finally, our method exhibits a performance improvement in the CASIA NIR-VIS 2.0 [1] and achieves superior results in the BUAA-VisNir [2] with large pose and emotion variations.

# Summary. An optional shortened abstract.
summary: ' '

tags:
  - Conferences

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: open access
  url: https://ieeexplore.ieee.org/document/9506682

url_pdf: 'https://arxiv.org/pdf/2102.00689.pdf'
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
