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

I am currently a Ph.D. at [South China University of Technology (SCUT)](https://www.scut.edu.cn/en/), advised by [Prof. Kui Jia](http://kuijia.site/). I received my bachelor degree from the same university (i.e. SCUT) in 2020, and expect to obtain my Ph.D. degree in 2025. I am currently an intern at [Tencent AI Lab](https://ai.tencent.com/ailab/zh/index).

I mainly focus on **3D Computer Vision**. My current research interests include Computer Graphics, 3D Semantic Learning and Reconstruction. Recently, I am working on Multi-View Reconstruction.


<!-- # 🔥 News -->
<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications

<div class="paper-box"><div class="paper-box-image"><div><div class="badge">Arxiv 2024</div><img src="images/LetsTalk.png" alt="sym" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

[LetsTalk: Latent Diffusion Transformer for Talking Video Synthesis](https://arxiv.org/abs/2411.16748)

Haojie Zhang, **Zhihao Liang**, Ruibo Fu, Zhengqi Wen, Xuefei Liu, Chenxing Li, Jianhua Tao, Yaling Liang

[**Project**](https://zhang-haojie.github.io/project-pages/letstalk.html) | [**Code**](https://github.com/zhang-haojie/letstalk)
- Portrait image animation using audio has rapidly advanced, enabling the creation of increasingly realistic and expressive animated faces. The challenges of this multimodality-guided video generation task involve fusing various modalities while ensuring consistency in timing and portrait. We further seek to produce vivid talking heads. To address these challenges, we present LetsTalk (LatEnt Diffusion TranSformer for Talking Video Synthesis), a diffusion transformer that incorporates modular temporal and spatial attention mechanisms to merge multimodality and enhance spatial-temporal consistency. To handle multimodal conditions, we first summarize three fusion schemes, ranging from shallow to deep fusion compactness, and thoroughly explore their impact and applicability. Then we propose a suitable solution according to the modality differences of image, audio, and video generation. For portrait, we utilize a deep fusion scheme (Symbiotic Fusion) to ensure portrait consistency. For audio, we implement a shallow fusion scheme (Direct Fusion) to achieve audio-animation alignment while preserving diversity. Our extensive experiments demonstrate that our approach generates temporally coherent and realistic videos with enhanced diversity and liveliness.
</div>
</div>

<div class="paper-box"><div class="paper-box-image"><div><div class="badge">Arxiv 2024</div><img src="images/GUS-IR.png" alt="sym" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

[GUS-IR: Gaussian Splatting with Unified Shading for Inverse Rendering](https://arxiv.org/abs/2411.07478)

**Zhihao Liang**, Hongdong Li, Kui Jia, Kailing Guo, Qi Zhang

[**Project**](https://arxiv.org/abs/2411.07478)
- Recovering the intrinsic physical attributes of a scene from images, generally termed as the inverse rendering problem, has been a central and challenging task in computer vision and computer graphics. In this paper, we present GUS-IR, a novel framework designed to address the inverse rendering problem for complicated scenes featuring rough and glossy surfaces. This paper starts by analyzing and comparing two prominent shading techniques popularly used for inverse rendering, forward shading and deferred shading, effectiveness in handling complex materials. More importantly, we propose a unified shading solution that combines the advantages of both techniques for better decomposition. In addition, we analyze the normal modeling in 3D Gaussian Splatting (3DGS) and utilize the shortest axis as normal for each particle in GUS-IR, along with a depth-related regularization, resulting in improved geometric representation and better shape reconstruction. Furthermore, we enhance the probe-based baking scheme proposed by GS-IR to achieve more accurate ambient occlusion modeling to better handle indirect illumination. Extensive experiments have demonstrated the superior performance of GUS-IR in achieving precise intrinsic decomposition and geometric representation, supporting many downstream tasks (such as relighting, retouching) in computer vision, graphics, and extended reality.
</div>
</div>

<div class="paper-box"><div class="paper-box-image"><div><div class="badge">ECCV 2024 (Oral)</div><img src="images/analytic-splatting.png" alt="sym" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

[Analytic-Splatting: Anti-Aliased 3D Gaussian Splatting via Analytic Integration](https://arxiv.org/abs/2403.11056)

**Zhihao Liang**, Qi Zhang, Wenbo Hu, Lei Zhu, Ying Feng, Kui Jia

[**Project**](https://lzhnb.github.io/project-pages/analytic-splatting) | [**Code**](https://github.com/lzhnb/Analytic-Splatting)
- In this paper, we derive an analytical solution to address the aliasing caused by discrete sampling in 3DGS. More specifically, we use a conditioned logistic function as the analytic approximation of the cumulative distribution function (CDF) in a one-dimensional Gaussian signal and calculate the Gaussian integral by subtracting the CDFs. We then introduce this approximation in the two-dimensional pixel shading, and present Analytic-Splatting, which analytically approximates the Gaussian integral within the 2D-pixel window area to better capture the intensity response of each pixel. Moreover, we use the approximated response of the pixel window integral area to participate in the transmittance calculation of volume rendering, making Analytic-Splatting sensitive to the changes in pixel footprint at different resolutions.
</div>
</div>

<div class="paper-box"><div class="paper-box-image"><div><div class="badge">Arxiv 2024</div><img src="images/GS-ID.png" alt="sym" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

[GS-ID: Illumination Decomposition on Gaussian Splatting via Diffusion Prior and Parametric Light Source Optimization](https://arxiv.org/abs/2408.08524)

Kang Du, **Zhihao Liang**, Zeyu Wang

[**Project**](https://kangdu.top/gsid/) | [**Code**](https://github.com/dukang/GS-ID.)
- We present GS-ID, a novel framework for illumination decomposition on Gaussian Splatting, achieving photorealistic novel view synthesis and intuitive light editing. In this work, we first introduce intrinsic diffusion priors to estimate the attributes for physically based rendering. Then we divide the illumination into environmental and direct components for joint optimization. Last, we employ deferred rendering to reduce the computational load. Our framework uses a learnable environment map and Spherical Gaussians (SGs) to represent light sources parametrically, therefore enabling controllable and photorealistic relighting on Gaussian Splatting.
</div>
</div>

<div class="paper-box"><div class="paper-box-image"><div><div class="badge">arXiv 2024</div><img src="images/3DGen-survey.png" alt="sym" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

[Advances in 3D Generation: A Survey](https://arxiv.org/abs/2401.17807)

Xiaoyu Li, Qi Zhang, Di Kang, Weihao Cheng, Yiming Gao, Jingbo Zhang, **Zhihao Liang**, Jing Liao, Yan-Pei Cao, Ying Shan

[**Project**](https://arxiv.org/abs/2401.17807)
- In this survey, we aim to introduce the fundamental methodologies of 3D generation methods and establish a structured roadmap, encompassing 3D representation, generation methods, datasets, and corresponding applications. We hope this survey will help readers explore this exciting topic and foster further advancements in the field of 3D content generation.
</div>
</div>

<div class="paper-box"><div class="paper-box-image"><div><div class="badge">ECCV 2024</div><img src="images/sur2f.png" alt="sym" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

[Sur2f: A Hybrid Representation for High-Quality and Efficient Surface Reconstruction from Multi-view Images](https://arxiv.org/abs/2401.03704)

Zhangjin Huang\*, **Zhihao Liang\***, Haojie Zhang, Yangkai Lin, Kui Jia

[**Project**](https://huang-zhangjin.github.io/project-pages/sur2f.html) | [**Code**](https://huang-zhangjin.github.io/project-pages/comming_soom.html)
- We propose a new hybrid representation, termed Sur2f, that can enjoy the benefits of both explicit and implicit surface representations. This is achieved by learning two parallel streams of an implicit SDF and an explicit surrogate surface mesh, both of which, by rendering, receive supervision from multi-view image observations.
</div>
</div>

<div class="paper-box"><div class="paper-box-image"><div><div class="badge">CVPR 2024</div><img src="images/gs-ir.png" alt="sym" width="100%"></div></div>
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
- *2021.09 - Present*, Ph.D., South China University of Technology, Guangzhou.
- *2020.09 - 2021.04*, Master, South China University of Technology, Guangzhou.
- *2016.09 - 2020.06*, Undergraduate, South China University of Technology, Guangzhou.
