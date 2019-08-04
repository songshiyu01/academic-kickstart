+++
title = "DeepVCP: An End-to-End Deep Neural Network for Point Cloud Registration"
date = 2019-06-16T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Weixin Lu", "Guowei Wan", "Yao Zhou", "Xiangyu Fu", "Pengfei Yuan", "**Shiyu Song**"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "*International Conference on Computer Vision (ICCV)*"
publication_short = "In **ICCV**"

# Abstract and optional shortened version.
abstract = "We present DeepVCP - a novel end-to-end learning-based 3D point cloud registration framework that achieves comparable registration accuracy to prior state-of-the-art geometric methods. Different from other keypoint based methods where a RANSAC procedure is usually needed, we implement the use of various deep neural network structures to establish an end-to-end trainable network. Our keypoint detector is trained through this end-to-end structure and enables the system to avoid the inference of dynamic objects, leverages the help of sufficiently salient features on stationary objects, and as a result, achieves high robustness. Rather than searching the corresponding points among existing points, the key contribution is that we innovatively generate them based on learned matching probabilities among a group of candidates, which can boost the registration accuracy. Our loss function incorporates both the local similarity and the global geometric constraints to ensure all above network designs can converge towards the right direction. We comprehensively validate the effectiveness of our approach using the KITTI, the Apollo-SouthBay and the 3DMatch dataset. Results demonstrate that our method achieves comparable or better performance than the state-of-the-art geometry-based methods. Detailed ablation and visualization analysis are included to further illustrate the behavior and insights of our network. The low registration error and high robustness of our method makes it attractive for substantial applications relying on the point cloud registration task."
abstract_short = "We present DeepVCP - a novel end-to-end learning-based 3D point cloud registration framework that achieves comparable registration accuracy to prior state-of-the-art geometric methods."

# Is this a featured publication? (true/false)
featured = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
#url_pdf = "pdf/L3Net_W.Lu_Y.Zhou_S.Song_CVPR2019.pdf"
#url_supplementary = "pdf/L3Net_W.Lu_Y.Zhou_S.Song_CVPR2019_supplementary.pdf"
#url_preprint = ""
#url_code = ""
#url_dataset = "http://data.apollo.auto"
#url_project = ""
#url_slides = ""
#url_video = "https://youtu.be/dptbd4D78Mk"
#url_poster = ""
#url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
#doi = "10.1109/ICRA.2018.8461224"

# Does this page contain LaTeX math? (true/false)
math = false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++

