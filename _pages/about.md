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

## Hi there! 👋

I am a Ph.D. student in Computer Science at Purdue University, advised by [Prof. Chunwei Liu](https://www.cs.purdue.edu/homes/chunwei/). I received both my master’s and bachelor’s degrees in Computer Science from Shanghai Jiao Tong University (SJTU). Before joining Purdue, I worked as a Software Engineer at Alibaba Cloud, building infrastructure for distributed deep learning.

My research focuses on **efficient AI systems**, especially the training and serving of large language models (LLMs). I study data selection, model distillation, and test-time alignment, and develop inference optimizations for heterogeneous GPU systems. I also evaluate the trade-offs among model quality, latency, and environmental impact. I interned on Meta’s Ads Ranking team, working on synthetic-data filtering, and now continue as a part-time Student Researcher working on LLM reranking and on-policy distillation.

<p style="color: #c62828; font-weight: 600;">
🚀 I’m actively exploring industry opportunities in AI research and engineering. Feel free to reach out!
</p>

# 🔥 News
- *2026.10*: 🎉 Our work on efficient LLM reranking, [DecisionRank: On-Policy Distillation for Decision-Model Rerankers](https://arxiv.org/abs/2610.42128), is now available online.
- *2026.09*: 🎉 Our work on online synthetic-data filtering, [FROST: Let Training Guide Selection](https://arxiv.org/abs/2609.29988), is now available online.
- *2026.08*: 🎉 I completed my summer internship at Meta. Many thanks to my mentor and teammates for their guidance, support, and collaboration!
- *2025.10*: 🎉 Our work on carbon-efficient disaggregated speculative decoding was accepted to [IEEE Computer Architecture Letters](https://www.computer.org/csdl/journal/ca). Thanks to my collaborators for a great collaboration!
- *2025.08*: 🎉 Our work on reward-shifted speculative sampling for test-time alignment was accepted to the EMNLP 2025 main conference. It was a pleasure working with all my coauthors!
- *2025.06*: 🎉 Our paper SCARF on water-sustainable computing was accepted to [HotCarbon 2025](https://hotcarbon.org/). Grateful for the support from my collaborators!
- *2025.05*: 🎉 Our paper FUEL on benchmarking the environmental impact of LLM serving was accepted to the ACL 2025 main conference. Thanks to my collaborators for their support throughout this project!

# 📝 Publications 
\* denotes equal contribution
- <span class="badge">arXiv 2026</span>
  DecisionRank: On-Policy Distillation for Decision-Model Rerankers<br>
  **Yanran Wu**, Dian Yu, Chongyang Bai, Jieyi Zhang, Rui Liu, Tianyi Chen, Shike Mei, Hang Cui, Frank Shyu, Sandeep Pandey, Luke Simon, Chunwei Liu, Xi Liu [📄 Paper](https://arxiv.org/abs/2610.42128)

- <span class="badge">arXiv 2026</span>
  Let Training Guide Selection: Online Synthetic Data Filtering via Real-Anchored Utility<br>
  **Yanran Wu**, Sana Lakdawala, Renzo Tassara Miller, Chongyang Bai, Sharath Ciddu, Shivendra Pratap Singh, Kungang Li, Sandeep Pandey, Chunwei Liu [📄 Paper](https://arxiv.org/abs/2609.29988)

- <span class="badge">ACL 2025</span>
  Unveiling Environmental Impacts of Large Language Model Serving: A Functional Unit View<br>
  **Yanran Wu**, Inez Hua, Yi Ding  [📄 Paper](https://arxiv.org/abs/2502.11256) · [💻 Code](https://github.com/jojacola/FUEL)<br>
  <span style="font-weight: bold; font-size: 0.9em; color: #333;">
  📰 Media Coverage:
</span>  [Green Software Foundation](https://www.linkedin.com/posts/green-software-foundation_unveiling-environmental-impacts-of-large-activity-7303076333545287680-CZSZ?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAA1GomkBzEFGPxfVQWWZcEnULYvX6TPzBDs)
- <span class="badge">HotCarbon&#39;25</span>
  Not All Water Consumption Is Equal: A Water Stress Weighted Metric for Sustainable Computing<br>
  **Yanran Wu**, Inez Hua, Yi Ding  [📄 Paper](https://arxiv.org/abs/2506.22773) · [💻 Code](https://github.com/jojacola/SCARF)<br>
  <span style="font-weight: bold; font-size: 0.9em; color: #333;">
  📰 Media Coverage:
</span>  [Texas Tribune](https://www.texastribune.org/2025/09/25/texas-data-center-water-use/) · [Texas Public Radio](https://www.tpr.org/environment/2025-08-15/big-techs-big-thirst-ais-demand-for-texas-water) · [Green Software Foundation](https://www.linkedin.com/posts/green-software-foundation_not-all-water-consumption-is-equal-a-water-activity-7367179218721337345-3BcW?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAA1GomkBzEFGPxfVQWWZcEnULYvX6TPzBDs) · [Green Web Foundation](https://www.thegreenwebfoundation.org/news/spains-data-centre-law-supporting-local-groups-in-the-public-consultation/)
- <span class="badge">EMNLP 2025</span>
  Reward-Shifted Speculative Sampling Is An Efficient Test-Time Weak-to-Strong Aligner<br>
 Bolian Li, **Yanran Wu**, Xinyu Luo, Ruqi Zhang  [📄 Paper](https://arxiv.org/abs/2508.15044)
- <span class="badge">IEEE CAL&#39;25</span>
  Disaggregated Speculative Decoding for Carbon-Efficient LLM Serving<br>
  Tianyao Shi\*, **Yanran Wu\***, Sihang Liu, Yi Ding  [📄 Paper](https://doi.org/10.1109/LCA.2025.3630094)

- <span class="badge">ICIP 2021</span>
  Fast and accurate scene parsing via bi-direction alignment networks<br>
  **Yanran Wu\***, Xiangtai Li\*, Chen Shi, Yunhai Tong, Yang Hua, Tao Song, Ruhui Ma, Haibing Guan  [📄 Paper](https://ieeexplore.ieee.org/abstract/document/9506720) · [💻 Code](https://github.com/jojacola/BiAlignNet)

- <span class="badge">ICIP 2021</span>
  Dynamic dual sampling module for fine-grained semantic segmentation<br>
  Chen Shi\*, Xiangtai Li\*, **Yanran Wu**, Yunhai Tong, Yi Xu  [📄 Paper](https://ieeexplore.ieee.org/abstract/document/9506628/)


# 📖 Education
- **Ph.D. in Computer Science**, Purdue University  
*2023 – Present* &nbsp;&nbsp;📍 West Lafayette, USA  

- **M.S. in Computer Science and Technology**, Shanghai Jiao Tong University  
*2019 – 2022* &nbsp;&nbsp;📍 Shanghai, China  

- **B.S. in Computer Science and Technology**, Shanghai Jiao Tong University  
*2015 – 2019* &nbsp;&nbsp;📍 Shanghai, China  

# 💻 Experience
- **Part-time Student Researcher, Ads Ranking**, Meta  
*Aug. 2026 – Present*  
Developed [DecisionRank](https://arxiv.org/abs/2610.42128) for efficient LLM reranking through on-policy distillation.

- **Research Scientist Intern, Ads Ranking**, Meta  
*May 2026 – Aug. 2026* &nbsp;&nbsp;📍 Sunnyvale, CA  
Developed [FROST](https://arxiv.org/abs/2609.29988) for online synthetic-data filtering, evaluated across ads ranking, text-to-SQL fine-tuning, and image classification.

- **Software Engineer**, Alibaba Cloud  
*Jun. 2022 – Jul. 2023* &nbsp;&nbsp;📍 Shanghai, China  
Worked on cloud-native infrastructure for distributed deep learning.

- **Computer Vision Research Intern**, SenseTime  
*Jul. 2020 – Mar. 2022* &nbsp;&nbsp;📍 Shanghai, China  
Worked on multi-object detection for autonomous driving.

# 📚 Teaching
- **Teaching Assistant**, Purdue CS 52500: Parallel Computing, *Spring 2026*
- **Teaching Assistant**, Purdue CS 53600: Data Communication and Computer Networks, *Fall 2025*
- **Teaching Assistant**, Purdue CS 37300: Data Mining and Machine Learning, *Fall 2024*

