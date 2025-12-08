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

Hi, there! I’m Tianao Zhang, a junor undergraduate student from [Shanghai Jiao Tong University (SJTU)](https://en.sjtu.edu.cn/), majoring in Engineering Mechanics. 
I  have the privilege of being advised by Prof. [Yulun Zhang](https://yulunzhang.com/) from [the School of Computer Science](https://www.cs.sjtu.edu.cn/en/).

My research interests lie in LLM/VLM/dLLM model compression and acceleration, including techniques such as binarization and post-training quantization. Additionally, I focus on AI-generated content (AIGC). I’m open to any collaborations! Feel free to drop me an email for casual chat!


# 🔥 News
- *2025.05*: &nbsp;🎉🎉 项目《面向端侧部署的大模型二值化压缩技术及应用》荣获第十九届“挑战杯”全国大学生课外学术科技作品竞赛特等奖。
- *2025.01*: &nbsp;🎉🎉 Our paper ARB-LLM is accepted by ICLR 2025.

# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2025</div><img src='images/arbllm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**ARB-LLM: Alternating Refined Binarizations for Large Language Models**](https://arxiv.org/abs/2410.03129) 
<div style="display: inline">
    <a href="https://arxiv.org/abs/2410.03129"> <strong>[Paper]</strong></a>
    <a href="https://github.com/ZHITENGLI/ARB-LLM"> <strong>[Code]</strong></a>
    <a class="fakelink" onclick="$(this).siblings('.abstract').slideToggle()" ><strong>[Abstract]</strong></a>
    <div class="abstract"  style="overflow: hidden; display: none;">  
        <p> Large Language Models (LLMs) have greatly pushed forward advancements in natural language processing, yet their high memory and computational demands hinder practical deployment. Binarization, as an effective compression technique, can shrink model weights to just 1 bit, significantly reducing the high demands on computation and memory. However, current binarization methods struggle to narrow the distribution gap between binarized and full-precision weights, while also overlooking the column deviation in LLM weight distribution. To tackle these issues, we propose ARB-LLM, a novel 1-bit post-training quantization (PTQ) technique tailored for LLMs. To narrow the distribution shift between binarized and full-precision weights, we first design an alternating refined binarization (ARB) algorithm to progressively update the binarization parameters, which significantly reduces the quantization error. Moreover, considering the pivot role of calibration data and the column deviation in LLM weights, we further extend ARB to ARB-X and ARB-RC. In addition, we refine the weight partition strategy with column-group bitmap (CGB), which further enhance performance. Equipping ARB-X and ARB-RC with CGB, we obtain ARB-LLM-X and ARB-LLM-RC respectively, which significantly outperform state-of-the-art (SOTA) binarization methods for LLMs. As a binary PTQ method, our ARB-LLMRC is the first to surpass FP16 models of the same size.  </p>
</div>

Zhiteng Li<sup>1</sup>, Xianglong Yan<sup>1</sup>, **Tianao Zhang**, Haotong Qin, Dong Xie, Jiang Tian, Zhongchao Shi, Linghe Kong*, Yulun Zhang*, and Xiaokang Yang

- **Memory Saving** - **33B** LLMs RL on a single H100 GPU.
- **Training Speedup** - **1.7x** end-to-end training speedup. 
- **High Performance** - Comparable accuracy to full training.
<!-- 
[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**
- -->

# 🎖 Honors and Awards
- Zhiyuan Honors Scholarship 致远荣誉奖学金 (2023,2024,2025)
- Excellent Undergraduate Scholarship 本科生优秀奖学金 (2024, 2025)
- Tongsheng Scholarship 同声奖学金 (2025)



# 📖 Educations
- *2023.09 - now*, B.Eng. in [Shanghai Jiao Tong University](https://www.sjtu.edu.cn/), Shanghai, China.
- *2020.09 - 2023.06*, High School, [The Experimental High School Attached to Beijing Normal University](http://www.sdsz.com.cn/), Beijing, China.

<!-- 
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
- -->

# 💻 Internships
- *2025.7 - 2025.12*, [Huawei](https://www.huawei.com/cn/), China.