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

<div style="text-align:right;margin-bottom:1em;">
  <a href="{{ '/zh.html' | relative_url }}" style="display:inline-block;padding:6px 14px;border:1px solid #999;border-radius:20px;font-size:0.9em;text-decoration:none;">🌐 中文版</a>
</div>

<span class='anchor' id='about-me'></span>

Jinhao Dong, Ph.D., is a lecturer in the Key Laboratory of Data Engineering and Knowledge Engineering (MOE) and the School of Information, Renmin University of China (RUC), and is selected into the **Wu Yuzhang Young Talents Program (吴玉章青年英才)** of RUC. He joins the research group led by Professor [Xiaoyong Du](http://info.ruc.edu.cn/jsky/szdw/ajxjgcx/jsjkxyjsx1/js2/7374b0a3f58045fc9543703ccea2eb9c.htm) and Professor [Wei Lu](http://info.ruc.edu.cn/jsky/szdw/ajxjgcx/jsjkxyjsx1/js2/43edc05040f54656aed4869bb7969de0.htm). He is also the technical advisor of **Xiaomi's LLM Core Team**, and a **core contributor to the MiMo series of foundation models** — he is primarily responsible for code-related LLM development, including **pretraining, reinforcement learning, Code Agent, browser agent, and the OpenClaw general agent platform**. The **MiMo-V2-Pro** model that he core-contributed ranks **#8 globally and #2 in China on the Artificial Analysis Intelligence Index**, and has been the **#1 model by call volume on OpenRouter**. He took the lead in establishing the **RUC–Xiaomi Joint Key Laboratory for Foundation Large Language Models** (the first joint key laboratory under RUC's new policy) and serves on its Technical Committee.

He has published **17 papers at CCF-A top-tier conferences and journals (11 as first / corresponding author)**, covering ICML, NeurIPS, KDD, ICSE, ASE, ISSTA, FSE, etc.

He obtained his Ph.D. from the School of Computer Science, Peking University in 2025, under the supervision of Professor [Dan Hao](https://sites.google.com/view/danhao/), and his Bachelor's degree from the School of Computer Science and Technology, Xidian University. He was a visiting scholar in National University of Singapore (NUS) for one year, under the supervision of Prof. [Jun Sun](https://sunjun.site/), Prof. [Yun Lin](http://linyun.info/), and Prof. [Jin Song Dong](https://www.comp.nus.edu.sg/~dongjs/).

His current research focuses on **Large Language Models (LLMs)**, building the next-generation trustworthy, general, and autonomous LLM & agent systems. Specifically:

1. **Code LLM** — code pretraining/posttraining and Code Agent reinforcement learning
2. **LLM Agent** — planning & memory, tool use, browser agent, multi-agent collaboration, agentic interaction data synthesis
3. **LLM Infra** — long-context inference acceleration (KVCache compression & quantization), robust fine-tuning
4. **General Agent Platform** — OpenClaw general agent system, large-scale real-world user interaction data & training

***<u>If you're interested in our research group or in pursuing an internship at Xiaomi's LLM Core Team, feel free to email me at dongjinhao@ruc.edu.cn.</u>***

<!-- # 🔥 News
- *2023.11*:🎉🎉 I started my year-long visit at NUS, supervised by Prof. [Jun Sun](https://sunjun.site/), Prof. [Yun Lin](http://linyun.info/), and Prof. [Jin Song Dong](https://www.comp.nus.edu.sg/~dongjs/).
- *2023.11*:🎉🎉 I became the PC member of ASE 2024.
- *2023.07*:🎉🎉One paper is accepted by ASE 2023.
- *2023.01*:🎉🎉One paper is accepted by ICSE 2023.
- *2021.12*:🎉🎉Two papers are accepted by ICSE 2022.
- *2021.05*:🎉🎉One papers is accepted by FSE 2021.
- *2020.07*:🎉🎉One paper is accepted by ASE 2020 NIER track.
- *2020.07*:🎉🎉One paper is accepted by ISSRE 2020.
- *2019.09*:🎉🎉One paper is accepted by NeurIPS 2019. -->

# 📖 Educations

- *2020.09 - 2025.07*, **Peking University**, *Ph.D. in Computer Science*, supervised by Prof. [Dan Hao](https://sites.google.com/view/danhao/) 
- *2023.11 - 2024.11*, **National University of Singapore (NUS)**, *Visiting Scholar in Computer Science*, supervised by Prof. [Jun Sun](https://sunjun.site/), Prof. [Yun Lin](http://linyun.info/), and Prof. [Jin Song Dong](https://www.comp.nus.edu.sg/~dongjs/)

- *2016.09 - 2020.07*, **Xidian University**, *Bachelor in Software Engineering*

# 💼 Experience

- *2025.08 - Present*, **Renmin University of China**, School of Information & Key Lab of Data Engineering and Knowledge Engineering (MOE), *Lecturer*
- *2025.08 - Present*, **RUC–Xiaomi Joint Key Laboratory for Foundation LLMs**, *Technical Committee Member*
- *2024.11 - Present*, **Xiaomi LLM Core Team**, *Technical Advisor*

# 📝 Publications 

Total: **17 papers at CCF-A top venues, 11 as first / corresponding author.** (\* denotes corresponding author)

- [Technical Report] **MiMo: Unlocking the Reasoning Potential of Language Model – From Pretraining to Posttraining**
<a href='pdfs/mimo-v1.pdf'><i class="fa fa-file-pdf"></i>[PDF]</a>
<a href='https://github.com/XiaomiMiMo/MiMo'><i class="fab fa-github"></i>[GitHub]</a>
  
  **Core contributor, responsible for code pre-training and reinforcement learning.** Processed the code pre-training and post-training data, and proposed a test-difficulty–driven code reward to mitigate the sparse-reward problem in code reinforcement learning.

- [Technical Report] **MiMo-VL Technical Report**
<a href='pdfs/mimo-vl.pdf'><i class="fa fa-file-pdf"></i>[PDF]</a>
<a href='https://github.com/XiaomiMiMo/MiMo-VL'><i class="fab fa-github"></i>[GitHub]</a>
  
  Contributor

- [Technical Report] **MiMo-Audio: Audio Language Models are Few-Shot Learners**
<a href='pdfs/mimo-audio.pdf'><i class="fa fa-file-pdf"></i>[PDF]</a>
<a href='https://github.com/XiaomiMiMo/MiMo-Audio'><i class="fab fa-github"></i>[GitHub]</a>
  
  Contributor

- [ICML'26] **RaBitQCache: Rotated Binary Quantization for KVCache in Long Context LLM Inference**

  Wenhao Li, **Jinhao Dong**\*, Hailin Zhang, Wenhang Shi, Wei Lu, Xiaoyong Du

- [ICML'26] **Training Prompt Matters: State-Adaptive Prompt Optimization for Robust Fine-Tuning (SAPO)**

  Wenhang Shi, Yiren Chen, Shuqing Bian, Zhe Zhao, **Jinhao Dong**\*, Pengfei Hu, Wei Lu, Xiaoyong Du

- [KDD'26] **Scaling Agentic Capabilities via Grounded Interaction Synthesis (GAIS)**

  Wenhang Shi, **Jinhao Dong**\*, Yiren Chen, Zhe Zhao, Shuqing Bian, Wei Lu, Xiaoyong Du

- [KDD'26] **BiVCoder: A Multi-Agent Framework for Code Generation via Bidirectional Code-Test Diagnosis**

  Xiaoyang Li, **Jinhao Dong**\*, Wenhang Shi, Wei Lu, Xiaoyong Du

- [ISSTA'25] **ConTested: Consistency-Aided Tested Code Generation with LLM**
<a href='pdfs/issta25_contest.pdf'><i class="fa fa-file-pdf"></i>[PDF]</a>
<a href='https://github.com/dongjinhao-ruc/replication_package'><i class="fab fa-github"></i>[GitHub]</a>
  
  **Jinhao Dong**, Jun Sun, Wenjie Zhang, Jin Song Dong, and Dan Hao

- [ASE'24] **Revisiting the Conflict-Resolving Problem from a Semantic Perspective**
<a href='pdfs/ase24_formal_merge.pdf'><i class="fa fa-file-pdf"></i>[PDF]</a>
<a href='https://github.com/dongjinhao-ruc/ase24-merge'><i class="fab fa-github"></i>[GitHub]</a>
  
  **Jinhao Dong**, Jun Sun, Yun Lin, Yedi Zhang, Murong Ma, Jin Song Dong, and Dan Hao

- [ASE'23] **Merge Conflict Resolution: Classification or Generation?**
<a href='pdfs/ase23_merge.pdf'><i class="fa fa-file-pdf"></i>[PDF]</a>
<a href='https://github.com/dongjinhao-ruc/ase-merge'><i class="fab fa-github"></i>[GitHub]</a>
  
  **Jinhao Dong**, Qihao Zhu, Zeyu Sun, Yiling Lou, and Dan Hao

- [ICSE'23] **Revisiting Learning-based Commit Message Generation** 
<a href='pdfs/icse23_study.pdf'><i class="fa fa-file-pdf"></i>[PDF]</a>
<a href='https://doi.org/10.5281/zenodo.7042270'><i class="fab fa-github"></i>[GitHub]</a>

   **Jinhao Dong**, Yiling Lou, Dan Hao, and Lin Tan

- [ICSE'22]  **FIRA: Fine-Grained Graph-Based Code Change Representation for Automated Commit Message Generation**
<a href='pdfs/icse22_fira.pdf'><i class="fa fa-file-pdf"></i>[PDF]</a>
<a href='https://github.com/dongjinhao-ruc/FIRA-ICSE'><i class="fab fa-github"></i>[GitHub]</a>

  **Jinhao Dong**, Yiling Lou, Qihao Zhu, Zeyu Sun, Zhilin Li, Wenjie Zhang, and Dan Hao

- [ICSE'22] **Recommending Good First Issues in GitHub OSS Projects**
<a href='pdfs/icse22_recommend.pdf'><i class="fa fa-file-pdf"></i>[PDF]</a>
<a href='https://zenodo.org/record/5881117#.YeliUEBBwlI'><i class="fab fa-github"></i>[GitHub]</a>
  
  Wenxin Xiao, Hao He, Weiwei Xu, Xin Tan, **Jinhao Dong**, and Minghui Zhou

- [SCIS] **What can we learn from quality assurance badges in open-source software?**
<a href='pdfs/what.pdf'><i class="fa fa-file-pdf"></i>[PDF]</a>
<a href='https://github.com/Spiridempt/Badge'><i class="fab fa-github"></i>[GitHub]</a>

  Feng Li, Yiling Lou, Xin Tan, Zhenpeng Chen, **Jinhao Dong**, Yang Li, Xuanzhi Wang, Dan Hao, and Lu Zhang

- [ESEC/FSE'21] **Boosting Coverage-Based Fault Localization via Graph-Based Representation Learning** 
<a href='pdfs/fse21_boost.pdf'><i class="fa fa-file-pdf"></i>[PDF]</a>
<a href='https://github.com/yilinglou/Grace'><i class="fab fa-github"></i>[GitHub]</a>

  Yiling Lou, Qihao Zhu, **Jinhao Dong**, Xia Li, Zeyu Sun, Dan Hao, Lu Zhang, and Lingming Zhang

- [ASE'20 NIER track] **SRRTA: Regression Testing Acceleration via State Reuse**
<a href='pdfs/ase20_srrta_cost.pdf'><i class="fa fa-file-pdf"></i>[PDF]</a>
<a href='https://github.com/DeepReduce/DeepReduce'><i class="fab fa-github"></i>[GitHub]</a>

  **Jinhao Dong**, Yiling Lou, and Dan Hao

- [ISSRE'20] **Cost-effective testing of a deep learning model through input reduction** 
<a href='pdfs/issre20_cost.pdf'><i class="fa fa-file-pdf"></i>[PDF]</a>
<a href='https://github.com/DeepReduce/DeepReduce'><i class="fab fa-github"></i>[GitHub]</a>

  Jianyi Zhou, Feng Li, **Jinhao Dong**, Hongyu Zhang and Dan Hao

- [NeurIPS'19] **MarginGAN: Adversarial Training in Semi-Supervised Learning**
<a href='pdfs/nips19_margingan.pdf'><i class="fa fa-file-pdf"></i>[PDF]</a>
<a href='https://github.com/dongjinhao-ruc/MarginGAN'><i class="fab fa-github"></i>[GitHub]</a>

  **Jinhao Dong**, Tong Lin

# 🎖 Honors and Awards
- *2025*: Selected into the **Wu Yuzhang Young Talents Program (吴玉章青年英才)**, Renmin University of China
- *2023.12*: Exceptional Award for Academic Innovation, Peking University
- *2022.12*: Merit Student, Peking University
- *2022.12*: Ubiquant Scholarship, Peking University
- *2021.12*: Exceptional Award for Academic Innovation, Peking University
- *2021.12*: Sanda Fighting Match, Bronze Medal, Peking University
- *2021.09*: President Scholarship, Peking University
- *2020.09*: President Scholarship, Peking University
- *2020.06*: Outstanding Graduate, Xidian University
- *2019.11*: President Fellowship, Xidian University
- *2018.10*: International Collegiate Programming Contest (ICPC), Bronze Medal
- *2018.04*: Mathematical Contest in Modeling (MCM), Meritorious Winner

# 💬 Invited Talks
- *2023.12*: Excellent Doctor Symposium of CCF ChinaSoft, Shanghai, China

# 💻 Services
**Program Committee Member**

- *2026*: ICSE Research Track
- *2025*: ASE Research Track
- *2024*: ASE Research Track

- *2024*: NeurIPS Main Conference
- *2023*: PRDC Fast Abstract Committee

**Reviewer**

- *2024*: Formal Aspects of Computing (FAC)
- *2024*: Science China Information Sciences (SCIS)

# 🐱 My Cat

Meet **11 (Eleven)**, my American Shorthair kitty. He got his name because I brought him home in **November**, and because I'm a big fan of *Stranger Things* — Eleven is the show's female lead.

这是我的美短小猫 **11 (Eleven)**。之所以叫 11，是因为他是 **11 月**带回家的，也因为我很喜欢《怪奇物语》——Eleven 是剧里的女主角。

<div style="display: flex; gap: 16px; flex-wrap: wrap; align-items: flex-start; margin-top: 12px;">
  <img src="images/cat_11.jpg" alt="11 the cat" style="max-width: 320px; width: 100%; border-radius: 8px;">
  <video src="images/cat_11.mp4" controls muted loop playsinline style="max-width: 320px; width: 100%; border-radius: 8px;"></video>
</div>

# 🥊 Hobbies

- Sanda (Chinese Kickboxing) and Mantis Boxing
- Breaking (Breakdance)
- Hiking and Camping
