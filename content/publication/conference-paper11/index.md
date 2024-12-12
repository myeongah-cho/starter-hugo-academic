---
title: 'Towards Multi-Domain Learning for Generalizable Video Anomaly Detection'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Taeoh Kim
  - Minho Shim
  - Dongyoon Wee
  - Sangyoun Lee 

# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2024-12-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2023-06'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *The Thirty-Eighth Annual Conference on Neural Information Processing Systems*
publication_short: In *NeurIPS 2024*

abstract: Most of the existing Video Anomaly Detection (VAD) studies have been conducted within single-domain learning, where training and evaluation are performed on a single dataset. However, the criteria for abnormal events differ across VAD datasets, making it problematic to apply a single-domain model to other domains. In this paper, we propose a new task called Multi-Domain learning forVAD (MDVAD) to explore various real-world abnormal events using multiple datasets for a general model. MDVAD involves training on datasets from multiple domains simultaneously, and we experimentally observe that Abnormal Conflicts between domains hinder learning and generalization. The task aims to address two key objectives (i) better distinguishing between general normal and abnormal events across multiple domains, and (ii) being aware of ambiguous abnormal conflicts. This paper is the first to tackle abnormal conflict issue and introduces a new benchmark, baselines, and evaluation protocols for MDVAD. As baselines, we propose a framework with Null(Angular)-Multiple Instance Learning and an Abnormal Conflict classifier. Through experiments on a MDVAD benchmark composed of six VAD datasets and using four different evaluation protocols, we reveal abnormal conflicts and demonstrate that the proposed baseline effectively handles these conflicts, showing robustness and adaptability across multiple domains.

# Summary. An optional shortened abstract.
summary: ' '

tags:
  - Conferences

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: open access
  url: https://openreview.net/forum?id=ywEQkCmImh

url_pdf: 'https://openreview.net/pdf?id=ywEQkCmImh'
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
