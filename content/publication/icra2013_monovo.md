+++
title = "Parallel, Real-Time Monocular Visual Odometry"
date = 2013-05-06
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Shiyu Song**", "Manmohan Chandraker", "Clark C. Guest"]

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
publication = "IEEE International Conference on Robotics and Automation"
publication_short = "**ICRA**"

# Abstract and optional shortened version.
abstract = "We present a real-time, accurate, large-scale monocular visual odometry system for real-world autonomous outdoor driving applications. The key contributions of our work are a series of architectural innovations that address the challenge of robust multithreading even for scenes with large motions and rapidly changing imagery. Our design is extensible for three or more parallel CPU threads. The system uses 3D-2D correspondences for robust pose estimation across all threads, followed by local bundle adjustment in the primary thread. In contrast to prior work, epipolar search operates in parallel in other threads to generate new 3D points at every frame. This significantly boosts robustness and accuracy, since only extensively validated 3D points with long tracks are inserted at keyframes. Fast-moving vehicles also necessitate immediate global bundle adjustment, which is triggered by our novel keyframe design in parallel with pose estimation in a thread-safe architecture. To handle inevitable tracking failures, a recovery method is provided. Scale drift is corrected only occasionally, using a novel mechanism that detects (rather than assumes) local planarity of the road by combining information from triangulated 3D points and the inter-image planar homography. Our system is optimized to output pose within 50 ms in the worst case, while average case operation is over 30 fps. Evaluations are presented on the challenging KITTI dataset for autonomous driving, where we achieve better rotation and translation accuracy than other state-of-the-art systems."
abstract_short = "A real-time, accurate, large-scale monocular visual odometry system for real-world autonomous outdoor driving applications."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = ["monocular_vo"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "pdf/icra2013_monovo.pdf"
url_preprint = "http://ieeexplore.ieee.org/document/6631246/?tp=&arnumber=6631246"
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

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
