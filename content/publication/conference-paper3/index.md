---
title: 'Occluded Person Re-Identification Via Relational Adaptive Feature Correction Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Minjung Kim
  - admin
  - Heansung Lee
  - Suhwan Cho
  - Sangyoun Lee

# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2022-05-01T00:00:00Z'
doi: '10.1109/ICASSP43922.2022.9746734'

# Schedule page publish date (NOT publication's date).
# publishDate: '2023-06'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Acoustics, Speech and Signal Processing*
publication_short: In *ICASSP 22*

abstract: Occluded person re-identification (Re-ID) in images captured by multiple cameras is challenging because the target person is occluded by pedestrians or objects, especially in crowded scenes. In addition to the processes performed during holistic person Re-ID, occluded person Re-ID involves the removal of obstacles and the detection of partially visible body parts. Most existing methods utilize the off-the-shelf pose or parsing networks as pseudo labels, which are prone to error. To address these issues, we propose a novel Occlusion Correction Network (OCNet) that corrects features through relational-weight learning and obtains diverse and representative features without using external networks. In addition, we present a simple concept of a center feature in order to provide an intuitive solution to pedestrian occlusion scenarios. Furthermore, we suggest the idea of Separation Loss (SL) for focusing on different parts between global features and part features. We conduct extensive experiments on five challenging benchmark datasets for occluded and holistic Re-ID tasks to demonstrate that our method achieves superior performance to state-of-the-art methods especially on occluded scene.

# Summary. An optional shortened abstract.
summary: ' '

tags:
  - Conferences

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: open access
  url: https://ieeexplore.ieee.org/document/9746734

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
