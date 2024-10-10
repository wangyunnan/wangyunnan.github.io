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

Currently, I am a second-year Ph.D. student at [Artificial Intelligence Institute](https://ai.sjtu.edu.cn/), Shanghai Jiao Tong University, under the supervison of Prof. [Xiaokang Yang (杨小康)](https://scholar.google.com.hk/citations?hl=zh-CN&user=yDEavdMAAAAJ). Meanwhile, I am also a research intern at [Eastern Institute for Advanced Study](https://www.eitech.edu.cn/?lang=en/) <img src='./images/eias_logo.png' style='height: 0.8em;'> (co-supervised by Prof. [Kevin Zeng (曾文军)](https://scholar.google.com.hk/citations?hl=zh-CN&user=_cUfvYQAAAAJ) and Prof. [Xin Jin (金鑫)](https://scholar.google.com/citations?user=byaSC-kAAAAJ&hl=zh-CN)) and [Ant Research](https://www.antgroup.com/en/technology/) <img src='./images/alipay_logo.png' style='height: 0.9em;'> (supervised by Dr. [Kecheng Zheng (郑可成)](https://scholar.google.com/citations?user=hMDQifQAAAAJ)). Before that, I received my M.S. degree from Shanghai Jiao Tong University in 2023 (supervised by Prof. [Jianxun Li (李建勋)](https://www.researchgate.net/profile/Li-Jianxun/)) and my B.S. degree from Northwestern Polytechnical University in 2020 (supervised by Prof. [Jianhua He (何建华)](https://teacher.nwpu.edu.cn/en/j82zf0vfmf50835d3461429868736702.html)). Besides, I also had a great time interning at 2012 Lab of [Huawei](https://www.huawei.com/en/) <img src='./images/huawei_logo.png' style='height: 1em;'> and Applied Machine Learning of [ByteDance](https://www.bytedance.com/en/) <img src='./images/bytedance_logo.png' style='height: 0.85em;'>.

My research interests include computer vision, semantic segmentation, un-/semi-supervised learning from 2019, and AI Generated Content (AIGC) and multi-modal learning from 2023.

# 🔥 News
- *2024.09*: &nbsp;🎉🎉 Two papers (with one **Spotlight**) were accepted by NeurlPS 2024 (<span style="color:red">**CCF-A**</span>)~
- *2024.08*: &nbsp;🎉🎉 One paper was accepted by BIBM 2024 (<span style="color:red">**Top Bioinformatics Conference, CCF-B**</span>)~
- *2024.07*: &nbsp;🎉🎉 I joined Interaction Intelligence Lab, [Ant Research](https://www.antgroup.com/en/technology/) as a research intern.
- *2024.04*: &nbsp;🎉🎉 Congratulations to Prof. Kevin Zeng on [his election](https://www.eitech.edu.cn/?p=2500) as the **International Fellow of the Canadian Academy of Engineering**.
- *2024.04*: &nbsp;🎉🎉 One paper was accepted by IJCAI 2024 (<span style="color:red">**CCF-A**</span>)~
- *2023.09*: &nbsp;🎉🎉 I joined [Eastern Institute for Advanced Study](https://www.eitech.edu.cn/?lang=en/) as a research intern.
- *2023.05*: &nbsp;🎉🎉 Shanghai Jiao Tong University officially released a [news](https://news.sjtu.edu.cn/zhxw/20230517/182978.html) about me.
- *2023.03*: &nbsp;🎉🎉 I will continue to pursue my Ph.D. degree at Shanghai Jiao Tong University.
- *2023.03*: &nbsp;🎉🎉 I graduated with the **highest honors** from Shanghai Jiao Tong University. 
- *2022.05*: &nbsp;🎉🎉 One paper was accepted by IROS 2022 (<span style="color:red">**Top Robotics Conference, CCF-C**</span>)~


# 📝 Publications 
**Equal contribution**$^\star$; **Corresponding author**$^\dagger$

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurlPS 2024</div><img src='images/nips-disco.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

**Scene Graph Disentanglement and Composition for Generalizable Complex Image Generation**

<span style="color:#1772d0">**Yunnan Wang**, Ziqiang Li, Zequn Zhang, Wenyao Zhang, Baao Xie, Xihui Liu, Wenjun Zeng, Xin Jin$^\dagger$</span>

<em><font color="#663399"><strong>Annual Conference on Neural Information Processing Systems (NeurIPS 2024).</strong></font></em> 
<em><font color="red"><strong>Spotlight.</strong></font></em>

[**Project**](https://neurips.cc/virtual/2024/poster/92965)/[**Arxiv**](https://neurips.cc/virtual/2024/poster/92965)/[**Code**](https://neurips.cc/virtual/2024/poster/92965)
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurlPS 2024</div><img src='images/nips-gem2.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

**Graph-based Unsupervised Disentangled Representation Learning via Multimodal Large Language Models**

<span style="color:#1772d0">Baao Xie, Qiuyu Chen,**Yunnan Wang**, Zequn Zhang, Xin Jin$^\dagger$, Wenjun Zeng</span>

<em><font color="#663399"><strong>Annual Conference on Neural Information Processing Systems (NeurIPS 2024).</strong></font></em> 

[**Project**](https://neurips.cc/virtual/2024/poster/94595)/[**Arxiv**](https://arxiv.org/html/2407.18999v1)/[**Code**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC)
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">BIBM 2024</div><img src='images/bibm.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

**Consistency Prior Matters: Biomedical-Prompting Dual Augmentation for Domain Adaptive Medical Image Segmentation**

<span style="color:#1772d0">**Yunnan Wang**, Zequn Zhang, Xin Jin, Wenjun Zeng$^\dagger$</span>

<em><font color="#663399"><strong>IEEE International Conference on Bioinformatics and Biomedicine (BIBM 2024).</strong></font></em> 
<em><font color="red"><strong>Oral Presentation.</strong></font></em>

[**Project**](https://www.ijcai.org/proceedings/2024/107)/[**Arxiv**](https://arxiv.org/abs/2303.13959)/[**Code**](https://github.com/Arlo0o/StereoScene)
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2024</div><img src='images/ijcai24.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

**Bridging Stereo Geometry and BEV Representation with Reliable Mutual Interaction for Semantic Scene Completion**

<span style="color:#1772d0">Bohan Li, Yasheng Sun, Zhujin Liang, Dalong Du, Zhuanghui Zhang, Xiaofeng Wang, **Yunnan Wang**, Xin Jin, Wenjun Zeng$^\dagger$</span>

<em><font color="#663399"><strong>International Joint Conference on Artificial Intelligence (IJCAI 2024).</strong></font></em>

[**Project**](https://www.ijcai.org/proceedings/2024/107)/[**Arxiv**](https://arxiv.org/abs/2303.13959)/[**Code**](https://github.com/Arlo0o/StereoScene)
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IROS 2022</div><img src='images/iros22.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

**Bilateral Knowledge Distillation for Unsupervised Domain Adaptation of Semantic Segmentation**

<span style="color:#1772d0">**Yunnan Wang**, Jianxun Li$^\dagger$</span>

<em><font color="#663399"><strong>IEEE/RSJ International Conference on Intelligent Robots and System (IROS 2022).</strong></font></em>
<em><font color="red"><strong>Oral Presentation.</strong></font></em>

[**Project**](https://ieeexplore.ieee.org/abstract/document/9981567)/[**Arxiv**](https://ieeexplore.ieee.org/abstract/document/9981567)/[**Code**](https://github.com/Arlo0o/StereoScene)
</div>
</div>


## Preprint

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCSVT 2024</div><img src='images/tcsvt24.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

**Canvas: Compositional Generation for Art Painting with Seamless Subject-Driven Infusion**

<span style="color:#1772d0">**Yunnan Wang**, Ziqiang Li, Wenyao Zhang, Lexiang Lv, Zequn Zhang, Xiaoyu Shen, Xin Jin, Wenjun Zeng$^\dagger$</span>

<em><font color="#663399"><strong>IEEE Transactions on Circuits and Systems for Video Technology (TCSVT), under review.</strong></font></em> 

[**Project**](https://neurips.cc/virtual/2024/poster/92965)/[**Arxiv**](https://neurips.cc/virtual/2024/poster/92965)/[**Code**](https://neurips.cc/virtual/2024/poster/92965)
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMI 2023</div><img src='images/tmi23.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

**Exploring Contrastive Pre-training for Domain Connections in Medical Image Segmentation**

<span style="color:#1772d0">Zequn Zhang$^\star$, Yun Jiang$^\star$, **Yunnan Wang**, Baao Xie, Wenyao Zhang, Yuhang Li, Zhen Chen, Xin Jin, Wenjun Zeng$^\dagger$</span>

<em><font color="#663399"><strong>IEEE Transactions on Medical Imaging (TMI), under review.</strong></font></em>

[**Project**](https://neurips.cc/virtual/2024/poster/92965)/[**Arxiv**](https://neurips.cc/virtual/2024/poster/92965)/[**Code**](https://neurips.cc/virtual/2024/poster/92965)
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KBS 2024</div><img src='images/kbs24.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

**Single-Instance Feature Bias Calibrating Learning Base EM for Text-to-Image Person Re-identification**

<span style="color:#1772d0">Yifeng Gou, Ziqiang Li, Junyin Zhang, **Yunnan Wang**, Yongxin Ge$^\dagger$</span>

<em><font color="#663399"><strong>Knowledge-based Systems (KBS), under review.</strong></font></em>

[**Project**](https://neurips.cc/virtual/2024/poster/92965)/[**Arxiv**](https://neurips.cc/virtual/2024/poster/92965)/[**Code**](https://neurips.cc/virtual/2024/poster/92965)
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Ongoing 2024</div><img src='images/ongoing1.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

**Coarse-to-Fine Monocular Depth Estimation with Text Alignment and Pose Disentanglement**

<span style="color:#1772d0">Wenyao Zhang, Bohan Li, **Yunnan Wang**, Shengyang Zhao, Xin Jin, Wenjun Zeng$^\dagger$</span>

<em><font color="#663399"><strong>Ongoing work.</strong></font></em>

[**Project**](https://neurips.cc/virtual/2024/poster/92965)/[**Arxiv**](https://neurips.cc/virtual/2024/poster/92965)/[**Code**](https://neurips.cc/virtual/2024/poster/92965)
</div>
</div>

# 📖 Educations
- *2023.03 - present*,  **Ph.D. in Computer Science,Shanghai Jiao Tong University (SJTU), Shanghai**
- *2020.09 - 2023.03*, **M.S. in Automation, Shanghai Jiao Tong University (SJTU), Shanghai**
- *2016.09 - 2020.09*, **B.S. in Automation, Northwestern Polytechnical University (NWPU), Xi'an, Shaanxi**

# 💻 Internships
- *2024.07 - present*:  **Interaction Intelligence Lab, Ant Research <img src='./images/alipay_logo.png' style='height: 0.9em;'>, Hangzhou, Zhejiang**
  - Position: Multi-Modal Algorithm Intern
  - Duty: Multi-Modal Algorithm Research
  - Supervisor: Dr. [Kecheng Zheng](https://scholar.google.com/citations?user=hMDQifQAAAAJ)

- *2023.09 - present*: **College of Information Science and Technology, Eastern Institute for Advanced Study <img src='./images/eias_logo.png' style='height: 0.8em;'>, Ningbo, Zhejiang**
  - Position: Computer Vision Algorithm Intern
  - Dutiy: AI Generated Content (AIGC) Research
  - Supervisor: Prof. [Wenjun Zeng](https://scholar.google.com.hk/citations?hl=zh-CN&user=_cUfvYQAAAAJ) and Prof. [Xin Jin](https://scholar.google.com/citations?user=byaSC-kAAAAJ&hl=zh-CN)

* *2022.06 - 2022.10*: **Central Media Technology Institute, 2012 Lab, Huawei <img src='./images/huawei_logo.png' style='height: 1em;'>, Shanghai**
  * Position: Computer Vision Algorithm Intern
  * Duty: Optical Flow Estimation, Motion Detection, and Lane Detection
  * Supervisor: Dr. [Jia Cai](https://scholar.google.com.hk/citations?user=gg6nH6QAAAAJ&hl=zh-CN&oi=sra)

* *2022.03 - 2022.06*: **Applied Machine Learning (AML), ByteDance <img src='./images/bytedance_logo.png' style='height: 0.85em;'>, Shanghai**
  * Position: Machine Learning Algorithm Intern
  * Duty: Recommendation/Advertising/Search Algorithm Research
  * Supervisor: Dr. Xiang Li

# 🎖 Honors and Awards
- *2023.03* Excellent Graduate of Shanghai (*Top 3%* in SJTU)
- *2022.09* CETC Les <img src='./images/les_logo.jpg' style='height: 0.9em;'> Scholarship (SJTU)
- *2021.10* **National Scholarship** for Graduate Students (*Top 3%* in SJTU)
- *2020.06* Excellent Graduate of Shaanxi Province(*Top 3%* in NWPU)
- *2019.11* Wu Yajun <img src='./images/longhu_logo.png' style='height: 0.85em;'> Scholarship (NWPU)
- *2018.11* The Third Prize of National Undergraduate Electronics Design Contest
- *2018.10* **National Scholarship** for Undergraduate Students (*Top 1%* in NWPU)
- *2018.05* Meritorious Winner of the Interdisciplinary Contest in Modeling (ICM) <img src='./images/comap_logo.png' style='height: 1em;'>
- *2017.10* Guangdong-Hong Kong-Macao <img src='./images/hk.png' style='height: 1em;'> Scholarship (NWPU)
- *2015.09* The Second Prize of Chinese Physics Olympiad <img src='./images/cpo_logo.png' style='height: 1em;'>
- *2015.09* The Third Prize of Chinese Mathematical Olympiad <img src='./images/cmo_logo.png' style='height: 0.9em;'>

# 💬 Activities
- Reviewer: NeurlPS, CVPR, ICCV, ACM MM, TCSVT and TNNLS etc.
- *2023.03 - present*, Alumni Trustee of Shanghai Jiao Tong University.
- *2020.09 - 2023.03*, Monitor of Master Class B2003292, Shanghai Jiao Tong University.
- *2016.09 - 2020.06*, Mental-Health Counselor, Northwestern Polytechnical University.
- Avocation <img src='./images/sports.png' style='height: 1em;'>: Competitive road cycling <img src='./images/bike.png' style='height: 1em;'> (more than 10 years); Marathon <img src='./images/track.png' style='height: 1em;'> (Half Marathon PB 1:27, Marathon PB 3:08).


<div id="footer-clusrmaps" style="width: 50%; position:relative; left:25%">
    <center>
        <div id="clustrmaps-widget" style="width:40%">
            <script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?d=zZNkfKhgzaLVh3Ca6PfppQ7OF2_hj7qf29D-Dz1hXUY"></script>
        </div>
    </center>
</div>
<!-- <script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=zZNkfKhgzaLVh3Ca6PfppQ7OF2_hj7qf29D-Dz1hXUY&cl=ffffff&w=a"></script> -->

