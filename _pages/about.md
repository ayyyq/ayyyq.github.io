---
permalink: /
title: ""
excerpt: "PhD student at USC building LLMs and LLM agents that improve themselves, that humans can trust, and that are efficient to train and run."
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!-- ## About Me -->
👋 Hi, I'm Yuqing! I'm a third-year Ph.D. student at the University of Southern California, advised by Prof. [Robin Jia](https://robinjia.github.io/). Previously, I earned my M.S. at Fudan University with Prof. [Xipeng Qiu](https://xpqiu.github.io/) and interned at GAIR Lab with Prof. [Pengfei Liu](https://plms.ai/people/index.html).

[//]: # (I am broadly interested in understanding *how and why* today's large language models fail. My research analyzes and mitigates their limitations in **problem-solving** and **human-AI interaction**, with the ultimate goal of making large language models more useful and reliable under limited resources.)

[//]: # (🔭 My ongoing projects center on **LLM Memory** and **Agent Evaluation and Benchmarking**.)

I am broadly interested in building LLMs and LLM agents that improve themselves, that humans can trust, and that are efficient to train and run. My research currently spans three directions:

- 🔁 **Self-improvement.** How can LLMs and agents improve themselves without human supervision? I study how LLMs can surpass their weaker supervisors ([weak-to-strong](https://arxiv.org/abs/2407.13647)), and how agents can evolve their own memory ([self-evolving memory extraction](https://arxiv.org/abs/2604.11610)), tools (unsupervised tool evolution, *paper coming soon*), and harnesses<!-- TODO: replace with [unsupervised tool evolution](arXiv link) once released -->.
- 🤝 **Trustworthy collaboration.** How can LLMs and agents become collaborators that humans can trust and oversee? I work on honesty, so that LLMs are upfront about what they know and admit their mistakes ([honesty](https://arxiv.org/abs/2312.07000), [retraction](https://arxiv.org/abs/2505.16170)); memory, so that agents can better serve their users ([memory](https://arxiv.org/abs/2604.11610)); and transparency, so that humans can see what agents are actually doing.
- ⚡ **Efficiency.** How can LLMs and agents become faster and cheaper to train and run? I have worked on fine-tuning LLMs with limited resources ([LOMO](https://arxiv.org/abs/2306.09782)), and I'm increasingly interested in the time and cost of agents on long-horizon tasks.

# News
- 🎤 **\[Oct 2026\]** I'll be at COLM 2026 in San Francisco (Oct 5 to 9), giving an oral presentation on our [retraction](https://arxiv.org/abs/2505.16170) paper on the afternoon of Oct 6. Come say hi!
- ✈️ **\[Jul 2026\]** Attended ACL 2026 in San Diego, where I presented our [table referencing](https://arxiv.org/abs/2606.32029) paper as an oral, and our [retraction](https://arxiv.org/abs/2505.16170) paper won the Best Paper Award at KnowFM@ACL 2026.
- 📍 **\[May 2026\]** Joined Google, Sunnyvale (SVL) as a research intern.

# Education
- **University of Southern California**  
  Ph.D. in Computer Science, 2024 - Present  
  Advisor: Prof. Robin Jia
- **Fudan University**  
  M.S. in Computer Science, 2021 - 2024  
  Advisor: Prof. Xipeng Qiu  
- **University of Chinese Academy of Sciences**  
  B.E. in Computer Science, 2017 - 2021  
  <!-- GPA: 3.94/4.00, Rankings: 3/112   -->

# Experience
- 🟦 **Systems Research, Google**  
  Research Intern, May 2026 - Aug. 2026  
  Mentor: [Jiani Zhang](https://jennyzhang0215.github.io/)  
  Worked on tool-centered evolution for data-lake analytics agents.
- 🟧 **Amazon Bedrock Core Science**  
  Applied Scientist Intern, May 2025 - Aug. 2025  
  Mentor: [Qi Zhu](https://gentlezhu.github.io/)  
  Enhanced LLM robustness for table tasks by identifying failure modes and optimizing data referencing accuracy.

# Selected Publications
\* denotes co-first authors
<!-- $^\dagger$ denotes corresponding author/main advisor -->

**Self-Evolving LLM Memory Extraction Across Heterogeneous Tasks**  
<span class="authors">**Yuqing Yang**, Tengxiao Liu, Wang Bill Zhu, Taiwei Shi, Linxin Song, Robin Jia</span>  
<span class="venue venue-pre">Preprint 2026</span> [[paper]](https://arxiv.org/abs/2604.11610) [[code]](https://github.com/ayyyq/heterogeneous-memory-extraction)

**When LLMs Read Tables Carelessly: Measuring and Reducing Data Referencing Errors**  
<span class="authors">**Yuqing Yang**, Qi Zhu, Zhen Han, Boran Han, Zhengyuan Shen, Shuai Wang, Vassilis N. Ioannidis, Huzefa Rangwala</span>  
<span class="venue venue-oral">ACL 2026 Oral</span> [[paper]](https://arxiv.org/abs/2606.32029) [[code]](https://github.com/ayyyq/table-referencing)

**When Do LLMs Admit Their Mistakes? Understanding the Role of Model Belief in Retraction**  
<span class="authors">**Yuqing Yang**, Robin Jia</span>  
<span class="venue venue-oral">CoLM 2026 Oral</span> <span class="venue venue-award">🏆 KnowFM@ACL 2026 Best Paper</span> [[paper]](https://arxiv.org/abs/2505.16170) [[code]](https://github.com/ayyyq/llm-retraction)

**Weak-to-Strong Reasoning**  
<span class="authors">**Yuqing Yang**, Yan Ma, Pengfei Liu</span>  
<span class="venue venue-cl">EMNLP Findings 2024</span> [[paper]](https://arxiv.org/abs/2407.13647) [[code]](https://github.com/GAIR-NLP/weak-to-strong-reasoning)

[//]: # (**BeHonest: Benchmarking Honesty of Large Language Models**  )

[//]: # (Steffi Chern\*, Zhulin Hu\*, **Yuqing Yang**\*, Ethan Chern, Yuan Guo, Jiahe Jin, Binjie Wang, Pengfei Liu  )

[//]: # (preprint arXiv 2024. [[paper]]&#40;https://arxiv.org/abs/2406.13261&#41; [[code]]&#40;https://github.com/GAIR-NLP/BeHonest&#41;)

**Alignment for Honesty**  
<span class="authors">**Yuqing Yang**, Ethan Chern, Xipeng Qiu, Graham Neubig, Pengfei Liu</span>  
<span class="venue venue-ml">NeurIPS 2024</span> [[paper]](https://arxiv.org/abs/2312.07000) [[code]](https://github.com/GAIR-NLP/alignment-for-honesty)

<!-- **OlympicArena: Benchmarking Multi-discipline Cognitive Reasoning for Superintelligent AI**  
<span class="authors">Zhen Huang, Zengzhi Wang, Shijie Xia, Xuefeng Li, Haoyang Zou, Ruijie Xu, Run-Ze Fan, Lyumanshan Ye, Ethan Chern, Yixin Ye, Yikai Zhang, **Yuqing Yang**, Ting Wu, Binjie Wang, Shichao Sun, Yang Xiao, Yiyuan Li, Fan Zhou, Steffi Chern, Yiwei Qin, Yan Ma, Jiadi Su, Yixiu Liu, Yuxiang Zheng, Shaoting Zhang, Dahua Lin, Yu Qiao, Pengfei Liu</span>  
<span class="venue venue-ml">NeurIPS D&amp;B 2024</span> [[paper]](https://arxiv.org/abs/2406.12753) -->

**Full Parameter Fine-tuning for Large Language Models with Limited Resources**  
<span class="authors">Kai Lv, **Yuqing Yang**, Tengxiao Liu, Qinghui Gao, Qipeng Guo, Xipeng Qiu</span>  
<span class="venue venue-oral">ACL 2024 Oral</span> [[paper]](https://arxiv.org/abs/2306.09782) [[code]](https://github.com/OpenLMLab/LOMO)

<!-- **Plan, Verify and Switch: Integrated Reasoning with Diverse X-of-Thoughts**  
<span class="authors">Tengxiao Liu, Qipeng Guo, **Yuqing Yang**, Xiangkun Hu, Yue Zhang, Xipeng Qiu, Zheng Zhang</span>  
<span class="venue venue-cl">EMNLP 2023</span> [[paper]](https://arxiv.org/abs/2310.14628) -->

[//]: # (**CoLLiE: Collaborative Training of Large Language Models in an Efficient Way**  )

[//]: # (Kai Lv\*, Shuo Zhang\*, Tianle Gu, Shuhao Xing, Jiawei Hong, Keyu Chen, Xiaoran Liu, **Yuqing Yang**, Honglin Guo, Tengxiao Liu, Yu Sun, Qipeng Guo, Hang Yan, Xipeng Qiu  )

[//]: # (EMNLP Demo 2023. [[paper]]&#40;https://arxiv.org/abs/2312.00407&#41; [[code]]&#40;https://github.com/OpenLMLab/collie&#41;)

[//]: # (**An AMR-based Link Prediction Approach for Document-level Event Argument Extraction**  )

[//]: # (**Yuqing Yang**\*, Qipeng Guo\*, Xiangkun Hu, Yue Zhang, Xipeng Qiu, Zheng Zhang  )

[//]: # (ACL 2023. [[paper]]&#40;https://arxiv.org/abs/2305.19162&#41; [[code]]&#40;https://github.com/ayyyq/TARA&#41;)

[//]: # ()
[//]: # (**DORE: Document ordered relation extraction based on generative framework**  )

[//]: # (Qipeng Guo\*, **Yuqing Yang**\*, Hang Yan, Xipeng Qiu, Zheng Zhang  )

[//]: # (EMNLP 2022 Findings. [[paper]]&#40;https://arxiv.org/abs/2210.16064&#41; [[code]]&#40;https://github.com/ayyyq/DORE&#41;)

[//]: # (**Uncertain local-to-global networks for document-level event factuality identification**  )

[//]: # (Pengfei Cao, Yubo Chen, **Yuqing Yang**, Kang Liu, Jun Zhao  )

[//]: # (EMNLP 2021. [[paper]]&#40;https://aclanthology.org/2021.emnlp-main.207/&#41;)

[//]: # (# Awards)

[//]: # ()
[//]: # (National Scholarship in 2017-2018  )

[//]: # ()
[//]: # (Outstanding Graduate of Beijing  )

[//]: # ()
[//]: # (Outstanding Graduate of University of Chinese Academy of Sciences  )

[//]: # ()
[//]: # (Xiaomi Scholarship in 2022-2023)

[//]: # ()
[//]: # (Outstanding Graduate of Fudan University)
