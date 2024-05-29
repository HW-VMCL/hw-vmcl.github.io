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

Hi! My name is Hongyuan Wang (王鸿远). I'm a second year M.S. student from School of Computer Scinence, Beijing Institute of Technology, supervised by [Prof. Lizhi Wang](https://wang-lizhi.github.io/). I received my bachelor's degree form the same school. I'm interested in computer photography, low-level vision, generative model and deep learning. 



# 🔥 News
- *2024.01*: &nbsp;🎉🎉 Our HySAT++ Wins ICASSP SP Grand Challenge on Hyperspectral Skin Vision!
- *2023.08*: &nbsp;🎉🎉 One paper accepted by ACM MM 2023. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/ECT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Learning Exhaustive Correlation for Spectral Super-Resolution: Where Spatial-Spectral Attention Meets Linear Dependence](https://arxiv.org/abs/2312.12833)

**Hongyuan Wang**, Lizhi Wang, Jiang Xu, Chang Chen, Xue Hu, Fenglong Song, Youliang Yan

[**Project**](https://gitee.com/hongyuan-wang-bit/models/tree/hysat_mm23/research/cv/hysat)
- Existing Transformers often separately emphasize either spatial-wise or spectral-wise correlation, disrupting the 3D features of hyperspectral images. We propose a Spectral-wise Discontinuous 3D (SD3D) splitting strategy to model unified spatial-spectral correlation both locally and non-locally.
- Existing self-attention mechanism always establishes full-rank correlation matrix by learning the correlation between pairs of tokens, leading to its inability to describe linear dependence widely existing in hyperspectral images among multiple tokens. We propose a Dynamic Low-Rank Mapping (DLRM) model, which captures linear dependence among multiple tokens through a dynamically calculated low-rank dependence map.
kens.
- Our method can model unified spatial-spectral correlation, local and non-local correlation, and low-rank and full-rank correlation, thus modeling exhaustive correlation within hyperspectral images.
</div>
</div>



# 🎖 Honors and Awards
- *2024.01* First Place Winner of ICASSP SP Grand Challenge on Hyperspectral Skin Vision. 
- *2023.10* M.S. Student Grand Prize Scholarship.
- *2022.10* M.S. New Student First Prize Scholarship.

# 📖 Educations
- *2022.09 - now*, School of Computer Science, Beijing Institute of Technology. 
- *2018.09 - 2022.06*, School of Computer Science, Beijing Institute of Technology. 

# 💻 Internships
- *2021.11 - 2022.05*, Baidu VIS, China. (Mostly online, due to the COVID-19)
