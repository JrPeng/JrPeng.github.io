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

# 🎓 About Me
I am currently an Associate Professor in the [School of Computer and Communication Engineering](https://scce.ustb.edu.cn/), [University of Science and Technology Beijing](https://www.ustb.edu.cn/). My research interests focus on 3D generative AI and Embodied AI, including motion capture & synthesis, 3D reconstruction, 3D scene generation, computer graphics,  image/video generation and robotics. 
Before I joined USTB, I obtained my B.E. and Ph.D. degrees from [Tsinghua University](https://www.tsinghua.edu.cn/en/), and [Institute of Automation](https://english.ia.cas.cn/)，[Chinese Academy of Sciences](https://english.cas.cn/), under the supervision of [Prof. Tieniu Tan](https://people.ucas.ac.cn/~0009513) and [Prof. Zhaoxiang Zhang](https://zhaoxiangzhang.net/). After that I joined Huawei and deeply cooperate with [Lingxi Xie](http://lingxixie.com/Home.html) under the supervision of [Prof. Qi Tian](https://www.qitian1987.com/). After that I have founded a startup Cheery.AI for a while. Now I'm in deep cooperation with [Prof. Zhaoxiang Zhang](https://zhaoxiangzhang.net/) in [Institute of Automation](https://english.ia.cas.cn/)，[Chinese Academy of Sciences](https://english.cas.cn/) and [Prof. Xucheng Yin]([https://zhaoxiangzhang.net/](https://enscce.ustb.edu.cn/About/Current/2020-05-27/44.html)) in USTB. 

# 🔈 Join Us
If you are interested in our projects on 3D vision, generative AI, or embodied AI, please feel free to contact me for potential collaboration or exchange. You can reach out via email or WeChat.

随时欢迎对三维视觉、生成式人工智能、具身智能、LLM感兴趣的老师/研究生/本科生/实习生通过[jrpeng4ever@126.com](jrpeng4ever@126.com)联系合作、交流


# 🔥 News
- *2024.12*: &nbsp; One paper(SceneX) accepted by AAAI 2024.
- *2024.10*: &nbsp; One paper accepted by NeurIPS 2024 D&B.
- *2024.08*: &nbsp; One paper accepted by ACL 2024 Findings.
- *2024.07*: &nbsp; Two papers accepted by ACM MM 2024 as oral representations. 
- *2024.07*: &nbsp; One paper accepted by ECCV 2024. 
- *2024.07*: &nbsp; One paper accepted by TPAMI 2024. 
- *2024.02*: &nbsp; One paper accepted by CVPR 2024.


# 📝 Selected Publications
<div class='paper-box'><div class='paper-box-image'><div><img src='images/SceneX.png' width="190" height="90"></div></div>
<div class='paper-box-text' markdown="1"> 
**2.SceneX: Procedural Controllable Large-scale Scene Generation via Large-language Models**
[[Paper](https://arxiv.org/pdf/2403.15698)]
[[Project](https://scenex-lab.github.io/)]

Mengqi Zhou, Yuxi Wang, Jun Hou, Chuanchen Luo, Zhaoxiang Zhang, **Junran Peng†**

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS Dataset 2024</div><img src='images/roleagent.png' width="190" height="90"></div></div>
<div class='paper-box-text' markdown="1"> 
**RoleAgent: Building, Interacting, and Benchmarking High-quality Role-Playing Agents from Scripts**

Jiaheng Liu, Zehao Ni, Haoran Que, Tao Sun, Zekun Wang, Jian Yang, Jiakai Wang, Hongcheng Guo, Zhongyuan Peng, Ge Zhang, Jiayi Tian, Xingyuan Bu, Ke Xu, Wenge Rong, **Junran Peng**, Zhaoxiang Zhang

NeurIPS Dataset and Benchmark Track 2024

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024 Findings</div><img src='images/rolellm.png' width="190" height="90"></div></div>
<div class='paper-box-text' markdown="1"> 
**RoleLLM: Benchmarking, Eliciting, and Enhancing Role-Playing Abilities of Large Language Models**
[[Paper](https://arxiv.org/abs/2310.00746)]
[[Code](https://github.com/InteractiveNLP-Team/RoleLLM-public)]

Zekun Moore Wang\*, Zhongyuan Peng\*, Haoran Que\*, Jiaheng Liu, Wangchunshu Zhou, Yuhan Wu, Hongcheng Guo, Ruitong Gan, Zehao Ni, Jian Yang, Man Zhang, Zhaoxiang Zhang, Wanli Ouyang, Ke Xu, Stephen W. Huang, Jie Fu, **Junran Peng**

Findings of the Association for Computational Linguistics (**Findings of ACL**) 2024

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MM 2024</div><img src='images/stablemofusion.png' width="190" height="90"></div></div>
<div class='paper-box-text' markdown="1"> 
**StableMoFusion: Towards Robust and Efficient Diffusion-based Motion Generation Framework**
[[Paper](https://arxiv.org/abs/2405.05691)]
[[Code](https://github.com/h-y1heng/StableMoFusion)]

Yiheng Huang, Hui Yang, Chuanchen Luo, Yuxi Wang, Shibiao Xu, Zhaoxiang Zhang, Man Zhang†, **Junran Peng†**

ACM International Conference on Multimedia (**ACM MM**) 2024 **Oral**

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MM 2024</div><img src='images/material.gif' width="190" height="90"></div></div>
<div class='paper-box-text' markdown="1"> 
**MaterialSeg3D: Segmenting Dense Materials from 2D Priors for 3D Assets**
[[Paper](https://arxiv.org/abs/2404.13923)]
[[Project](https://materialseg3d.github.io/)]

Zeyu Li, Ruitong Gan, Chuanchen Luo, Yuxi Wang, Jiaheng Liu, Ziwei Zhu, Man Zhang, Qing Li, Xucheng Yin, Zhaoxiang Zhang, **Junran Peng**

ACM International Conference on Multimedia (**ACM MM**) 2024 **Oral**

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/citygs.gif' width="190" height="90"></div></div>
<div class='paper-box-text' markdown="1"> 
**CityGaussian: Real-time High-quality Large-Scale Scene Rendering with Gaussians**
[[Paper](https://arxiv.org/abs/2404.01133)]
[[Project](https://dekuliutesla.github.io/citygs/)]
[[Code](https://github.com/DekuLiuTesla/CityGaussian)]

Yang Liu, He Guan, Chuanchen Luo, Lue Fan, **Junran Peng†**, Zhaoxiang Zhang†

European Conference on Computer Vision (**ECCV**) 2024

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/hardmo.png' width="190" height="90"></div></div>
<div class='paper-box-text' markdown="1"> 
**HardMo: A Large-Scale Hardcase Dataset for Motion Capture**
[[Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Liao_HardMo_A_Large-Scale_Hardcase_Dataset_for_Motion_Capture_CVPR_2024_paper.pdf)]
[[Project](https://ljqnb.github.io/HardMo.github.io/)]

Jiaqi Liao\*, Chuanchen Luo\*, Yiheng Du, Yuxi Wang, Xucheng Yin, Man Zhang, Zhaoxiang Zhang†, **Junran Peng†**

IEEE/CVF Conference on Computer Vision and Pattern Recognition (**CVPR**) 2024

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/LTA-PCS.png' width="190" height="90"></div></div>
<div class='paper-box-text' markdown="1"> 
**LTA-PCS: Learnable Task-Agnostic Point Cloud Sampling**
[[Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Liu_LTA-PCS_Learnable_Task-Agnostic_Point_Cloud_Sampling_CVPR_2024_paper.pdf)]

JiahengLiu\∗, JianhaoLi\∗, KaisiyuanWang, HongchengGuo, JianYang1, **Junran Peng**, KeXu, XianglongLiu, JinyangGuo1†

IEEE/CVF Conference on Computer Vision and Pattern Recognition (**CVPR**) 2024

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2023</div><img src='images/Large-Scale.png' width="190" height="90"></div></div>
<div class='paper-box-text' markdown="1"> 
**Large-Scale Object Detection in the Wild from Imbalanced Multi-Labels**
[[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10579784)]

CongPan\∗, **JunranPeng\∗**, XingyuanBu, ZhaoxiangZhang

IEEE Transactions on Pattern Analysis and Machine Intelligence (**TPAMI**) 2023

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/Logformer.png' width="190" height="90"></div></div>
<div class='paper-box-text' markdown="1"> 
**Logformer: A pre-train and tuning pipeline for log anomaly detection**
[[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/27764)]

Hongcheng Guo, Jian Yang, Jiaheng Liu, Jiaqi Bai, Boyang Wang, Zhoujun Li, Tieqiao Zheng, Bo Zhang, **Junran Peng**, Qi Tian

Proceedings of the AAAI Conference on Artificial Intelligence (**AAAI**) 2024

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2023</div><img src='images/GAIA.png' width="190" height="90"></div></div>
<div class='paper-box-text' markdown="1"> 
**GAIA-Universe: Everything is Super-Netify**
[[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10125046)]
[[Code](https://github.com/GAIA-vision)]

**Junran Peng**, Qing Chang, Haoran Yin, Xingyuan Bu, Jiajun Sun, Lingxi Xie, Xiaopeng Zhang, Qi Tian, Zhaoxiang Zhang

IEEE Transactions on Pattern Analysis and Machine Intelligence（**TPAMI**）2023

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/BAEFormer.png' width="190" height="90"></div></div>
<div class='paper-box-text' markdown="1"> 
**BAEFormer: Bi-Directional and Early Interaction Transformers for Bird's Eye View Semantic Segmentation**
[[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Pan_BAEFormer_Bi-Directional_and_Early_Interaction_Transformers_for_Birds_Eye_View_CVPR_2023_paper.pdf)]

Cong Pan, Yonghao He, **Junran Peng**, Qian Zhang, Wei Sui, Zhaoxiang Zhang

IEEE/CVF Conference on Computer Vision and Pattern Recognition (**CVPR**) 2023

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/DATA.png' width="190" height="90"></div></div>
<div class='paper-box-text' markdown="1"> 
**DATA: Domain-aware and task-aware self-supervised learning**
[[Paper](https://arxiv.org/pdf/2203.09041)]

Qing Chang, **Junran Peng**, Lingxie Xie, Jiajun Sun, Haoran Yin, Qi Tian, Zhaoxiang Zhang

IEEE/CVF Conference on Computer Vision and Pattern Recognition (**CVPR**) 2023

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCV 2022</div><img src='images/Delving.png' width="190" height="90"></div></div>
<div class='paper-box-text' markdown="1"> 
**Delving into the effectiveness of receptive fields: Learning scale-transferrable architectures for practical object detection**
[[Paper](https://link.springer.com/article/10.1007/s11263-021-01573-6)]

Zhaoxiang Zhang, Cong Pan, **Junran Peng**

International Journal of Computer Vision (**IJCV**) 2022

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2021</div><img src='images/Uncertainty-aware.png' width="190" height="90"></div></div>
<div class='paper-box-text' markdown="1"> 
**Uncertainty-aware pseudo label refinery for domain adaptive semantic segmentation**
[[Paper](http://openaccess.thecvf.com/content/ICCV2021/papers/Wang_Uncertainty-Aware_Pseudo_Label_Refinery_for_Domain_Adaptive_Semantic_Segmentation_ICCV_2021_paper.pdf)]

Yuxi Wang, **Junran Peng**, ZhaoXiang Zhang

IEEE/CVF International Conference on Computer Vision (**ICCV**) 2021

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2021</div><img src='images/Gaia.png' width="190" height="90"></div></div>
<div class='paper-box-text' markdown="1"> 
**Gaia: A transfer learning system of object detection that fits your needs**
[[Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Bu_GAIA_A_Transfer_Learning_System_of_Object_Detection_That_Fits_CVPR_2021_paper.pdf)]

Xingyuan Bu, **Junran Peng**, Junjie Yan, Tieniu Tan, Zhaoxiang Zhang

IEEE/CVF Conference on Computer Vision and Pattern Recognition (**CVPR**) 2021

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2020</div><img src='images/Large-scale.png' width="190" height="90"></div></div>
<div class='paper-box-text' markdown="1"> 
**Large-scale object detection in the wild from imbalanced multi-labels**
[[Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Peng_Large-Scale_Object_Detection_in_the_Wild_From_Imbalanced_Multi-Labels_CVPR_2020_paper.pdf)]

**Junran Peng**, Xingyuan Bu, Ming Sun, Zhaoxiang Zhang, Tieniu Tan, Junjie Yan

IEEE/CVF Conference on Computer Vision and Pattern Recognition (**CVPR**) 2020

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2019</div><img src='images/Efficient.png' width="190" height="90"></div></div>
<div class='paper-box-text' markdown="1"> 
**Efficient neural architecture transformation search in channel-level for object detection**
[[Paper](https://arxiv.org/pdf/1909.02293)]

**Junran Peng**, Ming Sun, Zhaoxiang Zhang, Tieniu Tan, Junjie Yan

Neural Information Processing Systems (**NeurIPS**) 2019

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2019</div><img src='images/POD.png' width="190" height="90"></div></div>
<div class='paper-box-text' markdown="1"> 
**POD: Practical object detection with scale-sensitive network**
[[Paper](http://openaccess.thecvf.com/content_ICCV_2019/papers/Peng_POD_Practical_Object_Detection_With_Scale-Sensitive_Network_ICCV_2019_paper.pdf)]

**Junran Peng**, Ming Sun, Zhaoxiang Zhang, Tieniu Tan, Junjie Yan

IEEE/CVF International Conference on Computer Vision (**ICCV**) 2019


</div>
</div>


# 📄 Pre-Prints 

<div class='paper-box'><div class='paper-box-image'><div><img src='images/CityX.png' width="190" height="90"></div></div>
<div class='paper-box-text' markdown="1"> 
**1.CityX: Controllable Procedural Content Generation for Unbounded 3D Cities**
[[Paper](https://arxiv.org/pdf/2407.17572)]
[[Project](https://cityx-lab.github.io/)]
[[Github](GitHub - cityx-lab/CityX-Lab)]

Shougao Zhang, Mengqi Zhou, Yuxi Wang*, Chuanchen Luo, Rongyu Wang, Yiwei Li, Xucheng Yin, Zhaoxiang Zhang†, **Junran Peng†**

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/Seek.png' width="190" height="90"></div></div>
<div class='paper-box-text' markdown="1"> 
**Seek for Incantations: Towards Accurate Text-to-Image Diffusion Synthesis through Prompt Engineering**
[[Paper](https://arxiv.org/pdf/2401.06345)]

Chang Yu, **Junran Peng**, Xiangyu Zhu, Zhaoxiang Zhang, Qi Tian, Zhen Lei

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/FurniScene.png' width="190" height="90"></div></div>
<div class='paper-box-text' markdown="1"> 
**FurniScene: A Large-scale 3D Room Dataset with Intricate Furnishing Scenes pre-print**
[[Paper](https://arxiv.org/pdf/2401.03470)]

Genghao Zhang, Yuxi Wang, Chuanchen Luo, Shibiao Xu, Zhaoxiang Zhang, Man Zhang, **Junran Peng**

</div>
</div>


# 📖 Experiences
* Associate Professor in the [School of Computer and Communication Engineering](https://enscce.ustb.edu.cn/), [University of Science and Technology Beijing](https://www.ustb.edu.cn/)  
  Date: 2024.09 ~ (now)

* CEO of Cheery.AI
  Date: 2023.07 ~ 2024.07

* Lead Engineer in the Team PanGu, Huawei Cloud.  
  Date: 2021.01 ~ 2023.07  
  Leader: Prof. [Qi Tian](https://www.qitian1987.com/).
  
* Ph.D in the [Institute of Automation](http://www.ia.cas.cn/), [Chinese Academy of Sciences](https://www.ucas.ac.cn/)  
  Date: 2015.09 ~ 2020.07  
  Supervisor: Prof. [Tieniu Tan](https://people.ucas.ac.cn/~0009513) and Prof. [Zhaoxiang Zhang (张兆翔)](https://zhaoxiangzhang.net/).
  
* B.E. in the [Department of Computer Science and Technology](https://www.cs.tsinghua.edu.cn/csen/), [Tsinghua University](https://www.tsinghua.edu.cn/en/)
  Date: 2011.09 ~ 2015.07
