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
- *2025.02*: &nbsp;🎉🎉 Our paper CAD-Mesher is accepted to IEEE Trans. on MultiMedia 2025!
- *2024.12*: &nbsp;🎉🎉 Our paper TRLO is accepted to RA-L 2025!

# 📖 Educations
- *2023.09 - present*, Master,  The State Key Laboratory of Robotics at Shenyang Institute of Automation, Chinese Academy of Sciences, Shenyang, China.
- *2019.09 - 2023.06*, Undergraduate, Department of Mechanical Engineering, Harbin Institute of Technology, Weihai, China.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-MM 2025</div><img src='images/cad-mesher.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CAD-Mesher: A Convenient, Accurate, Dense Mesh-based Mapping Module in SLAM for Dynamic Environments](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Yanpeng Jia**, Fengkui Cao\*, Ting Wang\*, Yandong Tang, Shiliang Shao and Lianqing Liu

[**Project**](https://yaepiii.github.io/CAD-Mesher/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- An accurate, consecutive, and dense meshing module adapting to dynamic environments, which is plug-and-play for conveniently integrating with various LiDAR odometry to further improve the pose estimation accuracy and filter dynamic objects. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RA-L 2025</div><img src='images/trlo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TRLO: An Efficient LiDAR Odometry with 3D Dynamic Object Tracking and Removal](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Yanpeng Jia**, Ting Wang\*, Fengkui Cao\*, Xieyuanli Chen, Shiliang Shao and Lianqing Liu

[**Project**](https://yaepiii.github.io/TRLO/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- A dynamic LiDAR odometry that can filter dynamic objects through a 3D multi-object tracker and achieve more accurate pose estimation through bounding box posture consistency constraint. 
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

Journal Reviewer: T-RO, RA-L, T-MM, T-IV, T-IM
