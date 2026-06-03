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

I am currently a second-year PhD student at the State Key Laboratory of Brain-Machine Intelligence, College of Computer Science and Technology, Zhejiang University under the supervision of  [Asst. Prof. Sha Zhao](http://www.shazhao.net/) and [Prof. Gang Pan](https://person.zju.edu.cn/gpan).

I earned my bachelor's degree in Information Engineering from the Sino-European Engineering School, Shanghai University.

My research interests include EEG decoding, Brain-Computer Interfaces, Deep Learning, and Artificial Intelligence. I am currently focusing on brain-inspired continual learning and continual brain decoding in real-world scenarios.

---

我目前是浙江大学脑机智能全国重点实验室的在读博士生，指导老师为[赵莎研究员](http://www.shazhao.net/)
和[潘纲教授](https://person.zju.edu.cn/gpan )。

我本科就读于上海大学中欧工程技术学院，获信息工程学士学位。

我的研究兴趣包括脑电信号解码、脑机接口、深度学习和人工智能。目前我正专注于研究基于脑启发的持续学习以及在现实场景的持续脑信号解码算法。

# 🔥 News
- *2026.04*: &nbsp;🎉 Our paper "_Tuning the Mind: Closed-loop Emotion Regulation via AIGC Music Driven by Wearable
  Multimodal Neurofeedback_" is accepted by **IEEE Transactions on Affective Computing**!
- *2026.01*: &nbsp;🎉 Our paper "_EEGDiffuser: Label-Guided EEG Signals Synthesis via Diffusion Model for BCI
  Applications_" is accepted by **Neurocomputing**!
- *2025.09*: &nbsp;🎉🎉 Our paper "_SPICED: A Synaptic Homeostasis-Inspired Framework for Unsupervised Continual EEG Decoding_" is accepted by **NeurIPS 2025**!
- *2025.07*: &nbsp;🎉 Our paper "_EEGMamba: An EEG Foundation Model with Mamba_" (**EEG Foundation
  Model 🤖**) is accepted by **Neural Networks**!
- *2025.07*: &nbsp;🎉 Our paper "_Wearable Music2Emotion : Assessing Emotions Induced by AI-Generated Music through
  Portable EEG-fNIRS Fusion_" is accepted by **ACMMM 2025**!
- *2025.01*: &nbsp;🎉🎉 Our paper "_CBraMod: A Criss-Cross Brain Foundation Model for EEG Decoding_" (**EEG Foundation
  Model 🤖**) is accepted by **ICLR 2025**!
- *2025.01*: &nbsp;🎉 Our paper "_BrainUICL: An Unsupervised Individual Continual Learning Framework for EEG
  Applications_" is accepted by **ICLR 2025**!
- *2024.12*: &nbsp;🎉 Our paper "_CareSleepNet: A Hybrid Deep Learning Network for Automatic Sleep Staging_" is
  published as a **Cover Article 🏆** in **IEEE Journal of Biomedical and Health Informatics (JBHI)**!
- *2024.12*: &nbsp;🎉 Our paper "_Personalized Sleep Staging Leveraging Source-Free Unsupervised Domain Adaptation_" is
  accepted by **AAAI 2025**!
- *2024.4*: &nbsp;🎉 Our paper "_Simplifying Multimodal with Single EOG Modality for Automatic Sleep Staging_" is published in **IEEE Transactions on Neural Systems and Rehabilitation Engineering (TNSRE)**!
- *2023.09*: &nbsp;🎉 Our paper "_Narcolepsy Diagnosis With Sleep Stage Features Using PSG Recordings_" is
  published in **IEEE Transactions on Neural Systems and Rehabilitation Engineering (TNSRE)**!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2026</div><img src='images/EvoBrain.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[EvoBrain: Continual Learning of EEG Foundation Models Across Heterogeneous BCI Tasks](http://arxiv.org/abs/2606.01767)

**Yangxuan Zhou**, Sha Zhao, Jiquan Wang, Shijian Li, Gang Pan

[![Paper](https://img.shields.io/badge/arXiv-2606.01767-red)](http://arxiv.org/abs/2606.01767)

- We propose **EvoBrain**, the first cross-task continual learning framework for pretrained EEG Foundation Models, which enables a single unified model to dynamically adapt across  heterogeneous EEG tasks and advances toward the **one-for-all objective for universal brain decoding.**
- EvoBrain introduces **Neuro-Spectral Task Normalization (NSN)** and **Response-Affinity Distillation (RAD)** to balance adaptation plasticity and memory stability, achieving consistent improvements across six EEG tasks and four mainstream foundation-model architectures, demonstrating strong architecture-agnostic generalization.
  
</div>
</div>
  
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/SPICED.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SPICED: A Synaptic Homeostasis-Inspired Framework for Unsupervised Continual EEG Decoding](https://neurips.cc/virtual/2025/poster/115851)

**Yangxuan Zhou**, Sha Zhao, Jiquan Wang, Haiteng Jiang, Shijian Li, Tao Li, Gang Pan

[![Paper](https://img.shields.io/badge/arXiv-2412.07236-red)](https://arxiv.org/pdf/2509.17439)
[![Paper](https://img.shields.io/badge/Paper-NeurIPS-008B8B)](https://neurips.cc/virtual/2025/poster/115851)
[![GitHub Repo stars](https://img.shields.io/github/stars/xiaobaben/SPICED)](https://github.com/xiaobaben/SPICED)

- This paper proposes a novel synaptic homeostasis inspired continual learning framework for EEG decoding in real-world scenarios.
- **The core contribution of SPICED** is the mechanistic translation of neurobiology into a computational continual learning framework.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/BrainUICL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[BrainUICL: An Unsupervised Individual Continual Learning Framework for EEG Applications](https://openreview.net/forum?id=6jjAYmppGQ)

**Yangxuan Zhou**, Sha Zhao, Jiquan Wang, Haiteng Jiang, Shijian Li, Tao Li, Gang Pan

[![Paper](https://img.shields.io/badge/Paper-ICLR-008B8B)](https://openreview.net/forum?id=6jjAYmppGQ)
[![GitHub Repo stars](https://img.shields.io/github/stars/xiaobaben/BrainUICL)](https://github.com/xiaobaben/BrainUICL)

- This paper proposes a novel unsupervised individual continual learning framework called **BrainUICL** for continual EEG decoding in real-world scenarios.
- **BrainUICL** achieves superior performance across up to **3 different downstream BCI datasets**, effectively balancing the **Stability-Plasticity dilemma** during the CL process

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/SF-UIDA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Personalized Sleep Staging Leveraging Source-Free Unsupervised Domain Adaptation](https://ojs.aaai.org/index.php/AAAI/article/view/33592)

**Yangxuan Zhou**, Sha Zhao, Jiquan Wang, Haiteng Jiang, Shijian Li, Benyan Luo, Tao Li, Gang Pan

[![Paper](https://img.shields.io/badge/Paper-AAAI-008B8B)](https://ojs.aaai.org/index.php/AAAI/article/view/33592)
[![GitHub Repo stars](https://img.shields.io/github/stars/xiaobaben/SF-UIDA)](https://github.com/xiaobaben/SF-UIDA)

- This paper proposes a novel source-free unsupervised individual domain adaptation framework called **SF-UIDA** for automatic personalized sleep staging in real-world scenarios.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/CBraMod.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CBraMod: A Criss-Cross Brain Foundation Model for EEG Decoding](https://openreview.net/forum?id=NPNUHgHF2w)

Jiquan Wang, Sha Zhao, Zhiling Luo, **Yangxuan Zhou**, Haiteng Jiang, Shijian Li, Tao Li, Gang Pan

[![Paper](https://img.shields.io/badge/arXiv-2412.07236-red)](https://arxiv.org/abs/2412.07236)
[![Paper](https://img.shields.io/badge/Paper-ICLR-008B8B)](https://openreview.net/forum?id=NPNUHgHF2w)
[![huggingface](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Models-FFD21E)](https://huggingface.co/weighting666/CBraMod)
[![GitHub Repo stars](https://img.shields.io/github/stars/wjq-learning/CBraMod)](https://github.com/wjq-learning/CBraMod)

- This paper proposes a novel **EEG Foundation Model 🤖** called **CBraMod**, with **criss-cross transformer** as the
  backbone and **ACPE** as the positional encodings.
- **CBraMod** achieves superior performance across up to **10 downstream BCI tasks with 12 public datasets**, proving
  its strong capability and generalizability.

</div>
</div>

---
- `TAFFC 2026` [Tuning the Mind: Closed-loop Emotion Regulation via AIGC Music Driven by Wearable Multimodal Neurofeedback](https://ieeexplore.ieee.org/document/11477097), Sha Zhao, Song Yi, **Yangxuan Zhou**, Jiadong Pan, Jiquan Wang, Jie Xia, Shijian Li, Shurong Dong, Gang Pan
- `Neurocomputing 2026` [EEGDiffuser: Label-Guided EEG Signals Synthesis via Diffusion Model for BCI Applications](https://www.sciencedirect.com/science/article/abs/pii/S0925231226000330), Jiquan Wang, Sha Zhao, Zhiling Luo, **Yangxuan Zhou**, Shijian Li, Gang Pan
- `NN 2025`[EEGMamba: An EEG Foundation Model with Mamba](https://www.sciencedirect.com/science/article/pii/S0893608025006963), Jiquan Wang, Sha Zhao, Zhiling Luo, **Yangxuan Zhou**, Shijian Li, Gang Pan
- `ACMMM 2025`[Wearable Music2Emotion : Assessing Emotions Induced by AI-Generated Music through
  Portable EEG-fNIRS Fusion](https://arxiv.org/abs/2508.04723), Sha Zhao, Song Yi, **Yangxuan Zhou**, Jiadong Pan, Jiquan Wang, Jie Xia, Shijian Li, Shurong Dong, Gang Pan
- `JBHI 2024` [CareSleepNet: A Hybrid Deep Learning Network for Automatic Sleep Staging](https://ieeexplore.ieee.org/document/10595067),
Jiquan Wang, Sha Zhao, **Yangxuan Zhou**, Haiteng Jiang, Zhenghe Yu, Tao Li, Shijian Li, Gang Pan
- `TNSRE 2024` [Simplifying Multimodal with Single EOG Modality for Automatic Sleep Staging](https://ieeexplore.ieee.org/document/10504925),
**Yangxuan Zhou**, Sha Zhao, Jiquan Wang, Haiteng Jiang, Zhenghe Yu, Shijian Li, Tao Li, Gang Pan
- `TNSRE 2023` [Narcolepsy Diagnosis With Sleep Stage Features Using PSG Recordings](https://ieeexplore.ieee.org/document/10242085),
Jiquan Wang, Sha Zhao, **Yangxuan Zhou**, Haiteng Jiang, Zhenghe Yu, Tao Li, Shijian Li, Gang Pan


<sup>**✉**</sup> denotes corresponding author and <sup>**#**</sup> denotes equal contribution.

# 📖 Educations
- *2022.09 -  (now)*, PhD candidate, Computer Science and Technology, Zhejiang University, Hanzhou, China.
- *2018.09 - 2022.06*, Undergraduate, Information Engineering, Sino-European Engineering School, Shanghai University, China.

