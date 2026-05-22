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


<span id="about"></span>
# 👋 Hi !

I am a **tenured Associate Professor** at the [School of Computing and Artificial Intelligence](https://scai.sufe.edu.cn/), [Shanghai University of Finance and Economics (SUFE)](https://www.sufe.edu.cn/). I received my Ph.D. from [The University of Hong Kong](https://www.hku.hk/) in 2018, and my Bachelor's degree from [Tsinghua University](https://www.tsinghua.edu.cn/) in 2013. I have published over 50 papers in top-tier international conferences and high-impact journals, including ACL, EMNLP, ICML, NeurIPS, ICLR, SIGKDD, NAACL, AAAI, TASLP.

My research interests span **Large Language Models**, **Multimodal AI**, **LLM-based Agents**, and **AI for Finance**. Feel free to reach out at [yunchen@sufe.edu.cn](mailto:yunchen@sufe.edu.cn).

<div style="background-color: #d1ecf1; padding:0.6em 0.9em; border-radius:6px; margin-top:0.6em;">
  📣 <strong>Positions available: Master / PhD program students for 2027 fall.</strong><br>
  招收博士生、硕士生，并长期招收访问学生，欢迎有志于研究大模型、智能体、多模态模型和金融科技的同学加入本课题组！请附简历邮件联系。
</div>



<span id="news"></span>
# 🔥 News
- *2026.05*: &nbsp;🎉🎉 One paper accepted by SIGKDD 2026 (Research Track): **SAFT** .
- *2026.05*: &nbsp;🎉🎉 My PhD student [Zeguan Xiao](https://zeguanxiao.github.io/) has successfully completed his thesis defense. Congratulations!
- *2026.05*: &nbsp;🎉🎉 Two papers accepted by ICML 2026: **PRINMIX**.
- *2026.04*: &nbsp;🎉🎉 Ten papers accepted by ACL 2026 (five Main, five Findings).
- *2026.01*: &nbsp;🎉🎉 Two papers accepted by ICLR 2026: **BiasScope** and **InfoScan**.
- *2026.01*: &nbsp;🎉🎉 One paper accepted by ICASSP 2026: **Compound-QA**.
- *2025.12*: &nbsp;Serving as Area Chair for ARR 2026 January.
- *2025.11*: &nbsp;🎉🎉 One paper accepted by AAAI 2026 on uncertainty estimation in LLMs.
- *2025.08*: &nbsp;🎉🎉 One paper accepted by NeurIPS 2025 on LLM-as-a-Judge alignment.
- *2025.08*: &nbsp;🎉🎉 Two papers accepted by EMNLP 2025: **Pi-SQL** and **G2**.
- *2025.07*: &nbsp;Serving as Area Chair for ARR 2025 July.
- *2025.05*: &nbsp;🎉🎉 Three papers accepted by ACL 2025: **ImPart**, **TAG-Instruct**, **FANNO**.
- *2025.01*: &nbsp;🎉🎉 Four papers accepted by NAACL 2025: **MiLoRA**, **SeqAR**, **FinEval**, **LayAlign**.


<span id="publications"></span>
# 📝 Selected Publications 

## 2026

1. **SAFT: Safety-Preserving Adaptation via Fine-Tuning Transfer for Large Language Models**
  Zhiwen Ruan, Yan Yang, Zhuocheng Liang, **Yun Chen**, Guanhua Chen.  *SIGKDD 2026 (CCF-A).*
2. **Principled SVD-based Delta Compression via Quantization Error Minimization**<br>
  Boya Xiong, Shuo Wang, Weifeng Ge, Guanhua Chen, **Yun Chen**. *ICML 2026 (CCF-A).*
3. **Anchored Policy Optimization: Mitigating Exploration Collapse Via Support-Constrained Rectification**
  Tianyi Wang, Long Li, Hongcan Guo, Yibiao Chen, Yixia Li, Yong Wang, **Yun Chen**, Guanhua Chen. *ICML 2026 (CCF-A).*
4. **Modeling LLM Unlearning as an Asymmetric Two-Task Learning Problem**<br>
  Zeguan Xiao, Siqing Li, Yong Wang, Xuetao Wei, Jian Yang, **Yun Chen**, Guanhua Chen. *ACL 2026 Main (CCF-A).*
5. **SPPO: Sequence-Level PPO for Long-Horizon Reasoning Tasks**<br>
  Tianyi Wang, Yixia Li, Long Li, Yibiao Chen, Shaohan Huang, **Yun Chen**, Peng Li, Yang Liu, Guanhua Chen. *ACL 2026 Main (CCF-A).*
6. **GIFT: Guided Fine-Tuning and Transfer for Enhancing Instruction-Tuned Language Models**<br>
  Zhiwen Ruan, Yichao Du, Jianjie Zheng, Longyue Wang, **Yun Chen**, Peng Li, Jinsong Su, Yang Liu, Guanhua Chen. *ACL 2026 Main (CCF-A).*
7. **VFA: Empowering Multilingual MLLMs via Vision-Free Adaptation**<br>
  Yixia Li, Yaqing Shi, Zhiwen Ruan, Dongdong Zhang, Lingjie Jiang, Shaohan Huang, **Yun Chen**, Guanhua Chen, Furu Wei. *ACL 2026 Main (CCF-A).*
8. **InstructDiff: Domain-Adaptive Data Selection via Contrastive Entropy for Efficient LLM Fine-Tuning**<br>
  Junyou Su, He Zhu, Xiao Luo, Liyu Zhang, Hong-Yu Zhou, **Yun Chen**, Peng Li, Yang Liu, Guanhua Chen. *ACL 2026 Main (CCF-A).*
9. **Toward Automated Robustness Evaluation of Mathematical Reasoning**<br>
  Yutao Hou, Zeguan Xiao, Fei Yu, Yihan Jiang, Shuguang Ma, Zhaoqian Dai, Hailiang Huang, **Yun Chen**, Guanhua Chen. *Findings of ACL 2026.*
10. **FinSafetyBench: Evaluating LLM Safety in Real-World Financial Scenarios**<br>
  Yutao Hou, Yihan Jiang, Yuhan Xie, Jian Yang, Liwen Zhang, Hailiang Huang, Guanhua Chen, **Yun Chen**. *Findings of ACL 2026.*
11. **Towards Bridging the Reward-Generation Gap in Direct Alignment Algorithms**<br>
  Zeguan Xiao, **Yun Chen**, Jian Yang, Guanhua Chen, Ke Tang. *Findings of ACL 2026.*
12. **Representation-Guided Parameter-Efficient LLM Unlearning**<br>
  Zeguan Xiao, Lang Mo, **Yun Chen**, Lei Yang, Jiehui Zhao, Lili Yang, Guanhua Chen. *Findings of ACL 2026.*
13. **Beyond Static Rules: Automated Discovery of Latent Vulnerabilities in Text-to-SQL**<br>
  Hanqing Wang, Yongdong Chi, Jian Yang, Lei Yang, Jiehui Zhao, **Yun Chen**, Guanhua Chen. *Findings of ACL 2026.*
14. **BiasScope: Towards Automated Detection of Bias in LLM-as-a-Judge Evaluation**<br>
  Peng Lai, Zhihao Ou, Yong Wang, Longyue Wang, Jian Yang, **Yun Chen**, Guanhua Chen. *ICLR 2026 (CCF-A).*
15. **InfoScan: Information-Efficient Visual Scanning via Resource-Adaptive Walks**<br>
  Yifeng Wu, Huimin Huang, Shangjie Zhou, Yawen Huang, Hao Zheng, **Yun Chen**, Xian Wu, Ruize Han, Guanhua Chen. *ICLR 2026 (CCF-A).*
16. **Compound-QA: A Benchmark for Evaluating LLMs on Compound Questions**<br>
  Yutao Hou, Yajing Luo, Zhiwen Ruan, Hongru Wang, Weifeng Ge, **Yun Chen**, Guanhua Chen. *ICASSP 2026 (CCF-B).*
17. **Enhancing Uncertainty Estimation in LLMs with Expectation of Aggregated Internal Belief**<br>
  Zeguan Xiao, Diyang Dou, Boya Xiong, **Yun Chen**, Guanhua Chen. *AAAI 2026 (CCF-A).*

## 2025

1. **Beyond the Surface: Enhancing LLM-as-a-Judge Alignment with Human via Internal Representations**<br>
  Peng Lai, Jianjie Zheng, Sijie Cheng, **Yun Chen**, Peng Li, Yang Liu, Guanhua Chen. *NeurIPS 2025 (CCF-A).*
2. **G2: Guided Generation for Enhanced Output Diversity in LLMs**<br>
  Zhiwen Ruan, Yixia Li, Yefeng Liu, **Yun Chen**, Weihua Luo, Peng Li, Yang Liu, Guanhua Chen. *EMNLP 2025 Main (CCF-B).* [\[PDF\]](https://aclanthology.org/2025.emnlp-main.713.pdf)
3. **Pi-SQL: Enhancing Text-to-SQL with Fine-Grained Guidance from Pivot Programming Languages**<br>
  Hanqing Wang, Zonghan Yang, Jian Yang, Xiao Yan, **Yun Chen**, Guanhua Chen. *Findings of EMNLP 2025.* [\[PDF\]](https://aclanthology.org/2025.findings-emnlp.1369.pdf)
4. **ImPart: Importance-Aware Delta-Sparsification for Improved Model Compression and Merging in LLMs**<br>
  Yan Yang, Yixia Li, Hongru Wang, Xuetao Wei, Jianqiao Yu, **Yun Chen**, Guanhua Chen. *ACL 2025 Main (CCF-A).* [\[PDF\]](https://aclanthology.org/2025.acl-long.921.pdf)
5. **TAG-Instruct: Controlled Instruction Complexity Enhancement through Structure-Based Augmentation**<br>
  He Zhu, Zhiwen Ruan, Junyou Su, Xingwei He, Wenjia Zhang, **Yun Chen**, Guanhua Chen. *Findings of ACL 2025.* [\[PDF\]](https://aclanthology.org/2025.findings-acl.911.pdf)
6. **FANNO: Augmenting High-Quality Instruction Data with Open-Sourced LLMs Only**<br>
  He Zhu, Yifan Ding, Yicheng Tao, Zhiwen Ruan, Yixia Li, Wenjia Zhang, **Yun Chen**, Guanhua Chen. *Findings of ACL 2025.* [\[PDF\]](https://aclanthology.org/2025.findings-acl.906.pdf)
7. **MiLoRA: Harnessing Minor Singular Components for Parameter-Efficient LLM Finetuning**<br>
  Hanqing Wang, Yixia Li, Shuo Wang, Guanhua Chen, **Yun Chen**. *NAACL 2025 Main (CCF-B).* [\[PDF\]](https://arxiv.org/pdf/2406.09044)
8. **SeqAR: Jailbreak LLMs with Sequential Auto-Generated Characters**<br>
  Yan Yang, Zeguan Xiao, Xin Lu, Hongru Wang, Xuetao Wei, Hailiang Huang, Guanhua Chen, **Yun Chen**. *NAACL 2025 Main (CCF-B).* [\[PDF\]](https://arxiv.org/pdf/2407.01902)
9. **FinEval: A Chinese Financial Domain Knowledge Evaluation Benchmark for Large Language Models**<br>
  Xin Guo, et al., **Yun Chen**, Weining Shen, Liwen Zhang. *NAACL 2025 Main (CCF-B).* [\[PDF\]](https://aclanthology.org/2025.naacl-long.318.pdf)
10. **LayAlign: Enhancing Multilingual Reasoning in LLMs via Layer-Wise Adaptive Fusion and Alignment**<br>
  Zhiwen Ruan, Yixia Li, He Zhu, Longyue Wang, Weihua Luo, Kaifu Zhang, **Yun Chen**, Guanhua Chen. *Findings of NAACL 2025.* [\[PDF\]](https://aclanthology.org/2025.findings-naacl.81.pdf)

## 2024

1. **SeTAR: Out-of-Distribution Detection with Selective Low-Rank Approximation**<br>
  Yixia Li, Boya Xiong, Guanhua Chen, **Yun Chen**. *NeurIPS 2024 (CCF-A).* [\[PDF\]](https://arxiv.org/pdf/2406.12629)
2. **Delta-CoMe: Training-Free Delta-Compression with Mixed-Precision for Large Language Models**<br>
  Bowen Ping, Shuo Wang, Hanqing Wang, Xu Han, Yuzhuang Xu, Yukun Yan, **Yun Chen**, Baobao Chang, Zhiyuan Liu, Maosong Sun. *NeurIPS 2024 (CCF-A).* [\[PDF\]](https://arxiv.org/pdf/2406.08903)
3. **Distract Large Language Models for Automatic Jailbreak Attack**<br>
  Zeguan Xiao, Yan Yang, Guanhua Chen, **Yun Chen**. *EMNLP 2024 Main (CCF-B).* [\[PDF\]](https://arxiv.org/pdf/2403.08424.pdf)
4. **LoRA-Flow: Dynamic LoRA Fusion for Large Language Models in Generative Tasks**<br>
  Hanqing Wang, Bowen Ping, Shuo Wang, Xu Han, **Yun Chen**, Zhiyuan Liu, Maosong Sun. *ACL 2024 Main (CCF-A).* [\[PDF\]](https://arxiv.org/pdf/2402.11455.pdf)
5. **PACIT: Unlocking the Power of Examples for Better In-Context Instruction Tuning**<br>
  Tianci Xue, Ziqi Wang, Yixia Li, **Yun Chen**, Guanhua Chen. *Findings of ACL 2024.*

## 2023

1. **StyleBART: Decorate Pretrained Model with Style Adapters for Unsupervised Stylistic Headline Generation**<br>
  Hanqing Wang, Yajing Luo, Boya Xiong, Guanhua Chen, **Yun Chen**. *Findings of EMNLP 2023.* [\[PDF\]](https://aclanthology.org/2023.findings-emnlp.697.pdf)
2. **mCLIP: Multilingual CLIP via Cross-lingual Transfer**<br>
  Guanhua Chen, Lu Hou, **Yun Chen**, Wenliang Dai, Lifeng Shang, Xin Jiang, Qun Liu, Jia Pan, Wenping Wang. *ACL 2023 (CCF-A).* [\[PDF\]](https://aclanthology.org/2023.acl-long.728.pdf)
3. **Lexical Complexity Controlled Sentence Generation for Language Learning**<br>
  Jinran Nie, Liner Yang, **Yun Chen**, Cunliang Kong, Junhui Zhu, Erhong Yang. *CCL 2023 — Best English Paper Award.* [\[PDF\]](https://arxiv.org/pdf/2211.14540.pdf)

## 2022

1. **XLM-D: Decorate Cross-lingual Pre-training Model as Non-Autoregressive Neural Machine Translation**<br>
  Yong Wang, Shilin He, Guanhua Chen, **Yun Chen**, Daxin Jiang. *EMNLP 2022 Main (CCF-B).* [\[PDF\]](https://aclanthology.org/2022.emnlp-main.466.pdf)
2. **Multilingual Sentence Transformer as A Multilingual Word Aligner**<br>
  Weikang Wang, Guanhua Chen, Hanqing Wang, Yue Han, **Yun Chen**. *Findings of EMNLP 2022 (short).* [\[PDF\]](https://aclanthology.org/2022.findings-emnlp.215.pdf)
3. **Towards Making the Most of Cross-Lingual Transfer for Zero-Shot Neural Machine Translation**<br>
  Guanhua Chen, Shuming Ma, **Yun Chen**, Li Dong, Dongdong Zhang, Jia Pan, Wenping Wang, Furu Wei. *ACL 2022 Main (CCF-A).* [\[PDF\]](https://aclanthology.org/2022.acl-long.12.pdf)
4. **Multitasking Framework for Unsupervised Simple Definition Generation**<br>
  Cunliang Kong, **Yun Chen**, Hengyuan Zhang, Liner Yang, Erhong Yang. *ACL 2022 Main (CCF-A).* [\[PDF\]](https://aclanthology.org/2022.acl-long.409.pdf)

## 2021

1. **Zero-shot Cross-lingual Transfer of Neural Machine Translation with Multilingual Pretrained Encoders**<br>
  Guanhua Chen, Shuming Ma, **Yun Chen**, Li Dong, Dongdong Zhang, Jia Pan, Wenping Wang, Furu Wei. *EMNLP 2021 Main (CCF-B).* [\[PDF\]](https://aclanthology.org/2021.emnlp-main.2.pdf)
2. **Lexically Constrained Neural Machine Translation with Explicit Alignment Guidance**<br>
  Guanhua Chen, **Yun Chen**, Victor O.K. Li. *AAAI 2021 (CCF-A).* [\[PDF\]](https://cdn.aaai.org/ojs/17496/17496-13-20990-1-2-20210518.pdf)

## 2020

1. **Accurate Word Alignment Induction from Neural Machine Translation**<br>
  **Yun Chen**, Yang Liu, Guanhua Chen, Xin Jiang, Qun Liu. *EMNLP 2020 Main (CCF-B).* [\[PDF\]](http://aclweb.org/anthology/2020.emnlp-main.42.pdf)
2. **Lexical-Constraint-Aware Neural Machine Translation via Data Augmentation**<br>
  Guanhua Chen, **Yun Chen**, Yong Wang, Victor O.K. Li. *IJCAI 2020 (CCF-A).* [\[PDF\]](https://www.ijcai.org/proceedings/2020/0496.pdf)
3. **Perturbed Masking: Parameter-Free Probing for Analyzing and Interpreting BERT**<br>
  Zhiyong Wu, **Yun Chen**, Ben Kao, Qun Liu. *ACL 2020 Main (CCF-A).* [\[PDF\]](https://arxiv.org/pdf/2004.14786)
4. **Reinforced Zero-shot Cross-lingual Neural Headline Generation**<br>
  Ayana, **Yun Chen**, Cheng Yang, Zhiyuan Liu, Maosong Sun. *IEEE TASLP 2020 (CCF-B).* [\[PDF\]](https://ieeexplore.ieee.org/document/9142327)
5. **Incorporating Sememes into Chinese Definition Modeling**<br>
  Liner Yang, Cunliang Kong, **Yun Chen**, Yang Liu, Qinan Fan, Erhong Yang. *IEEE TASLP 2020 (CCF-B).* [\[PDF\]](https://ieeexplore.ieee.org/document/9072279)

## 2018

1. **A Stable and Effective Learning Strategy for Trainable Greedy Decoding**<br>
  **Yun Chen**, Victor O.K. Li, Kyunghyun Cho, Samuel R. Bowman. *EMNLP 2018 Main (CCF-B).* [\[arXiv\]](https://arxiv.org/abs/1804.07915)
2. **Meta-Learning for Low-Resource Neural Machine Translation**<br>
  Jiatao Gu, Yong Wang, **Yun Chen**, Victor O.K. Li, Kyunghyun Cho. *EMNLP 2018 Main (CCF-B).* [\[arXiv\]](https://arxiv.org/abs/1808.08437)
3. **Zero-Resource Neural Machine Translation with Multi-Agent Communication Game**<br>
  **Yun Chen**, Yang Liu, Victor O.K. Li. *AAAI 2018 (CCF-A).* [\[arXiv\]](https://arxiv.org/abs/1802.03116)
4. **Stable and Effective Trainable Greedy Decoding for Sequence to Sequence Learning**<br>
  **Yun Chen**, Kyunghyun Cho, Samuel R. Bowman, Victor O.K. Li. *ICLR Workshop 2018.* [\[OpenReview\]](https://openreview.net/forum?id=rJZlKFkvM)
5. **Zero-Shot Cross-Lingual Neural Headline Generation**<br>
  Ayana, Shiqi Shen, **Yun Chen**, Cheng Yang, Zhiyuan Liu, Maosong Sun. *IEEE TASLP 2018 (CCF-B).* [\[PDF\]](https://ieeexplore.ieee.org/document/8370729/)

## 2017

1. **A Teacher-Student Framework for Zero-Resource Neural Machine Translation**<br>
  **Yun Chen**, Yang Liu, Yong Cheng, Victor O.K. Li. *ACL 2017 Main (CCF-A).* [\[PDF\]](http://aclweb.org/anthology/P17-1176)



<!-- # 🎓 Education
- *2014.09 – 2018.06*, Ph.D., Department of Electrical and Electronic Engineering, **The University of Hong Kong**.
- *2009.09 – 2013.06*, B.Eng., **Tsinghua University**, Beijing. -->

<span id="grants"></span>
# 💸 Research Grants (as PI)

- National Natural Science Foundation of China (NSFC) - Young Scientists Fund
- National Natural Science Foundation of Shanghai - Young Scientists Fund
- Shanghai Youth Science and Technology Talent Sailing Program


<span id="awards"></span>
# 🏆 Awards

- Outstanding Young Female Scholar of SUFE（2025）
- Excellent Supervisor of Graduation Thesis（2025）
- Star Scholar Program of MSRA (2023)
- Best English Paper Award of CCL (2023) 
- Overseas High-Level Talents of Shanghai（2020）


<span id="service"></span>
# 👨‍🏫 Academic Service

- Long-term Area Chair for ACL Rolling Review.
- Long-term reviewer for CCF Class A conferences including ICML, ICLR, KDD, AAAI.
- Long-term reviewer for journals inlcuding TPAMI, AIJ, FCS, TALLIP.

  
<span id="students"></span>
# 👥 Graduate Student Supervision

Supervised 13 graduate students, with 2 graduates to date. Notable student achievements include:
- Two graduent students received the Academic Star Award of SUFE (Hanqing Wang 2025; one of five university-wide recipients) and the Academic Star Nomination Award of SUFE (Yan Yang 2025; one of ten university-wide recipients).
- One master student (Boya Xiong 2026) was honored as a 'Shanghai Outstanding Graduate'.
- Two master students (Yan Yang 2026, Yajing Luo 2025) and one PhD student (Zeguan Xiao 2026) were honored as 'Outstanding Graduates of SUFE'.
- Two graduent students received National Scholarship (Yan Yang 2025, Hanqing Wang 2025).
- One undergraduate student (Jiayang Li 2025) received the 'Outstanding Graduation Thesis of SUFE'.


<!-- # 👥 Students

### Current

*To be added.*

### Alumni

*To be added.* -->
