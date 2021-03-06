+++
title = "Joint SFM and Detection Cues for Monocular 3D Localization in Road Scenes"
date = 2015-06-08
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Shiyu Song**", "Manmohan Chandraker"]

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
publication = "*IEEE International Conference on Computer Vision and Pattern Recognition (CVPR)*"
publication_short = "In **CVPR (Oral)**"

# Abstract and optional shortened version.
abstract = "We present a system for fast and highly accurate 3D localization of objects like cars in autonomous driving applications, using a single camera. Our localization framework jointly uses information from complementary modalities such as structure from motion (SFM) and object detection to achieve high localization accuracy in both near and far fields. This is in contrast to prior works that rely purely on detector outputs, or motion segmentation based on sparse feature tracks. Rather than completely commit to tracklets generated by a 2D tracker, we make novel use of raw detection scores to allow our 3D bounding boxes to adapt to better quality 3D cues. To extract SFM cues, we demonstrate the advantages of dense tracking over sparse mechanisms in autonomous driving scenarios. In contrast to complex scene understanding, our formulation for 3D localization is efficient and can be regarded as an extension of sparse bundle adjustment to incorporate object detection cues. Experiments on the KITTI dataset show the efficacy of our cues, as well as the accuracy and robustness of our 3D object localization relative to ground truth and prior works."
abstract_short = "A system for fast and highly accurate 3D localization of objects like cars in autonomous driving applications using a single camera."

# Is this a selected publication? (true/false)
featured = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = ["monocular_vo"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["List"]

# Links (optional).
url_pdf = "https://www.cv-foundation.org/openaccess/content_cvpr_2015/app/2B_043.pdf"
#url_preprint = "http://ieeexplore.ieee.org/document/7298997/"
#url_code = ""
#url_dataset = ""
#url_project = ""
#url_slides = ""
url_video = "https://www.youtube.com/watch?v=_uxX_DlJ0CI"
url_poster = "pdf/cvpr2015_object_poster.pdf"
#url_source = ""

doi = "10.1109/CVPR.2015.7298997"

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
