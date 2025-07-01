---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

My research interests include Multimodal Sensor Fusion, Unmanned Surface Vehicles, and Intelligent Transportation Systems.
<a href='https://scholar.google.com/citations?user=SHLZ-cYAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.


# 🔥 News
- *2025.06*: &nbsp;🎉🎉 A USV-based object tracking dataset in inland waterways is accepted by IROS.
- *2025.03*: &nbsp;🎉 A survey for Radar Data Representations is accepted by [TITS](https://ieeexplore.ieee.org/document/10952908).
- *2024.06*: &nbsp;🌟 A 4D Radar-Camera Fusion Dataset is accepted by [TITS](https://ieeexplore.ieee.org/document/10571852).
- *2024.09*: &nbsp; Radar-Camera Fusion is a Highly Cited Paper 🏆 by [WOS](https://www.webofscience.com/wos/woscc/full-record/WOS:001173317800176).
- *2023.08*: &nbsp; A survey for Radar-Camera Fusion is accepted by [TIV](https://ieeexplore.ieee.org/document/10225711). 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TITS</div><img src='images/WaterScenes.png' alt="" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[WaterScenes: A Multi-Task 4D Radar-Camera Fusion Dataset and Benchmarks for Autonomous Driving on Water Surfaces](https://ieeexplore.ieee.org/document/10571852)

**Shanliang Yao**, Runwei Guan, Zhaodong Wu, Yi Ni, Ryan Wen Liu, Yong Yue, Xiaohui Zhu, Yutao Yue, etc.

[[**Website**]](https://waterscenes.github.io) 
[![](https://img.shields.io/github/stars/WaterScenes/WaterScenes?style=social&label=Code+Stars)](https://github.com/WaterScenes/WaterScenes) 
<img src="https://img.shields.io/badge/dynamic/json?url=https://raw.githubusercontent.com/yaoshanliang/yaoshanliang.github.io/google-scholar-stats/gs_data.json&query=$.publications.SHLZ-cYAAAAJ:U_HPUtbDl20C.num_citations&logo=Google%20Scholar&label=citations&color=9cf&labelColor=f6f6f6&style=flat">
<span class='show_paper_citations' data='SHLZ-cYAAAAJ:e84hm74t-eoC'></span>
- The first multi-task 4D radar-camera fusion dataset on water surfaces, which offers data from multiple sensors, including a 4D radar, monocular camera, GPS, and IMU.
- It can be applied in multiple tasks, such as object detection, instance segmentation, semantic segmentation, free-space segmentation, and waterline segmentation.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IROS</div><img src='images/USVTrack.png' alt="" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[USVTrack: USV-Based 4D Radar-Camera Tracking Dataset for Autonomous Driving in Inland Waterways](https://arxiv.org/abs/2506.18737)

**Shanliang Yao**, Runwei Guan, Yi Ni, Yong Yue, Xiaohui Zhu, Ryan Wen Liu.

[[**Website**]](https://usvtrack.github.io) 
[![](https://img.shields.io/github/stars/usvtrack/usvtrack?style=social&label=Code+Stars)](https://github.com/usvtrack/usvtrack) 
<img src="https://img.shields.io/badge/dynamic/json?url=https://raw.githubusercontent.com/yaoshanliang/yaoshanliang.github.io/google-scholar-stats/gs_data.json&query=$.publications.SHLZ-cYAAAAJ:hefNtdE4IMkC.num_citations&logo=Google%20Scholar&label=citations&color=9cf&labelColor=f6f6f6&style=flat">
<span class='show_paper_citations' data='SHLZ-cYAAAAJ:hefNtdE4IMkC'></span>
- The first USV-based 4D radar-camera tracking dataset for autonomous driving in waterborne transportation systems, providing comprehensive data from four sensors: a 4D radar, a monocular optical camera, a GPS and an IMU.
- USVTrack contains a rich diversity of data samples, including various waterways (wide and narrow rivers, lakes, canals, moats and docks), diverse time conditions (daytime, nightfall, night), weather conditions (sunny, overcast, rainy, snowy), and lighting conditions (normal, dim, strong).
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TITS</div><img src='images/RadarPerception.png' alt="" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Exploring Radar Data Representations in Autonomous Driving: A Comprehensive Review](https://ieeexplore.ieee.org/document/10952908)

**Shanliang Yao**, Runwei Guan, Yong Yue, Xiaohui Zhu, Yutao Yue, etc.

[[**Website**]](https://radar-camera-fusion.github.io/radar) [Github](https://github.com/Radar-Camera-Fusion/Awesome-Radar-Perception)
[![](https://img.shields.io/github/stars/Radar-Camera-Fusion/Awesome-Radar-Perception?style=social&label=Code+Stars)](https://github.com/Radar-Camera-Fusion/Awesome-Radar-Perception) 
<img src="https://img.shields.io/badge/dynamic/json?url=https://raw.githubusercontent.com/yaoshanliang/yaoshanliang.github.io/google-scholar-stats/gs_data.json&query=$.publications.SHLZ-cYAAAAJ:e84hm74t-eoC.num_citations&logo=Google%20Scholar&label=citations&color=9cf&labelColor=f6f6f6&style=flat">
<span class='show_paper_citations' data='SHLZ-cYAAAAJ:e84hm74t-eoC'></span>
- We offer an up-to-date (2019-2024) overview of radar-based datasets and algorithms, providing in-depth research on their advantages and limitations.
- We analyze the significant challenges and open questions related to these data representations, and propose potential research directions for further investigation.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TIV</div><img src='images/Radar-Camera-Fusion.png' alt="" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Radar-Camera Fusion for Object Detection and Semantic Segmentation in Autonomous Driving: A Comprehensive Review](https://ieeexplore.ieee.org/document/10225711)

**Shanliang Yao**, Runwei Guan, Yong Yue, Xiaohui Zhu, Yutao Yue, etc.

[[website]](https://waterscenes.github.io) [Github](https://github.com/Radar-Camera-Fusion/Awesome-Radar-Camera-Fusion)
[![](https://img.shields.io/github/stars/Radar-Camera-Fusion/Awesome-Radar-Camera-Fusion?style=social&label=Code+Stars)](https://github.com/Radar-Camera-Fusion/Awesome-Radar-Camera-Fusion) 
<img src="https://img.shields.io/badge/dynamic/json?url=https://raw.githubusercontent.com/yaoshanliang/yaoshanliang.github.io/google-scholar-stats/gs_data.json&query=$.publications.SHLZ-cYAAAAJ:oTdOBqtIf_kC.num_citations&logo=Google%20Scholar&label=citations&color=9cf&labelColor=f6f6f6&style=flat">
<span class='show_paper_citations' data='SHLZ-cYAAAAJ:e84hm74t-eoC'></span>
- We present an up-to-date (2019–2023) overview of radar-camera fusion datasets and algorithms, and conduct in-depth research on “why to fuse”, “what to fuse”, “where to fuse”, “when to fuse”, and “how to fuse”.
- We analyze the critical challenges and open questions in radar-camera fusion, and put forward potential research directions.
</div>
</div>


- [USVTrack: USV-Based 4D Radar-Camera Tracking Dataset for Autonomous Driving in Inland Waterways](https://arxiv.org/abs/2506.18737). **Shanliang Yao**, Runwei Guan, Yi Ni, Yong Yue, Xiaohui Zhu, Ryan Wen Liu. *2025 38th IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS 2025)*, Hangzhou, China, 2025.
- [Exploring Radar Data Representations in Autonomous Driving: A Comprehensive Review](https://ieeexplore.ieee.org/document/10952908). **Shanliang Yao**, Runwei Guan, Zitian Peng, Chenhang Xu, Yilu Shi, Yong Yue, Weiping Ding, Eng Gee Lim, Hyungjoon Seo, Ka Lok Man, Jieming Ma, Xiaohui Zhu, Yutao Yue. *IEEE Transactions on Intelligent Transportation Systems*. 2025, 26(6): 7401-7425, doi: 10.1109/TITS.2025.3554781.
- [WaterScenes: A Multi-Task 4D Radar-Camera Fusion Dataset and Benchmarks for Autonomous Driving on Water Surfaces](https://ieeexplore.ieee.org/document/10571852). **Shanliang Yao**, Runwei Guan, Zhaodong Wu, Yi Ni, Zile Huang, Ryan Wen Liu, Yong Yue, Weiping Ding, Eng Gee Lim, Hyungjoon Seo, Ka Lok Man, Jieming Ma, Xiaohui Zhu, Yutao Yue. *IEEE Transactions on Intelligent Transportation Systems*, 2024, 25(11): 16584-16598, doi: 10.1109/TITS.2024.3415772.
- [Radar-Camera Fusion for Object Detection and Semantic Segmentation in Autonomous Driving: A Comprehensive Review](https://ieeexplore.ieee.org/document/10225711). **Shanliang Yao**, Runwei Guan, Xiaoyu Huang, Zhuoxiao Li, Xiangyu Sha, Yong Yue, Eng Gee Lim, Hyungjoon Seo, Ka Lok Man, Xiaohui Zhu, Yutao Yue. *IEEE Transactions on Intelligent Vehicles*, 2024, 9(1): 2094-2128, doi: 10.1109/TIV.2023.3307157.
- [WaterVG: Waterway Visual Grounding Based on Text-Guided Vision and mmWave Radar](https://ieeexplore.ieee.org/document/10847630/). Runwei Guan, Liye Jia, **Shanliang Yao**, Fengyufan Yang, Erick Purwanto, Xiaohui Zhu, Eng Gee Lim, Jeremy Smith, Ka Lok Man, Xuming Hu, Yutao Yue. *IEEE Transactions on Intelligent Transportation Systems*, 2025, vol. 26, no. 5, pp. 7275-7291, doi: 10.1109/TITS.2025.3527011.
- [ASY-VRNet: Waterway Panoptic Driving Perception Model Based on Asymmetric Fair Fusion of Vision and 4D mmWave Radar](https://ieeexplore.ieee.org/document/10802447). Runwei Guan, **Shanliang Yao**, Xiaohui Zhu, Ka Lok Man, Yong Yue, Jeremy Smith, Eng Gee Lim, Yutao Yue. *2024 37th IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS 2024)*, Abu Dhabi, United Arab Emirates, 2024, 12479-12486, doi: 10.1109/IROS58592.2024.10802447.
- [Achelous: A Fast Unified Water-Surface Panoptic Perception Framework Based on Fusion of Monocular Camera and 4D mmWave Radar](https://ieeexplore.ieee.org/document/10422325). Runwei Guan, **Shanliang Yao**, Xiaohui Zhu, Ka Lok Man, Eng Gee Lim, Jeremy Smith, Yong Yue, Yutao Yue. *2023 IEEE 26th International Conference on Intelligent Transportation Systems (ITSC 2023)*, Bilbao, Spain, 2023, 182-188, doi: 10.1109/ITSC 57777.2023.10422325.
- [Mask-VRDet: A Robust Riverway Panoptic Perception Model Based on Dual Graph Fusion of Vision and 4D mmWave Radar](https://www.sciencedirect.com/science/article/abs/pii/S0921889023002117). Runwei Guan, **Shanliang Yao**, Lulu Liu, Xiaohui Zhu, Ka Lok Man, Yong Yue, Jeremy Smith, Eng Gee Lim, Yutao Yue. *Robotics and Autonomous Systems*, 2024, 171: 104572, doi: 10.1016/j.robot.2023.104572.

# 🎖 Honors and Awards
- Project Management Professional (PMI-PMP), International Project Management Institute
- Information System Project Manager, Ministry of Industry and Information Technology

- *2022* The 8th ‘Internet+’ Student Innovation and Entrepreneurship Competition, Bronze Award in National Finals
- *2022* The 12th ‘Challenge Cup’ National College Student Business Plan Competition, Bronze Award in Jiangsu Provincial Competition
- *2020* The 6th ‘Internet+’ Student Innovation and Entrepreneurship Competition, Second Prize in Jiangsu Provincial Competition

# 📖 Educations
- *2021.09 - 2024.11*, Ph.D. in Computer Science and Software Engineering, University of Liverpool.
- *2019.09 - 2021.04*, M.S. in Applied Informatics, University of Liverpool.
- *2012.08 - 2016.06*, B.E. in Software Engineering, Soochow University.


# 💻 Services
- Reviewer of TITS, TIV, TCSVT, TMC, RAL, ICRA, IROS, PR, etc.

