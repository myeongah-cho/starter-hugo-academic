---
title: Look Around for Anomalies Weakly-Supervised Anomaly Detection via Context-Motion Relational Learning

summary: MyeongAh Cho, Minjung Kim, Sangwon Hwang, Chaewon Park, Kyungjae Lee, Sangyoun Lee

date: '2023-06'

tags:
  - Conference
location: IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR 23)
address:
  city: Vancouver
  country: Canada
# Optional external URL for project (replaces project detail page).
external_link: https://openaccess.thecvf.com/content/CVPR2023/html/Cho_Look_Around_for_Anomalies_Weakly-Supervised_Anomaly_Detection_via_Context-Motion_Relational_CVPR_2023_paper.html

image:
  caption: 
  focal_point: Smart

url_code: ''
url_pdf: 'https://openaccess.thecvf.com/content/CVPR2023/papers/Cho_Look_Around_for_Anomalies_Weakly-Supervised_Anomaly_Detection_via_Context-Motion_Relational_CVPR_2023_paper.pdf'
url_slides: ''
url_video: 'https://www.youtube.com/watch?v=31ccYdwGDG8'
---
**Abstract**
  Weakly-supervised Video Anomaly Detection is the task of detecting frame-level anomalies using video-level labeled training data. It is difficult to explore class representative features using minimal supervision of weak labels with a single backbone branch. Furthermore, in real-world scenarios, the boundary between normal and abnormal is ambiguous and varies depending on the situation. For example, even for the same motion of running person, the abnormality varies depending on whether the surroundings are a playground or a roadway. Therefore, our aim is to extract discriminative features by widening the relative gap between classes' features from a single branch. In the proposed Class-Activate Feature Learning (CLAV), the features are extracted as per the weights that are implicitly activated depending on the class, and the gap is then enlarged through relative distance learning. Furthermore, as the relationship between context and motion is important in order to identify the anomalies in complex and diverse scenes, we propose a Context--Motion Interrelation Module (CoMo), which models the relationship between the appearance of the surroundings and motion, rather than utilizing only temporal dependencies or motion information. The proposed method shows SOTA performance on four benchmarks including large-scale real-world datasets, and we demonstrate the importance of relational information by analyzing the qualitative results and generalization ability.
