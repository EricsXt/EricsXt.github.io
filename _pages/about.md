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

I am a first-year Ph.D. student at [XLANG Lab](https://xlang.ai/), The University of Hong Kong, advised by [Prof. Tao Yu](https://taoyds.github.io/). I am also a research intern with the World Action Model Team at [X Square Robot](https://x2robot.com/en). My research interests focus on <span style="color:red">Embodied AI, particularly Vision-Language-Action Models (VLAs) and World Action Models (WAMs)</span>. I received my B.S. in [Computer Science and Technology](http://www.cs.zju.edu.cn/) from Zhejiang University, where I was fortunate to be advised by [Prof. Zhou Zhao](https://scholar.google.com/citations?hl=zh-CN&user=IIoFY90AAAAJ). If you are interested in my work or would like to discuss related topics, please feel free to contact me via [email](mailto:xintonghu.erics@gmail.com).




<span class='anchor' id='news'></span>

# 🔥 News
- *2026.06*: &nbsp; 🎉🎉 "FineVLA: Fine-Grained Instruction Alignment for Steerable Vision-Language-Action Policies" is released on arXiv.
- *2026.05*: &nbsp; 🎉🎉 "Qwen-VLA: Unifying Vision-Language-Action Modeling across Tasks, Environments, and Robot Embodiments" is released on arXiv.
- *2025.09*: &nbsp; 🎉🎉 "MRSAudio: A Large-Scale Multimodal Recorded Spatial Audio Dataset with Refined Annotations" is accepted by NeurIPS2025.
- *2025.09*: &nbsp; 🎉🎉 "Tree of Preferences for Diversified Recommendation" is accepted by NeurIPS2025.
<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<span class='anchor' id='publications'></span>

# 📝 Publications 


<!-- paper: FineVLA -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Preprint 2026</div>
      <img src='images/FineVLA-main.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
  [FineVLA: Fine-Grained Instruction Alignment for Steerable Vision-Language-Action Policies](https://arxiv.org/abs/2605.27284)

  **Xintong Hu**<sup>*</sup>, Xuhong Huang<sup>*</sup>, Jinyu Zhang, Yutong Yao, Yuchong Sun, Qiuyue Wang, Mingsheng Li, Sicheng Xie, Yitao Liu, Junhao Chen, Yixuan Chen, Yingming Zheng, Shuai Bai, Tao Yu

  [🌐 **Project Page**](https://finevla.xlang.ai/)
  [<i class="fab fa-github" style="font-size: 20px; margin-right: 5px;"></i>**Code**](https://github.com/xlang-ai/FineVLA) <img src="https://img.shields.io/github/stars/xlang-ai/FineVLA?style=social" alt="GitHub stars" style="vertical-align: middle; margin-left: 5px;">
  [<img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" alt="huggingface" width="20px" style="vertical-align: middle; margin-right: 5px;"> **RoboFine-VLM**](https://huggingface.co/xlangai/RoboFine-VLM-397B-A17B)
  [<img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" alt="huggingface" width="20px" style="vertical-align: middle; margin-right: 5px;"> **Benchmark**](https://huggingface.co/datasets/xlangai/RoboFine-bench)

  An open framework for fine-grained VLA supervision, including: (1) **FineVLA-Data And Pipeline** that unifies 972K trajectories from 10 robot datasets into 47K human-verified fine-grained trajectories; (2) **RoboFine-Bench**, a 500-video benchmark with 10K+ atomic facts and 1K VQA questions; (3) **RoboFine-VLM**, a robotics-specialized VLM annotator for scalable trajectory annotation; (4) **FineVLA-Policy**, a steerable VLA policy achieving 86.8%/82.5% in RoboTwin and 62.7/100 in real-world dual-arm manipulation.
  </div>
</div>


<!-- paper: Qwen-VLA -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Preprint 2026</div>
      <img src='images/qwen-vla-main.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
  [Qwen-VLA: Unifying Vision-Language-Action Modeling across Tasks, Environments, and Robot Embodiments](https://arxiv.org/abs/2605.30280)

  Qwen Team (**Xintong Hu** is a **core contributor**)

  [<i class="fab fa-github" style="font-size: 20px; margin-right: 5px;"></i>**Code**](https://github.com/QwenLM/Qwen-VLA) <img src="https://img.shields.io/github/stars/QwenLM/Qwen-VLA?style=social" alt="GitHub stars" style="vertical-align: middle; margin-left: 5px;">
  [🌐 **Project Page**](https://qwen.ai/blog?id=qwenvla)

  - A unified embodied foundation model extending Qwen's VL stack to action and trajectory generation via a DiT-based decoder, unifying manipulation, navigation, and trajectory prediction.
  <br>
  - Achieves 97.9% on LIBERO, 86.1%/87.2% on RoboTwin, 69.0% OSR on R2R, 76.9% OOD success on real-world ALOHA.
  </div>
</div>


<!-- paper1 ： MRSAudio  -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">NeurIPS 2025 Poster</div>
      <img src='images/MRSAudio.jpg' alt="sym" width="100%" style="margin-bottom: 10px;">
      <img src='images/MRSAudio-2.jpg' alt="sym" width="100%">
      </div>
    </div>
  <div class='paper-box-text' markdown="1">
  [MRSAudio: A Large-Scale Multimodal Recorded Spatial Audio Dataset with Refined Annotations](https://openreview.net/forum?id=p2pRiDwjDa&noteId=TmGqB9RN30)

  Wenxiang Guo<sup>*</sup>, Changhao Pan<sup>*</sup>, Zhiyuan Zhu<sup>*</sup>, **Xintong Hu**<sup>*</sup>, Yu Zhang<sup>*</sup>, Li Tang, Rui Yang, Han Wang, Zongbao Zhang, Yuhan Wang, Yixuan Chen, Hankun Xu, Ke Xu, Pengfei Fan, Zhetao Chen, Yanhao Yu, Qiange Huang, Fei Wu, Zhou Zhao<sup>†</sup>


  [<img src='images/MRSAudio-headImage.jpg' alt="demo" width="20px" style="vertical-align: middle; margin-right: 5px;"> **DemoPage**](https://mrsaudio.github.io/index.html) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
  [<i class="fab fa-github" style="font-size: 20px; margin-right: 5px;"></i>**Code**](https://github.com/MRSAudio/MRSAudio_Main) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
  [<img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" alt="huggingface" width="20px" style="vertical-align: middle; margin-right: 5px;"> **Dataset**](https://huggingface.co/datasets/verstar/MRSAudio) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>


  -Datasets: Establish MRSAudio, a 500-hour multimodal spatial audio dataset with ambisonic audio, synchronized video, motion trajectories, and fine-grained annotations (transcripts, lyrics, scores), covering 4 real-world scenarios (daily life/speech/singing/music).
  <br>
  -Benchmark: Unified benchmark for 5 spatial audio tasks (spatialization, text-to-speech, singing synthesis, music generation, sound localization) enabling 3D-aware audio modeling.
  </div>
</div>



<!-- paper2 ： Tree of Preference  -->
<div class='paper-box'>
  <div class='paper-box-image'><div><div class="badge">NeurIPS 2025 Poster</div><img src='images/Tree_of_preference.jpg' alt="sym" width="100%"></div></div>
  <div class='paper-box-text' markdown="1">

  [Tree of Preferences for Diversified Recommendation](https://openreview.net/forum?id=KlZUwDP0pR&noteId=vB7YeUWlGH)

  Hanyang Yuan,Ning Tang, Tongya Zheng, Jiarong Xu, **Xintong Hu**, Renhong Huang, Shunyu Liu, Jiacong Hu, Jiawei Chen, Mingli Song<sup>†</sup>

  [<i class="fab fa-github" style="font-size: 20px; margin-right: 5px;"></i>**Code**](https://anonymous.4open.science/r/TPRec-7047/README.md) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

  -Abstract: With the help of the agent, complete the user information to improve the diversity of recommendations. Use Agent to help solve the Filter Bubble problem in traditional recommendation algorithms.
  </div>
</div>


<span class='anchor' id='projects'></span>

# 🛠 Projects

<div class="project-entry">
  <div class="project-entry__visual">
    <img src="images/qwen-logo.png" alt="Qwen logo">
  </div>
  <div class="project-entry__content" markdown="1">
  **Verifiable Coding Data and Rollout Pipeline for [Qwen3.8 / Qwen3.9](https://qwen.ai/blog?id=qwen3.8)**
  </div>
  <details class="project-details">
    <summary>Details</summary>
    <figure class="project-details__figure">
      <img src="images/qwen-coding-pipeline.png" alt="Pipeline from real IDE logs to test-grounded SFT data" loading="lazy" decoding="async">
    </figure>
    <p>Contributed to Qwen3.8 and Qwen3.9 by designing and building an end-to-end pipeline that transforms real-world IDE assistant interaction logs into reproducible and verifiable coding tasks for model training. The pipeline mines challenging multi-turn cases, reconstructs paired buggy and resolved repository states, generates executable test patches, and validates them through a bidirectional test gate that must fail on the buggy state and pass on the resolved state. It further applies anti-overfitting checks, builds reproducible containerized environments, and evaluates model rollouts with hidden tests to produce reliable accept/reject-labeled multimodal SFT trajectories.</p>
  </details>
</div>


<span class='anchor' id='honors-and-awards'></span>

# 🎖 Honors and Awards
- *2025.10* **National Scholarship(Top 1%)**.
- *2024.10* **National Scholarship(Top 1%)**.
- *2025.06* 2025 IEEE ASRU AudioMos Challenge **Second Prize**.
- *2024.11* Zhejiang Province "Shangde Scholar" Award (Single Recipient).
- *2024.11* Zhejiang University CS ”Campus Star” Honor (Top 10 Students).
- *2025.09* Zhejiang University First-Class Scholarship (Top 3%).
- *2024.09* Zhejiang University First-Class Scholarship(Top 3%).
<!-- - *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<span class='anchor' id='educations'></span>

# 📖 Education

<div class="institution-entry">
  <div class="institution-entry__content">
    <em>2026.09 - Present</em>, <em>Ph.D.</em>, The University of Hong Kong, School of Computer and Data Science.
  </div>
  <div class="institution-entry__logo institution-entry__logo--seal">
    <img src="images/hku-logo.png" alt="The University of Hong Kong logo">
  </div>
</div>

<div class="institution-entry">
  <div class="institution-entry__content">
    <em>2022.09 - 2026.06</em>, <em>B.S.</em>, Zhejiang University, School of Computer Science and Technology.
  </div>
  <div class="institution-entry__logo institution-entry__logo--seal">
    <img src="images/zju-logo.png" alt="Zhejiang University logo">
  </div>
</div>
<!-- - *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<span class='anchor' id='internships'></span>

# 💻 Internships

<div class="institution-entry">
  <div class="institution-entry__content" markdown="1">
**World Action Model Team, [X Square Robot](https://x2robot.com/en)**<br>
*Research Intern* (09/2026 -- Present)<br>
Advisor: [Xiaofan Li](https://shalfun.github.io/)<br>
Research Topic: **World Action Models (WAMs)**
  </div>
  <a class="institution-entry__logo" href="https://x2robot.com/en" aria-label="Visit X Square Robot">
    <img src="images/x-square-robot-logo.png" alt="X Square Robot logo">
  </a>
</div>

<div class="institution-entry">
  <div class="institution-entry__content" markdown="1">
**Alibaba Group, [Qwen-VL Team](https://github.com/QwenLM/Qwen-VL)**<br>
*Research Intern* (01/2026 -- 09/2026)<br>
Advisor: [Shuai Bai](https://shuaibai623.github.io/)<br>
Research Topic: **Vision-Language-Action (VLA)**
  </div>
  <div class="institution-entry__logo institution-entry__logo--qwen">
    <img src="images/qwen-logo.png" alt="Qwen logo">
  </div>
</div>

<hr>
<div class="page__meta" style="text-align: right;">
  <p>Last updated: September 11, 2026</p>
</div>
