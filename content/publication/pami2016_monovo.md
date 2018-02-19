+++
title = "High Accuracy Monocular SFM and Scale Correction for Autonomous Driving"
date = 2016-04-01
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
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "IEEE Transactions on Pattern Analysis and Machine Intelligence"
publication_short = "**T-PAMI**"

# Abstract and optional shortened version.
abstract = "We present a real-time monocular visual odometry system that achieves high accuracy in real-world autonomous driving applications. First, we demonstrate robust monocular SFM that exploits multithreading to handle driving scenes with large motions and rapidly changing imagery. To correct for scale drift, we use known height of the camera from the ground plane. Our second contribution is a novel data-driven mechanism for cue combination that allows highly accurate ground plane estimation by adapting observation covariances of multiple cues, such as sparse feature matching and dense inter-frame stereo, based on their relative confidences inferred from visual data on a per-frame basis. Finally, we demonstrate extensive benchmark performance and comparisons on the challenging KITTI dataset, achieving accuracy comparable to stereo and exceeding prior monocular systems. Our SFM system is optimized to output pose within 50 ms in the worst case, while average case operation is over 30 fps. Our framework also significantly boosts the accuracy of applications like object localization that rely on the ground plane."
abstract_short = "A real-time monocular visual odometry system that achieves high accuracy in real-world autonomous driving applications."

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
url_pdf = "pdf/pami2016_monovo.pdf"
url_preprint = "http://ieeexplore.ieee.org/document/7206590/"
#url_code = ""
#url_dataset = ""
#url_project = ""
#url_slides = ""
#url_video = ""
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
