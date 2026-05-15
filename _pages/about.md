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
Hi, I'm Chubin Chen. I am currently a second-year master's student at Tsinghua University, under the supervision of Professor Xiu Li. I completed my undergraduate studies at Beijing University of Posts and Telecommunications (BUPT).
My research lies in multimodal AIGC, spanning diffusion models, reinforcement learning, and world models.
I am always open to discussing potential research collaborations with fellow researchers and practitioners in the field. Additionally, I am currently preparing to apply for PhD programs starting in the Fall 2027 semester, and I welcome any insights or opportunities in this pursuit.



# 🔥 News

- *2026.05*: &nbsp;🎉 ***`E²PO`*** (co-first-author) and another co-author paper were both accepted by **ICML 2026**!

- *2026.02*: &nbsp;🎉 One first-author paper, ***`D²-Align`*** was accepted by **CVPR 2026**!

- *2026.01*: &nbsp;🎉 One first-author paper, ***`S²-Guidance`*** was accepted by **ICLR 2026**!

- *2025.11*: &nbsp;🎉 Two papers were accepted by **AAAI 2026**!

- *2025.07*: &nbsp;🎉 One paper was accepted by **ICCV 2025**!

- *2025.01*: &nbsp;🎉 One paper was accepted by **ICLR 2025**!




# 📝 Publications

<!-- 三篇带平方的核心论文，单独用三栏网格突出展示 -->
## ✨ Featured Works
<div style="display: grid; grid-template-columns: 1fr 1fr 1fr; gap: 24px; margin: 30px 0;">

<!-- E²PO 卡片 -->
<div class='paper-box' style="border: 3px solid #ff6b6b; border-radius: 12px; padding: 16px; background: #fff8f8; transition: transform 0.2s;">
  <div class='paper-box-image'>
    <div><div class="badge" style="background: linear-gradient(135deg, #ff6b6b, #ee5a5a); color: white; padding: 4px 8px; border-radius: 4px; display: inline-block;">ICML 2026</div>
    <img src='images/500x300.png' alt="E²PO" width="100%" style="border-radius: 8px; margin-top:10px;"></div>
  </div>
  <div class='paper-box-text' style="padding:12px 8px;">
  <a href="https://your-paper-link.com">
    <strong><em><span style="color:#ff6b6b;">E</span>²PO</em></strong>: Embedding-perturbed Exploration Preference Optimization for Flow Models
  </a>
  <br><br>
  Sujie Hu ⋅ <strong>Chubin Chen</strong> ⋅ Jiashu Zhu ⋅ Jiahong Wu ⋅ Xiangxiang Chu ⋅ Xiu Li
  <br><br>
  <a href="https://your-project-link.com">🔗 Project</a> | <a href="https://your-paper-link.com">📄 Paper</a>
  </div>
</div>

<!-- D²-Align 卡片 -->
<div class='paper-box' style="border: 3px solid #4ecdc4; border-radius: 12px; padding: 16px; background: #f5fffe; transition: transform 0.2s;">
  <div class='paper-box-image'>
    <div><div class="badge" style="background: linear-gradient(135deg, #4ecdc4, #44a08d); color: white; padding: 4px 8px; border-radius: 4px; display: inline-block;">CVPR 2026</div>
    <img src='images/500x300.png' alt="D²-Align" width="100%" style="border-radius: 8px; margin-top:10px;"></div>
  </div>
  <div class='paper-box-text' style="padding:12px 8px;">
  <a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=cVOC7dwAAAAJ&citation_for_view=cVOC7dwAAAAJ:zA6iFVUQeVQC">
    <strong><em><span style="color:#4ecdc4;">D</span>²-Align</em></strong>: Taming Preference Mode Collapse via Directional Decoupling Alignment in Diffusion Reinforcement Learning
  </a>
  <br><br>
  <strong>Chubin Chen</strong>, Sujie Hu, Jiashu Zhu, Meiqi Wu, Jintao Chen, Yanxun Li, Nisha Huang, Chengyu Fang, Jiahong Wu, Xiangxiang Chu, Xiu Li
  <br><br>
  <a href="https://your-project-link.com">🔗 Project</a> | <a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=cVOC7dwAAAAJ&citation_for_view=cVOC7dwAAAAJ:zA6iFVUQeVQC">📄 Paper</a>
  </div>
</div>

<!-- S²-Guidance 卡片 -->
<div class='paper-box' style="border: 3px solid #96ceb4; border-radius: 12px; padding: 16px; background: #f8fff9; transition: transform 0.2s;">
  <div class='paper-box-image'>
    <div><div class="badge" style="background: linear-gradient(135deg, #96ceb4, #88b899); color: white; padding: 4px 8px; border-radius: 4px; display: inline-block;">ICLR 2026</div>
    <img src='images/500x300.png' alt="S²-Guidance" width="100%" style="border-radius: 8px; margin-top:10px;"></div>
  </div>
  <div class='paper-box-text' style="padding:12px 8px;">
  <a href="https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf">
    <strong><em><span style="color:#96ceb4;">S</span>²-Guidance</em></strong>: Stochastic Self Guidance for Training-Free Enhancement of Diffusion Models
  </a>
  <br><br>
  <strong>Chubin Chen</strong>, Jiashu Zhu, Xiaokun Feng, Nisha Huang, Meiqi Wu, Fangyuan Mao, Jiahong Wu, Xiangxiang Chu, Xiu Li
  <br><br>
  <a href="https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC">🔗 Project</a> | <a href="https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf">📄 Paper</a>
  </div>
</div>
</div>

<!-- 其他普通论文区 -->
## Other Publications
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[**S²-Guidance**: Stochastic Self Guidance for Training-Free Enhancement of Diffusion Models](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)
**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun
[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
</div></div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**



# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
