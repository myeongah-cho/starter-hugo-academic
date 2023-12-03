---
title: 'Look Around for Anomalies: Weakly-Supervised Anomaly Detection via Context-Motion Relational Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - '**MyeongAh Cho**'
  - Minjung Kim
  - Sangwon Hwang
  - Chaewon Park
  - Kyungjae Lee
  - Sangyoun Lee

# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2023-06-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2023-06'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IEEE / CVF Computer Vision and Pattern Recognition Conference*
publication_short: In *CVPR 23*

abstract: Weakly-supervised Video Anomaly Detection is the task of detecting frame-level anomalies using video-level labeled training data. It is difficult to explore class representative features using minimal supervision of weak labels with a single backbone branch. Furthermore, in real-world scenarios, the boundary between normal and abnormal is ambiguous and varies depending on the situation. For example, even for the same motion of running person, the abnormality varies depending on whether the surroundings are a playground or a roadway. Therefore, our aim is to extract discriminative features by widening the relative gap between classes' features from a single branch. In the proposed Class-Activate Feature Learning (CLAV), the features are extracted as per the weights that are implicitly activated depending on the class, and the gap is then enlarged through relative distance learning. Furthermore, as the relationship between context and motion is important in order to identify the anomalies in complex and diverse scenes, we propose a Context--Motion Interrelation Module (CoMo), which models the relationship between the appearance of the surroundings and motion, rather than utilizing only temporal dependencies or motion information. The proposed method shows SOTA performance on four benchmarks including large-scale real-world datasets, and we demonstrate the importance of relational information by analyzing the qualitative results and generalization ability.

# Summary. An optional shortened abstract.
summary: ' '

tags:
  - Conferences

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: open access
  url: https://openaccess.thecvf.com/content/CVPR2023/html/Cho_Look_Around_for_Anomalies_Weakly-Supervised_Anomaly_Detection_via_Context-Motion_Relational_CVPR_2023_paper.html

url_pdf: 'https://openaccess.thecvf.com/content/CVPR2023/papers/Cho_Look_Around_for_Anomalies_Weakly-Supervised_Anomaly_Detection_via_Context-Motion_Relational_CVPR_2023_paper.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=31ccYdwGDG8'

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
