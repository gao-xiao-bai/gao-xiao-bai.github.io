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

I am a fourth-year PhD student at [CUHK text mining group](https://www1.se.cuhk.edu.hk/~textmine/), supervised by Prof. Lam Wai. Prior to this, I obtained my master degree at Harbin Institute of Technology.

In the past, my research primarily revolved around enhancing the generalization capabilities and robustness of natural language processing (NLP) models. This was achieved through the optimization of model architecture, learning algorithms, and data representation. Currently, my interests have shifted towards large language model (LLM) alignment, specifically focusing on instruction tuning and AI safety.


<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Preprints 


<div class='paper-box'><div class='paper-box-image'><div><img src='images/StrategyLLM.jpg' height="100%" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

StrategyLLM: Large Language Models as Strategy Generators, Executors, Optimizers, and Evaluators for Problem Solving

**Chang Gao**, Haiyun Jiang, Deng Cai, Shuming Shi, Wai Lam

[Paper](https://arxiv.org/abs/2311.08803) 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/JsonTuning.jpg' height="100%" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

JsonTuning: Towards Generalizable, Robust, and Controllable Instruction Tuning

**Chang Gao**, Wenxuan Zhang, Guizhen Chen, Wai Lam

[Paper](https://arxiv.org/abs/2310.02953) [Code](https://github.com/gao-xiao-bai/jsontuning)
</div>
</div>

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024 Findings</div><img src='images/CodeAttack.jpg' height="100%" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Exploring Safety Generalization Challenges of Large Language Models via Code

Qibing Ren\*, **Chang Gao**\*, Jing Shao, Junchi Yan, Xin Tan, Wai Lam, Lizhuang Ma

[Paper](https://arxiv.org/abs/2403.07865)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/m3exam.jpg' height="100%" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

M3Exam: A Multilingual, Multimodal, Multilevel Benchmark for Examining Large Language Models

Wenxuan Zhang, Sharifah Mahani Aljunied, **Chang Gao**, Yew Ken Chia, Lidong Bing

[Paper](https://arxiv.org/abs/2306.05179) [Code](https://github.com/DAMO-NLP-SG/M3Exam)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2023 Findings</div><img src='images/E2H.png' height="100%" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Easy-to-Hard Learning for Information Extraction

**Chang Gao**, Wenxuan Zhang, Wai Lam, Lidong Bing

[Paper](https://arxiv.org/abs/2305.09193) [Code](https://github.com/DAMO-NLP-SG/IE-E2H)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2022 Findings</div><img src='images/TKK.png' height="100%" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Towards Generalizable and Robust Text-to-SQL Parsing

**Chang Gao**, Bowen Li, Wenxuan Zhang, Wai Lam, Binhua Li, Fei Huang, Luo Si, Yongbin Li

[Paper](https://aclanthology.org/2022.findings-emnlp.155/) [Code](https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/tkk)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2022</div><img src='images/Yingxiu.png' width="100%" height="100%"></div></div>
<div class='paper-box-text' markdown="1">

Prompt Conditioned VAE: Enhancing Generative Replay for Lifelong Learning in Task-Oriented Dialogue

Yingxiu Zhao, Yinhe Zheng, Zhiliang Tian, **Chang Gao**, Jian Sun, Nevin L. Zhang

[Paper](https://aclanthology.org/2022.emnlp-main.766/) [Code](https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/pcll)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2022</div><img src='images/UniGDD.png' width="100%" height="100%" ></div></div>
<div class='paper-box-text' markdown="1">

UniGDD: A Unified Generative Framework for Goal-Oriented Document-Grounded Dialogue

**Chang Gao**, Wenxuan Zhang, Wai Lam

[Paper](https://aclanthology.org/2022.acl-short.66/) [Code](https://github.com/gao-xiao-bai/UniGDD)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECIR 2022</div><img src='images/GACS.png' width="100%" height="100%"></div></div>
<div class='paper-box-text' markdown="1">

Search Clarification Selection via Query-Intent-Clarification Graph Attention

**Chang Gao**, Wai Lam

[Paper](https://www.researchgate.net/publication/364165129_Search_Clarification_Selection_via_Query-Intent-Clarification_Graph_Attention)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CIKM 2020</div><img src='images/Rotate3D.png' width="100%" height="100%"></div></div>
<div class='paper-box-text' markdown="1">

Rotate3D: Representing Relations as Rotations in Three-Dimensional Space for Knowledge Graph Embedding

**Chang Gao**, Chengjie Sun, Lili Shan, Lei Lin, Mingjiang Wang



[Paper](https://dl.acm.org/doi/10.1145/3340531.3411889) [Code](https://github.com/gao-xiao-bai/Rotate3D)
</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 📖 Educations
- *2020.08 - 2024.08 (now)*, PhD, The Chinese University of Hong Kong, Hong Kong, China
- *2018.09 - 2020.06*, Master, Harbin Institute of Technology, Harbin, China
- *2014.09 - 2018.06*, Undergraduate, Harbin Institute of Technology, Weihai, China

# 🎖 Honors and Awards
- *2020.09* ACM SIGIR Student Travel Grant 
- *2020.06* Outstanding Master Thesis Award
- *2018.06* Outstanding Graduate Award
- *2017.11* National Scholarship
- *2016.11* National Scholarship

<!-- # 💻 Experience
- *2019.05 - 2020.02*,  -->


<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
 -->
<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->