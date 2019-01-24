+++
title = "Robust and Precise Vehicle Localization based on Multi-sensor Fusion in Diverse City Scenes"
date = 2018-05-21T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Guowei Wan", "Xiaolong Yang", "Renlan Cai", "Hao Li", "Yao Zhou", "Hao Wang", "**Shiyu Song**"]

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
publication = "In *IEEE International Conference on Robotics and Automation (ICRA)*, IEEE."
publication_short = "In **ICRA**"

# Abstract and optional shortened version.
abstract = "We present a robust and precise localization system that achieves centimeter-level localization accuracy in disparate city scenes. Our system adaptively uses information from complementary sensors such as GNSS, LiDAR, and IMU to achieve high localization accuracy and resilience in challenging scenes, such as urban downtown, highways, and tunnels. Rather than relying only on LiDAR intensity or 3D geometry, we make innovative use of LiDAR intensity and altitude cues to significantly improve localization system accuracy and robustness. Our GNSS RTK module utilizes the help of the multi-sensor fusion framework and achieves a better ambiguity resolution success rate. An error-state Kalman filter is applied to fuse the localization measurements from different sources with novel uncertainty estimation. We validate, in detail, the effectiveness of our approaches, achieving 5-10cm RMS accuracy and outperforming previous state-of-the-art systems. Importantly, our system, while deployed in a large autonomous driving fleet, made our vehicles fully autonomous in crowded city streets despite road construction that occurred from time to time. A dataset including more than 60 km real traffic driving in various urban roads is used to comprehensively test our system."
abstract_short = "A robust and precise localization system that achieves centimeter-level localization accuracy by adaptively fusing information from complementary sensors such as GNSS, LiDAR, and IMU in disparate city scenes, such as urban downtown, highways, and tunnels."

# Is this a featured publication? (true/false)
featured = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = ["msf_localization"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "pdf/ICRA18_0470_FI.pdf"
#url_preprint = ""
#url_code = ""
#url_dataset = ""
#url_project = ""
#url_slides = ""
url_video = "https://youtu.be/8wRs_TaAfUk"
#url_poster = ""
#url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = "10.1109/ICRA.2018.8461224"

# Does this page contain LaTeX math? (true/false)
math = false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"
+++
