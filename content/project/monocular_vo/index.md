+++
title = "Monocular Visual Odometry"
date = 2012-02-18T00:00:00

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = []

# Project summary to display on homepage.
summary = "A real-time monocular visual odometry system that corrects for scale drift using a novel cue combination framework for ground plane estimation, yielding accuracy comparable to stereo over long driving sequences."


# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com/georgecushen"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
[image]
  # Caption (optional)
  caption = ""
  
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++
### Summary

Scale drift is a crucial challenge for monocular autonomous driving to emulate the performance of stereo. This paper presents a real-time monocular SFM system that corrects for scale drift using a novel cue combination framework for ground plane estimation, yielding accuracy comparable to stereo over long driving sequences. Our ground plane estimation uses multiple cues like sparse features, dense inter-frame stereo and (when applicable) object detection. A data-driven mechanism is proposed to learn models from training data that relate observation covariances for each cue to error behavior of its underlying variables. During testing, this allows per-frame adaptation of observation covariances based on relative confidences inferred from visual data. Our framework significantly boosts not only the accuracy of monocular self-localization, but also that of applications like object localization that rely on the ground plane. Experiments on the KITTI dataset demonstrate the accuracy of our ground plane estimation, monocular SFM and object localization relative to ground truth, with detailed comparisons to prior art.

### Accuracy

We demonstrate our performance on the KITTI dataset. For camera self-localization, our purely vision-based system achieves a rotation error of 0.005 degrees per meter and a translation error of 2.5%, which compares favorably even to state-of-the-art stereo systems and significantly outperforms other monocular systems. For 3D localization of other traffic participants like cars, we achieve low errors of 8% for near objects (within 30 meters) and 12% for far objects (beyond 30 meters).

![The overview of the monocular visual odometry system](/img/monocular_vo_overview.png)

### Cue combination

The main challenge in monocular SFM is scale drift, since unlike the case of stereo, there is no reference baseline. We overcome this challenge with a novel cue combination framework, that combines information from 3D points, inter-frame stereo and object detection.

![The cue combination of the monocular visual odometry system](/img/monocular_vo_cue.png)

### Comparison to other systems

Our real-time monocular SFM is comparable in accuracy to state-of-the-art stereo systems and significantly outperforms other monocular systems. A few example sequences are shown here from the KITTI benchmark.

![The comparison to other systems](/img/monocular_vo_comparison.png)

### Videos

These videos provide a 1-minute description of the paper and demonstrate the monocular visual odometry and 3D object localization results.

##### Overview

{{< youtube RN-WHId0tek >}}

##### 3D object localization

{{< youtube _uxX_DlJ0CI >}}

##### Monocular visual odometry

{{< youtube 7orRPfRbhUs >}}
