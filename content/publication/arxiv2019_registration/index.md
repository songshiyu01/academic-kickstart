+++
title = "DeepICP: An End-to-End Deep Neural Network for 3D Point Cloud Registration"
date = "2019-05-10"
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
publication_types = ["4"]

# Publication name and optional abbreviated version.
publication = "In arXiv.org"
publication_short = "In **arXiv**"

# Abstract and optional shortened version.
abstract = "We present DeepICP - a novel end-to-end learning-based 3D point cloud registration framework that achieves comparable registration accuracy to prior state-of-the-art geometric methods. Different from other keypoint based methods where a RANSAC procedure is usually needed, we implement the use of various deep neural network structures to establish an end-to-end trainable network. Our keypoint detector is trained through this end-to-end structure and enables the system to avoid the inference of dynamic objects, leverages the help of sufficiently salient features on stationary objects, and as a result, achieves high robustness. Rather than searching the corresponding points among existing points, the key contribution is that we innovatively generate them based on learned matching probabilities among a group of candidates, which can boost the registration accuracy. Our loss function incorporates both the local similarity and the global geometric constraints to ensure all above network designs can converge towards the right direction. We comprehensively validate the effectiveness of our approach using both the KITTI dataset and the Apollo-SouthBay dataset. Results demonstrate that our method achieves comparable or better performance than the state-of-the-art geometry-based methods. Detailed ablation and visualization analysis are included to further illustrate the behavior and insights of our network. The low registration error and high robustness of our method makes it attractive for substantial applications relying on the point cloud registration task."
abstract_short = "We present DeepICP - a novel end-to-end learning-based 3D point cloud registration framework that achieves comparable registration accuracy to prior state-of-the-art geometric methods."

# Featured image thumbnail (optional)
#image_preview = "icra2018_localization.png"

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#projects = ["msf_localization"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "https://arxiv.org/pdf/1905.04153.pdf"
url_preprint = "https://arxiv.org/abs/1905.04153"
#url_code = ""
#url_dataset = ""
#url_project = ""
#url_slides = ""
#url_video = "https://www.youtube.com/watch?v=CEvcwRjDVOg"
#url_poster = ""
#url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++
