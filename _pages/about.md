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
Hi there! I am an undergraduate from Shanghai Jiao Tong University, majoring in Artificial Intelligence. My research interests include, but are not limited to, Multi-modal learning.

# 🔥 News
- *2026.01*: &nbsp;🎉🎉 One paper is accepted by ICLR 2026! 
- *2025.01*: &nbsp;🎉🎉 One paper is accepted by ICLR 2025! 


# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/sdf_teaser_figure.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Beyond Static Vision: Scene Dynamic Field Unlocks Intuitive Physics Understanding in Multi-modal Large Language Models](https://arxiv.org/abs/2410.01417)

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

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2022.09 - now*, Shanghai Jiao Tong University

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->
