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

<span class="anchor" id="about-me"></span>

I am currently a Ph.D. at [South China University of Techonology (SCUT)](https://www.scut.edu.cn/en/), advised by [Prof. Kui Jia](http://kuijia.site/). I received my bachelor degree from the same university (i.e. SCUT) in 2020, and expect to obtain my Ph.D. degree in 2025. I am currently an intern at [Tencent AI Lab](https://ai.tencent.com/ailab/zh/index).

I mainly focus on **3D Computer Vision**. My current research interests include Computer Graphics, 3D Semantic Learning and Reconstruction. Recently, I am working on Multi-View Reconstruction.


<!-- # 🔥 News -->
<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications

<div class="paper-box"><div class="paper-box-image"><div><div class="badge">arXiv 2024</div><img src="images/sur2f.png" alt="sym" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

[Sur2f: A Hybrid Representation for High-Quality and Efficient Surface Reconstruction from Multi-view Images](https://arxiv.org/abs/2401.03704)

Zhangjin Huang\*, **Zhihao Liang\***, Haojie Zhang, Yangkai Lin, Kui Jia

[**Project**](https://huang-zhangjin.github.io/project-pages/sur2f.html) | [**Code**](https://huang-zhangjin.github.io/project-pages/comming_soom.html)
- We propose a new hybrid representation, termed Sur2f, that can enjoy the benefits of both explicit and implicit surface representations. This is achieved by learning two parallel streams of an implicit SDF and an explicit surrogate surface mesh, both of which, by rendering, receive supervision from multi-view image observations.
</div>
</div>

<div class="paper-box"><div class="paper-box-image"><div><div class="badge">arXiv 2023</div><img src="images/gs-ir.png" alt="sym" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

[GS-IR: 3D Gaussian Splatting for Inverse Rendering](https://arxiv.org/abs/2311.16473)

**Zhihao Liang\***, Qi Zhang\*, Ying Feng, Ying Shan, Kui Jia

[**Project**](https://lzhnb.github.io/project-pages/gs-ir.html) | [**Code**](https://github.com/lzhnb/GS-IR)
- We present GS-IR that models a scene as a set of 3D Gaussians to achieve physically-based rendering and state-ofthe-art decomposition results for both objects and scenes.
</div>
</div>

<div class="paper-box"><div class="paper-box-image"><div><div class="badge">CVPR 2023</div><img src="images/HelixSurf.png" alt="sym" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

[HelixSurf: A Robust and Efficient Neural Implicit Surface Learning of Indoor Scenes with Iterative Intertwined Regularization](https://arxiv.org/pdf/2302.14340.pdf)

**Zhihao Liang\***, Zhangjin Huang\*, Changxing Ding, Kui Jia

[**Project**](https://lzhnb.github.io/project-pages/helixsurf.html) | [**Code**](https://github.com/Gorilla-Lab-SCUT/HelixSurf)
- We present a novel method of HelixSurf for reconstruction of indoor scene surface from multi-view images. HelixSurf enjoys the complementary benefits of the traditional MVS and the recent neural implicit surface learning, by regularizing the learning/optimization of one strategy iteratively using the intermediate prediction from the other.
</div>
</div>

<div class="paper-box"><div class="paper-box-image"><div><div class="badge">CVPR 2022</div><img src="images/VISTA.png" alt="sym" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

[VISTA: Boosting 3D Object Detection via Dual Cross-VIew SpaTial Attention](https://openaccess.thecvf.com/content/CVPR2022/papers/Deng_VISTA_Boosting_3D_Object_Detection_via_Dual_Cross-VIew_SpaTial_Attention_CVPR_2022_paper.pdf)

Shengheng Deng\*, **Zhihao Liang\***, Lin Sun, Kui Jia

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=oQpAzREAAAAJ&citation_for_view=oQpAzREAAAAJ:u-x6o8ySG0sC) | [**Code**](https://github.com/Gorilla-Lab-SCUT/VISTA)
- We propose a novel plug-and-play fusion module Dual Cross-VIew SpaTial Attention (VISTA) to produce well-fused multi-view features to boost the performances of 3D object detector. Our proposed VISTA replaces the MLPs with convolutional operators, which is capable of better handling the local cues for attention modeling.
</div>
</div>


<div class="paper-box"><div class="paper-box-image"><div><div class="badge">ICCV 2021</div><img src="images/SSTNet.png" alt="sym" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

[Instance Segmentation in 3D Scenes using Semantic Superpoint Tree Networks](https://openaccess.thecvf.com/content/ICCV2021/papers/Liang_Instance_Segmentation_in_3D_Scenes_Using_Semantic_Superpoint_Tree_Networks_ICCV_2021_paper.pdf)

**Zhihao Liang**, Zhihao Li, Songcen Xu, Mingkui Tan, Kui Jia

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=oQpAzREAAAAJ&citation_for_view=oQpAzREAAAAJ:9yKSN-GCB0IC) | [**Code**](https://github.com/Gorilla-Lab-SCUT/SSTNet)
- We propose an end-to-end solution of Semantic Superpoint Tree Network (SSTNet) to directly propose and evaluate object instances from observed 3D scenes. By working with superpoints, our method enjoys the benefit of geometric regularity that supports consistent and sharp segmentations, especially at object boundaries.
</div>
</div>


<div class="paper-box"><div class="paper-box-image"><div><div class="badge">CVPR 2020</div><img src="images/FGN.png" alt="sym" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

[Fgn: Fully guided network for few-shot instance segmentation](https://openaccess.thecvf.com/content_CVPR_2020/papers/Fan_FGN_Fully_Guided_Network_for_Few-Shot_Instance_Segmentation_CVPR_2020_paper.pdf)

Zhibo Fan, Jin-Gang Yu, **Zhihao Liang**, Jiarong Ou, Changxin Gao, Gui-Song Xia, Yuanqing Li

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=oQpAzREAAAAJ&citation_for_view=oQpAzREAAAAJ:2osOgNQ5qMEC)
- We propose the Fully Guided Network, a novel framework for few-shot instance segmentation.
</div>
</div>


# 📖 Educations
- *2021.09 - Now*, Ph.D., South China University of Technology, Guangzhou.
- *2020.09 - 2021.04*, Master, South China University of Technology, Guangzhou.
- *2016.09 - 2020.06*, Undergraduate, South China University of Technology, Guangzhou.
