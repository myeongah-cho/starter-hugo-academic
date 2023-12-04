---
title: "SSAT: Self-Supervised Associating Network for Multiobject Tracking"
authors:
- Tae-Young Chung
- admin
- Heansung Lee
- Sangyoun Lee

date: "2022-06-01T00:00:00Z"
doi: "10.1109/TCSVT.2022.3186751"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-06-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Circuits and Systems for Video Technology <u>(IF: 5.86)</u>*"
publication_short: "*IEEE TCSVT <u>(IF: 5.86)</u>*"

abstract: Multi-object tracking (MOT), which is crucial for computer vision and video processing, has immense potential for improvement. Traditional tracking-by-detection approaches include feature-based object re-identification methods that use trained features, but these methods suffer from a lack of suitable training data. In training datasets used for MOT, every object in a video sequence must have its own location and ID. However, assigning IDs to each object in every sequence is considerably labor-intensive, and hence current MOT datasets are unsuitable for training re-identification networks. To resolve this issue, this paper proposes a novel self-supervised learning method using several short videos that contain no human-added labels, based on the idea that each video is a set of temporally corresponding image frames. We then describe how to improve tracking performance using a re-identification network trained in a self-supervised manner. In addition, ablation studies were conducted in order to define the optimal parameters, such as number of clips, data augmentation, and appropriate matching algorithms. The proposed approach achieved competitive performance compared with current best-practice methods including supervised methods, achieving MOT accuracy = 62.0% and ID F1-score = 62.7% on the MOT17 benchmark.

# Summary. An optional shortened abstract.
summary: ' '

tags:
- Journals
featured: false

links:
- name: open access
  url: https://ieeexplore.ieee.org/abstract/document/9808162
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
