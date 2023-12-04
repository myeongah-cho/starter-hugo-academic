---
title: "Frame-to-frame visual odometry estimation network with error relaxation method"
authors:
- Sangwon Hwang
- admin
- Yuseok Ban
- Kyungjae Lee

date: "2022-10-01T00:00:00Z"
doi: "10.1109/ACCESS.2022.3214823"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-10-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Access __(IF: 3.48)__*"
publication_short: "*IEEE Access __(IF: 3.48)__*"

abstract: Estimating frame-to-frame (F2F) visual odometry with monocular images has significant problems of propagated accumulated drift. We propose a learning-based approach for F2F monocular visual odometry estimation with novel and simple methods that consider the coherence of camera trajectories without any post-processing. The proposed network consists of two stages- initial estimation and error relaxation. In the first stage, the network learns disparity images to extract features and predicts relative camera pose between adjacent two frames through the attention, rotation, and translation networks. Then, loss functions are proposed in the error relaxation stage to reduce the local drift, increasing consistency under dynamic driving scenes. Moreover, our skip-ordering scheme shows the effectiveness of dealing with sequential data. Experiments with the KITTI benchmark dataset show that our proposed network outperforms other approaches with higher and more stable performance.

# Summary. An optional shortened abstract.
summary: ' '

tags:
- Journals
featured: false

links:
- name: open access
  url: https://ieeexplore.ieee.org/abstract/document/9919836
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
