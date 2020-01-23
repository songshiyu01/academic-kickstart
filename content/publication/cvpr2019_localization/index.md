+++
title = "L3-Net: Towards Learning based LiDAR Localization for Autonomous Driving"
date = 2019-02-16T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Weixin Lu", "Yao Zhou", "Guowei Wan", "Shenhua Hou", "**Shiyu Song**"]

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
publication_short = "In **CVPR**"

# Abstract and optional shortened version.
abstract = "We present L3-Net - a novel learning-based LiDAR localization system that achieves centimeter-level localization accuracy, comparable to prior state-of-the-art systems with hand-crafted pipelines. Rather than relying on these hand-crafted modules, we innovatively implement the use of various deep neural network structures to establish a learning-based approach. L3-Net learns local descriptors specifically optimized for matching in different real-world driving scenarios. 3D convolutions over a cost volume built in the solution space significantly boosts the localization accuracy. RNNs are demonstrated to be effective in modeling the vehicle's dynamics, yielding better temporal smoothness and accuracy. We comprehensively validate the effectiveness of our approach using freshly collected datasets. Multiple trials of repetitive data collection over the same road and areas make our dataset ideal for testing localization systems. The  SunnyvaleBigLoop sequences, with a year's time interval between the collected mapping and testing data, made it quite challenging, but the low localization error of our method in these datasets demonstrates its maturity for real industrial implementation."
abstract_short = "We present L3-Net - a novel learning-based LiDAR localization system that achieves centimeter-level localization accuracy, comparable to prior state-of-the-art systems with hand-crafted pipelines."

# Is this a featured publication? (true/false)
featured = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = ["msf_localization"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["List"]

# Links (optional).
url_pdf = "pdf/L3Net_W.Lu_Y.Zhou_S.Song_CVPR2019.pdf"
url_supplementary = "pdf/L3Net_W.Lu_Y.Zhou_S.Song_CVPR2019_supplementary.pdf"
#url_preprint = ""
#url_code = ""
url_dataset = "http://data.apollo.auto"
#url_project = ""
#url_slides = ""
url_video = "https://youtu.be/dptbd4D78Mk"
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

