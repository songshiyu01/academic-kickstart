+++
title = "Multi-sensor Fusion based Localization System"
date = 2015-11-02
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = []

# Project summary to display on homepage.
summary = "A robust and precise vehicle localization system that achieves centimeter-level accuracy by adaptively fusing information from multiple complementary sensors, such as GNSS, LiDAR, camera and IMU, for self-driving cars."

# Optional image to display on homepage.
image_preview = "msf_localization_preview.jpg"

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = true

# Does the project detail page use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++

### Summary

We present a robust and precise localization system that achieves centimeter-level localization accuracy in disparate city scenes. Our system adaptively uses information from complementary sensors such as GNSS, LiDAR, and IMU to achieve high localization accuracy and resilience in challenging scenes, such as urban downtown, highways, and tunnels. Rather than relying only on LiDAR intensity or 3D geometry, we make innovative use of LiDAR intensity and altitude cues to significantly improve localization system accuracy and robustness. Our GNSS RTK module utilizes the help of the multi-sensor fusion framework and achieves a better ambiguity resolution success rate. An error-state Kalman filter is applied to fuse the localization measurements from different sources with novel uncertainty estimation. We validate, in detail, the effectiveness of our approaches, achieving 5-10cm RMS accuracy and outperforming previous state-of-the-art systems. Importantly, our system, while deployed in a large autonomous driving fleet, made our vehicles fully autonomous in crowded city streets despite road construction that occurred from time to time. A dataset including more than 60 km real traffic driving in various urban roads is used to comprehensively test our system.

### Sensors

Our autonomous vehicle is equipped with a Velodyne LiDAR HDL-64E. An integrated navigation system, NovAtel ProPak6 plus NovAtel IMU-IGM-A1, is installed for raw sensor data collection, such as GNSS pseudo range and carrier wave, IMU specific force and rotation rate. The built-in tightly integrated inertial and satellite navigation solution was not used. A computing platform equipped with Dual Xeon E5-2658 v3 12 cores, and a Xilinx KU115 FPGA chip with 55% utilization for LiDAR localization.

![Sensor configuration](/img/msf_localization_sensors.png)

### Framework

Overview of the architecture of our system that estimates the optimal position, velocity, attitude (PVA) of the autonomous vehicle using a loosely coupled error-state-Kalman filter. It combines sensor input (purple) with pre-built LiDAR map (yellow). GNSS and LiDAR estimate the PVA used by an error-state Kalman filter as the measurements, while the Kalman filter provides the predicted prior PVA. The strap-down inertial navigation system (SINS) is used as a prediction model in the Kalman filter propagation phase by integrating the specific force $f^b$ measured by the accelerometer and the rotation rate $\omega_{ib}^b$ measured by the gyroscope. The corrections including the bias of accelerometer and gyroscope, the errors of PVA, etc estimated by the Kalman filter are fed to the SINS.

![System framework](/img/msf_localization_framework.png)

### Accuracy

Our system has been extensively tested in real-world driving scenarios. We compare our localization performance against the state-of-the-art intensity-based localization method proposed by Levinson et al. [12] and the built-in tightly-coupled GNSS/IMU integrated solution in the commercial product. In order to explicitly demonstrate the contribution of different sensors, the test results of our proposed system are shown in two modes:

* 2-Systems: LiDAR + IMU
* 3-Systems: LiDAR + GNSS + IMU. 

In the table, we show the quantitative results in both regular or weak GNSS roads. Note our vast performance improvement over [12] and the robust and accurate localization results in both regular and weak GNSS scenarios with centimeter level accuracy.

![System accuracy](/img/msf_localization_accuracy.png)

### Videos

These videos provide a brief description of the project and demonstrate the performance of the localization system.

{{< youtube CEvcwRjDVOg >}}
