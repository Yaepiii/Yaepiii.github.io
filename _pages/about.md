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

My name is Yanpeng Jia (贾彦鹏), I received the B.S. degree in Department of Mechanical Engineering from Harbin Institute of Technology, Weihai, China in 2023. I'm currently pursuing the M.S degree with the Shenyang Institute of Automation, Chinese Academy of Sciences. My current research interests include robot control, LiDAR Odometry and dynamic SLAM.


# 🔥 News
- *2025.03*: &nbsp;🎉🎉 Our paper M2UD is accepted to IJRR 2025!
- *2025.02*: &nbsp;🎉🎉 Our paper 《面向地面机器人的通用鲁棒激光SLAM技术》 is accepted to 《机器人》!
- *2024.11*: &nbsp;🎉🎉 Our paper 《面向地面机器人的通用鲁棒激光SLAM技术》 is submitted to 《机器人》!
- *2024.10*: &nbsp;🎉🎉 Our paper TRLO is submitted to T-IM 2025!
- *2024.09*: &nbsp;🎉🎉 Our paper CAD-Mesher is submitted to IEEE Trans. on MultiMedia 2025!
- *2024.08*: &nbsp;🎉🎉 Our paper C-LOAM is accepted to IEEE ICUS 2024!

# 📖 Educations
- *2023.09 - present*, Master,  The State Key Laboratory of Robotics at Shenyang Institute of Automation, Chinese Academy of Sciences, Shenyang, China.
- *2019.09 - 2023.06*, Undergraduate, Department of Mechanical Engineering, Harbin Institute of Technology, Weihai, China.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJRR 2025</div><img src='images/m2ud.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[M2UD: A Multi-model, Multi-scenario, Uneven-terrain Dataset for Ground Robot with Localization and Mapping Evaluation](https://arxiv.org/pdf/2503.12387)

**Yanpeng Jia**, Shiyi Wang, Shiliang Shao\*, Yue Wang, Fu Zhang，Ting Wang\*

[**Project**](https://yaepiii.github.io/M2UD/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- The dataset includes 58 sequences across 12 categories, collected from a diverse set of highly challenging environments, including urban areas, rural regions, open fields, long corridors, and mixed scenarios, etc, covering a total distance of over 50 km. 
- We collect data under extreme weather conditions, including darkness, smoke, snow, sand, and dust, to support researchers in developing SLAM solutions for such extreme situations.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">机器人</div><img src='images/gr-loam++.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[面向地面机器人的通用鲁棒激光SLAM技术](https://yaepiii.github.io/)

**贾彦鹏**, 王挺, 邵士亮\*, 王少聪, 王世逸，曹风魁

[**Project**](https://yaepiii.github.io/GR-LOAM_Plus_Plus/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- 这是我们之前工作[GR-LOAM](https://www.sciencedirect.com/science/article/pii/S0921889021000440)和[RGC-SLAM](https://ieeexplore.ieee.org/abstract/document/10654559)的进一步拓展，改进了之前的地面提取方案和特征提取方案，使得算法适用于各种型号的雷达。
- 另外，通过引入强度特征，以及几何相似性和强度相似性约束，使得算法取得更鲁棒的效果。
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-MM 2025</div><img src='images/cad-mesher.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CAD-Mesher: A Convenient, Accurate, Dense Mesh-based Mapping Module in SLAM for Dynamic Environments](https://arxiv.org/pdf/2408.05981)

**Yanpeng Jia**, Fengkui Cao\*, Ting Wang\*, Yandong Tang, Shiliang Shao and Lianqing Liu

[**Project**](https://yaepiii.github.io/CAD-Mesher/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- An accurate, consecutive, and dense meshing module adapting to dynamic environments, which is plug-and-play for conveniently integrating with various LiDAR odometry to further improve the pose estimation accuracy and filter dynamic objects. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-IM 2025</div><img src='images/trlo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TRLO: An Efficient LiDAR Odometry with 3D Dynamic Object Tracking and Removal](https://arxiv.org/pdf/2410.13240)

**Yanpeng Jia**, Ting Wang\*, Xieyuanli Chen and Shiliang Shao

[**Project**](https://yaepiii.github.io/TRLO/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- A dynamic LiDAR odometry that can filter dynamic objects through a 3D multi-object tracker and achieve more accurate pose estimation through bounding box posture consistency constraint. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICUS 2024</div><img src='images/c-loam.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Compact LiDAR Odometry and Mapping with Dynamic Removal](https://arxiv.org/pdf/2410.13240)

Meifeng Zhang, **Yanpeng Jia**\*, Shiliang Shao\* and Shiyi Wang

[**Project**](https://yaepiii.github.io/C-LOAM/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- A compact LiDAR odometry that can filter dynamic objects, extract ground points, and segmentation through range image and achieve more accurate pose estimation through ground normal and z-axis constraint. 
</div>
</div>

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
-->

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
-->

# 💻 Academic Services
Conference Reviewer: CVPR, ICCV, ECCV, IROS, ICRA, ICUS, ASCC

Journal Reviewer: T-RO, RA-L, T-MM, T-ITS, T-IV, T-IM，机器人
