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

I am **Haoxiang Sun**, an undergraduate student in **Computer Science and Engineering** at **Sichuan University** (2023.09 - expected 2027.06), currently with GPA **3.79/4.0**.

Since 2024.12, I have been a research intern at [**DICALab**](https://center.dicalab.cn/) (Data Intelligence and Computing Art Laboratory), supervised by [**Dr. Tao Wang**](https://twangnh.github.io/). My current work focuses on:

- Multimodal Large Language Models (MLLMs / VLLMs)
- Transferring VLLMs to real-world applications
- Inference acceleration and efficient decoding

<span class='anchor' id='about-me'></span>

<div class="cvpr-banner" markdown="1">
**CVPR 2026:** I will attend **CVPR 2026** in **Denver, Colorado, USA**, from **June 3 to June 8, 2026**. Feel free to reach out if you would like to meet up or grab a meal in person!
</div>

_Updated on May 2026._


# 🔥 News
- *2026.04*: &nbsp;I will join **Peking University** (Shenzhen Graduate School) as a master's student in Fall 2027.
- *2026.03*: &nbsp;[From Structure to Synergy: A Survey of Vision-Language Perception Paradigm Evolution in Multimodal Large Language Models](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=MOgH2ksAAAAJ&citation_for_view=MOgH2ksAAAAJ:u-x6o8ySG0sC) accepted by **Information Fusion**.
- *2026.02*: &nbsp;[Dr. Seg: Revisiting GRPO Training for Visual Large Language Models through Perception-Oriented Design](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=MOgH2ksAAAAJ&citation_for_view=MOgH2ksAAAAJ:u5HHmVD_uO8C) accepted by **CVPR 2026**.
<!-- - *2026.01*: &nbsp;Started contributing to vLLM and vLLM-speculators with a focus on multimodal speculative decoding. -->
- *2024.12*: &nbsp;Joined DICALab as a research intern.

# 🧩 Open Source Contributions
- *2026.01 - now*, Contributor @ **vLLM-speculators**

<!-- 
# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Survey (2025-2026)</div><img src='images/500x300.png' alt="survey" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

From Structure to Synergy: A Survey of Vision-Language Perception Paradigm Evolution in Multimodal Large Language Models

**Haoxiang Sun**, Tao Wang, Li Yuan, Jian Zhao, Jiancheng Lv

- Information Fusion · JCR Q1 · IF 15.5 · CAS Q1 Top
- First survey analyzing vision-language perception in MLLMs as an intrinsic unified capability.
- Proposed a five-stage taxonomy of MLLM perception paradigm evolution.
- Timeline: 2025.04 - 2026.03
</div>
</div>

- **Dr.Seg: Revisiting GRPO Training for Visual Large Language Models through Perception-Oriented Design**  
  **Haoxiang Sun**, Tao Wang, Chenwei Tang, Li Yuan, Jiancheng Lv  
  CVPR 2026 (CCF-A), Accept Rate: 25.42% · Timeline: 2025.08 - 2026.02

  - Identified key differences between GRPO for visual perception and reasoning tasks.
  - Designed `Look-to-Confirm` and `Distribution-Ranked Reward`.
  - Built the challenging `COCONut` dataset for multi-object perception.

# 🎖 Honors and Awards
- *2024.09*: Second-class Scholarship (Top 10%), Sichuan University.

# 📖 Educations
- *2023.09 - expected 2027.06*, B.Eng. in Computer Science and Engineering, Sichuan University, Chengdu, China (GPA: 3.79/4.0).

<!-- # 💬 Invited Talks
- No invited talks yet.
-->

# 💻 Internships
- *2024.12 - now*, Research Intern, [DICALab](https://center.dicalab.cn/) (Data Intelligence and Computing Art Laboratory), Chengdu, China.  
  Supervised by [Dr. Tao Wang](https://twangnh.github.io/); focusing on multimodal LLMs for visual perception.

<!-- # 🧩 Open Source Contributions
- *2026.01 - now*, Contributor @ **vLLM-speculators**  
  First technical lead and primary owner of multimodal speculative decoding support.
- *2026.01 - now*, Contributor @ **vLLM**  
  Supported multimodal speculative decoding in vLLM.
-->

# 🛠 Technical Skills
- **Languages**: Mandarin (native), English (fluent)
- **Programming Languages**: C/C++, Python
- **Frameworks**: PyTorch, vLLM, VeRL
