+++
title = "LiDAR Inertial Odometry Aided Robust LiDAR Localization System in Changing City Scenes"
date = 2020-01-20T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Wendong Ding", "Shenhua Hou", "Hang Gao", "Guowei Wan", "**Shiyu Song**"]

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
publication = "*IEEE International Conference on Robotics and Automation (ICRA)*"
publication_short = "In **ICRA**"

# Abstract and optional shortened version.
abstract = "Environmental fluctuations pose crucial challenges to a localization system in autonomous driving. We present a robust LiDAR localization system that maintains its kinematic estimation in changing urban scenarios by using a dead reckoning solution implemented through a LiDAR inertial odometry. Our localization framework jointly uses information from complementary modalities such as global matching and LiDAR inertial odometry to achieve accurate and smooth real time localization estimation. To improve the performance of the LiDAR odometry, we incorporate inertial and LiDAR intensity cues into an occupancy grid based LiDAR odometry to enhance frame-to-frame motion and matching estimation. Multi-resolution occupancy grid is implemented yielding a coarse-to-fine approach to balance the odometry's precision and computational requirement. To fuse both the odometry and global matching results, we formulate a MAP estimation problem in a pose graph fusion framework that can be efficiently solved. An effective environmental change detection method is proposed that allows us to know exactly when and what portion of the map requires an update. We comprehensively validate the effectiveness of the proposed approaches using both the Apollo SouthBay dataset and our internal dataset. The results confirm that our efforts lead to a more robust and accurate localization system, especially in dynamically changing urban scenarios, outperforming state-of-the-art approaches."
#abstract_short = "We present a robust LiDAR localization system that maintains its kinematic estimation in changing urban scenarios by using a dead reckoning solution implemented through a LiDAR inertial odometry."

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
#url_pdf = "pdf/DeepVCP_W.Lu_S.Song_ICCV2019.pdf"
#url_supplementary = "pdf/L3Net_W.Lu_Y.Zhou_S.Song_CVPR2019_supplementary.pdf"
#url_preprint = ""
#url_code = ""
#url_dataset = "http://data.apollo.auto"
#url_project = ""
#url_slides = ""
#url_video = "https://www.youtube.com/watch?v=O9AMulNyrzY"
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
