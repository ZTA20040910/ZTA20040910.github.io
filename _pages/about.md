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

Welcome to Tianao Zhang's (张天骜) personal website!

I am currently a junior undergraduate student at [Shanghai Jiao Tong University (SJTU)](https://www.sjtu.edu.cn/), majoring in Engineering Mechanics.

I am fortunate to be advised by Prof. [Yulun Zhang](https://yulunzhang.com/) and Prof. [Xiaokang Yang](https://scholar.google.com/citations?user=yDEavdMAAAAJ&hl=en) from the [School of Computer Science](https://www.cs.sjtu.edu.cn/en/), [Shanghai Jiao Tong University (SJTU)](https://www.sjtu.edu.cn/).

My research focuses on model compression and acceleration for Large Language Models (LLMs) and Diffusion Models (dLLMs), with an emphasis on techniques such as binarization and post-training quantization. I am dedicated to building powerful yet resource-efficient AI systems that push the boundaries of computational efficiency. ⚡

I am always open to collaborations and academic discussions! Feel free to reach out via email at [ztaztazta2785@gmail.com](mailto:ztaztazta2785@gmail.com) or via WeChat (ZTAZTAZTAZTAZTA).

# 🔥 News

- _2025.11_: &nbsp;🎉🎉 Our team was awarded the **Grand Prize** at the National "Challenge Cup" Competition (挑战杯全国**特等奖**) for the project "Binarization Compression Technology and Application of Large Models for Edge Deployment"!
- _2025.06_: &nbsp;🎉🎉 Our team was awarded the **Grand Prize** at the Shanghai "Challenge Cup" Competition (挑战杯上海市**特等奖**) for the project "Novel Binarization Compression Technology for Large Language Models"!
- _2025.01_: &nbsp;🎉🎉 Our paper **ARB-LLM** has been accepted to **ICLR 2025**!

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/arb-llm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ARB-LLM: Alternating Refined Binarizations for Large Language Models](https://arxiv.org/abs/2410.03129)

Zhiteng Li<sup>1</sup>, Xianglong Yan<sup>1</sup>, **Tianao Zhang**, Haotong Qin, Dong Xie, Jiang Tian, Zhongchao Shi, Linghe Kong\*, Yulun Zhang\*, and Xiaokang Yang

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/quant-dllm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Quant-dLLM: Post-Training Extreme Low-Bit Quantization for Diffusion Large Language Models](https://arxiv.org/abs/2510.03274)

**Tianao Zhang**<sup>1</sup>, Zhiteng Li<sup>1</sup>, Xianglong Yan, Haotong Qin, Yong Guo, and Yulun Zhang\*

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/pt2llm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PT<sup>2</sup>-LLM: Post-Training Ternarization for Large Language Models](https://arxiv.org/abs/2510.03267)

Xianglong Yan<sup>1</sup>, Chengzhu Bao<sup>1</sup>, Zhiteng Li, **Tianao Zhang**, Kaicheng Yang, Haotong Qin, Ruobing Xie, Xingwu Sun, and Yulun Zhang\*

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/recalkv.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ReCalKV: Low-Rank KV Cache Compression via Head Reordering and Offline Calibration](https://arxiv.org/abs/2505.24357)

Xianglong Yan<sup>1</sup>, Zhiteng Li<sup>1</sup>, **Tianao Zhang**, Haotong Qin, Linghe Kong, Yulun Zhang\*, and Xiaokang Yang

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/pbs2p.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Progressive Binarization with Semi-Structured Pruning for LLMs](https://arxiv.org/abs/2502.01705)

Xianglong Yan<sup>1</sup>, **Tianao Zhang**<sup>1</sup>, Zhiteng Li, Haotong Qin, and Yulun Zhang\*

</div>
</div>

<!--
[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**
- -->

# 🎖 Honors and Awards

- Tongsheng Scholarship (Top 1%) 同声奖学金 (2025)
- Han Ying Ju Hua Special Achievements Scholarship (Top 1%) 含英咀华专项成就奖学金 (2025)
- Zhiyuan Honors Scholarship (Top 5%) 致远荣誉奖学金 (2023,2024,2025)
- Excellent Undergraduate Scholarship (Top 10%) 本科生优秀奖学金 (2024, 2025)

# 📖 Educations

- _2023.09 - now_, B.Eng. in [Shanghai Jiao Tong University](https://www.sjtu.edu.cn/), Shanghai, China.
- _2020.09 - 2023.06_, High School, [The Experimental High School Attached to Beijing Normal University](http://www.sdsz.com.cn/), Beijing, China.

<!--
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
- -->

# 🤝 Academic Service

- Reviewer of ICLR 2026.

# 💻 Internships

- _2025.7 - 2025.12_, AI Algorithm Engineer, [Huawei](https://www.huawei.com/cn/), Shanghai, China.
