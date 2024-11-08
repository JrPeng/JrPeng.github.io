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
Before I joined USTB, I obtained my B.E. and Ph.D. degrees from [Tsinghua University](https://www.tsinghua.edu.cn/en/), and [Institute of Automation](https://english.ia.cas.cn/)，[Chinese Academy of Sciences](https://english.cas.cn/), under the supervision of [Prof. Tieniu Tan](https://people.ucas.ac.cn/~0009513) and [Prof. Zhaoxiang Zhang](https://zhaoxiangzhang.net/). After that I joined Huawei and deeply cooperate with [Lingxi Xie](http://lingxixie.com/Home.html) under the supervision of [Prof. Qi Tian](https://www.qitian1987.com/). After that I have founded a startup Cheery.AI for a while. Now I'm in deep cooperation with [Prof. Zhaoxiang Zhang](https://zhaoxiangzhang.net/) in [Institute of Automation](https://english.ia.cas.cn/)，[Chinese Academy of Sciences](https://english.cas.cn/). I also collaberate closely with [Prof.Jiaheng Liu] in Nanjing University and [Prof. Chuanchen Luo](https://luckydc.github.io/) in Shandong University.

# 🔈 Join Us
If you are interested in our projects on 3D vision, generative AI, or embodied AI, please feel free to contact me for potential collaboration or exchange. You can reach out via email or WeChat.

随时欢迎对三维视觉、生成式人工智能、具身智能感兴趣的老师/研究生/本科生/实习生通过[jrpeng4ever@126.com](jrpeng4ever@126.com)联系合作、交流


# 🔥 News
- *2024.10*: &nbsp; One paper accepted by NeurIPS 2024 D&B.
- *2024.08*: &nbsp; One paper accepted by ACL 2024 Findings.
- *2024.07*: &nbsp; Two papers accepted by ACM MM 2024 as oral representations. 
- *2024.07*: &nbsp; One paper accepted by ECCV 2024. 
- *2024.07*: &nbsp; One paper accepted by TPAMI 2024. 
- *2024.02*: &nbsp; One paper accepted by CVPR 2024.


# 📝 Selected Publications

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


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE/CAA JAS 2024</div><img src='images/Depth-Guided.png' width="190" height="90"></div></div>
<div class='paper-box-text' markdown="1"> 
**Depth-Guided Vision Transformer With Normalizing Flows for Monocular 3D Object Detection*
[[Paper](https://www.ieee-jas.net/article/doi/10.1109/JAS.2023.123660)]

Cong Pan, **Junran Peng**, Zhaoxiang Zhang

5.IEEE/CAA Journal of Automatica Sinica (**IEEE/CAA JAS**)2024

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

<div class='paper-box'><div class='paper-box-image'><div><img src='images/SceneX.png' width="190" height="90"></div></div>
<div class='paper-box-text' markdown="1"> 
**2.SceneX: Procedural Controllable Large-scale Scene Generation via Large-language Models **
[[Paper](https://arxiv.org/pdf/2403.15698)]
[[Project](https://scenex-lab.github.io/)]

Mengqi Zhou, Yuxi Wang, Jun Hou, Chuanchen Luo, Zhaoxiang Zhang, **Junran Peng†**

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
  
* Ph.D in the [Institute of Automation](http://www.ia.cas.cn/), [Chinese Academy of Sciences](https://www.ucas.ac.cn/)  
  Date: 2015.09 ~ 2020.07  
  Supervisor: Prof. [Tieniu Tan](https://people.ucas.ac.cn/~0009513) and Prof. [Zhaoxiang Zhang (张兆翔)](https://zhaoxiangzhang.net/).
  
* B.E. in the [Department of Computer Science and Technology](https://www.cs.tsinghua.edu.cn/csen/), [Tsinghua University](https://www.tsinghua.edu.cn/en/)
  Date: 2011.09 ~ 2015.07
