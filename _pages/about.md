---
permalink: /
title: "About me"
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
I am a first-year Master's student in Artificial Intelligence at Fudan University, under the supervision of Prof. Zhineng Chen in the FVL Lab. Previously, I received my bachelor's degree in Artificial Intelligence from Shanghai Jiao Tong University.

My research focuses on video generation and world models, especially on building **physics-consistent and controllable generative worlds**.

# 🔥 News
- *2026.01*: &nbsp;🎉🎉 One paper is accepted by ICLR 2026! 
- *2025.01*: &nbsp;🎉🎉 One paper is accepted by ICLR 2025! 


# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/sdf_teaser_figure.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Beyond Static Vision: Scene Dynamic Field Unlocks Intuitive Physics Understanding in Multi-modal Large Language Models](https://openreview.net/forum?id=Ax02eR2c3d)

Nanxi Li, Xiang Wang, **Yuanjie Chen**, Haode Zhang, Hong Li, Yong-Lu Li 

[**[Project website]**](https://iclr.cc/virtual/2026/poster/10010991)
[**[Paper]**](https://openreview.net/forum?id=Ax02eR2c3d)

While Multimodal Large Language Models (MLLMs) excel at general understanding, they struggle with high-level physics reasoning, particularly regarding intuitive physics and continuum dynamics. To address this, we introduce two benchmark tasks: Next Frame Selection (NFS) and Temporal Coherence Verification (TCV). Experiments show that state-of-the-art models perform poorly on these tasks. We propose Scene Dynamic Field (SDF), a multi-task fine-tuning framework that integrates physics simulators. SDF significantly boosts performance—achieving major gains in fluid tasks—and demonstrates strong generalization to unseen domains.

</div>
</div>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/llm_perception_teaser_figure.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[The Labyrinth of Links: Navigating the Associative Maze of Multi-modal LLMs](https://arxiv.org/abs/2410.01417)

Hong Li, Nanxi Li, **Yuanjie Chen**, Jianbin Zhu, Qinlu Guo, Cewu Lu, Yong-Lu Li 

[**[Project website]**](https://mvig-rhos.com/llm_inception)
[**[Paper]**](https://arxiv.org/abs/2410.01417)

In this paper, we first devise a standard association benchmark based on adjective and verb association semantic concepts. Instead of costly data annotation and organization, we propose a convenient annotation-free reconstruction method transforming the general dataset for our association tasks. Furthermore, we comprehensively investigate the MLLMs's ability and potential for association ability.

</div>
</div>

# 🎖 Honors and Awards
- *2026*, Outstanding Graduate of Shanghai Jiao Tong University
- *2023, 2025*, SJTU Undergraduate Second-Class Excellence Scholarship (Top 10%)
- *2022–2025*, Zhiyuan Honors Scholarship

# 📖 Educations
- *2026.9 - now*, Fudan University
- *2022.09 - 2026.6*, Shanghai Jiao Tong University

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2026.3 - 2026.8*, Research Intern at [Kafang Tech](https://www.kafangtech.com/)
- *2025.8 - 2026.3*, Algorithm Intern at [Xiaohongshu](https://www.xiaohongshu.com/protocols/about)
- *2024.7 - 2024.9*, Research Intern at [Shanghai AI Lab](https://www.shlab.org.cn/)
