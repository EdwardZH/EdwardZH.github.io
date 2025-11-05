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

Zhenghao Liu (刘正皓), Associate Professor of Northeastern University, is a visiting researcher at Tsinghua University's Natural Language Processing Laboratory (<a href="http://nlp.csai.tsinghua.edu.cn" target="_blank">THUNLP</a>). I obtained my Bachelor's degree in Engineering from Northeastern University in 2016 and was directly admitted to Tsinghua University's State Key Laboratory of Intelligent Technology and Systems as a Ph.D. student, under the supervision of Professor Sun Maosong. My main research interests include natural language processing and information retrieval, and I earned my Ph.D. degree from Tsinghua University in 2021 (<A href="./slides/lzh_thesis.pdf" target="_blank">thesis</A>).

I work with Ge Yu (<a href="https://scholar.google.com/citations?user=HClMOmUAAAAJ" target="_blank">于戈</a>) and Yu Gu (<a href="https://scholar.google.com/citations?user=IDYbTZwAAAAJ" target="_blank">谷峪</a>). I also collaborate with Zhiyuan Liu (<a href="https://scholar.google.com/citations?user=dT0v5u0AAAAJ" target="_blank">刘知远</a>), Chenyan Xiong (<a href="https://scholar.google.com/citations?user=E9BaEBYAAAAJ" target="_blank">熊辰炎</a>), Shuo Wang (<a href="https://scholar.google.com/citations?user=5vm5yAMAAAAJ" target="_blank">王硕</a>), Yukun Yan (<a href="https://scholar.google.com/citations?user=B88nSvIAAAAJ" target="_blank">闫宇坤</a>), Shi Yu (<a href="https://scholar.google.com/citations?user=xcMVPTgAAAAJ" target="_blank">于是</a>), Liner Yang (<a href="https://scholar.google.com/citations?user=mupyk1sAAAAJ" target="_blank">杨麟儿</a>), and Zulong Chen (<a href="https://scholar.google.com/citations?user=nUVmSqUAAAAJ" target="_blank">陈祖龙</a>) from Tsinghua University, Carnegie Mellon University, Beijing Language and Culture University, and Alibaba closely. I have published more than 30 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=4vrZRk0AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>. 

# 🔥 News
- *2025.10*: &nbsp; Our paper has been awarded the Best Paper Award at the 2025 International Conference on Advanced Data Mining and Applications (ADMA 2025)! 🏆 
- *2025.01*: &nbsp;🎉🎉  <a href="https://github.com/OpenBMB/UltraRAG" target="_blank">UltraRAG 2.0 (MCP version)</a> has been officially released—a modular RAG framework built on the Model Context Protocol with native pipeline control!
- *2024.09*: &nbsp;🎉🎉 We are excited to announce the release of the MiniCPM-RAG LoRA Toolkit, which has already garnered over 320,000 downloads!


# 📖 Educations
- *Aug, 2021 - Now*, Dept. of Computer Science and Technology (<a href="https://neuir.github.io" target="_blank">NEUIR Lab</a>), Northeastern University, Shenyang, China. 
- *Aug, 2016 - Jun, 2021*, Dept. of Computer Science and Technology (<a href="http://nlp.csai.tsinghua.edu.cn" target="_blank">THUNLP Lab</a>), Tsinghua University, Beijing, China. Supervisor: Maosong Sun (<a href="https://scholar.google.com/citations?user=zIgT0HMAAAAJ" target="_blank">孙茂松</a>).
- *Sep, 2012 - Jul, 2016*, Dept. of Computer Science and Technology, Northeastern University, Shenyang, China. 


# 💬 Invited Talks
- *2024.08*, "Introduction to Large Language Models". THUNLP-OpenBMB Summer Course [<A href="https://nlp.csai.tsinghua.edu.cn/summer_class/">link</A>].
- *2023.08*, "Semantic Matching based Retrieval for Multimodal Documents". The 17th China Conference on Knowledge Graph and Semantic Computing (CCKS 2023) [<A href="./slides/CCKS2023.pdf" target="_blank">slides</A>].
- *2021.04*, "From Exact Matching to Semantic Matching: Using neural models for ranking". Hong Kong University of Science and Technology (HKUST) [<A href="./slides/hkust_neuir.pdf" target="_blank">slides</A>].


# 🧑‍🎨 Academic Services
- Session Chair of ACL 2024, MLNLP 2022-2024.
- Web Chair of CCL 2024.
- Publication Chair of ACL 2025, CCL 2025.
- Poster Chair of WISA 2024.
- Area Chair of ACL ARR, ICLR, COLING, ICTIR.
- Conference Review: NeurIPS, ICML, ICLR, ACL, EMNLP, NAACL, COLING, WebConf, ECAI, AAAI, EACL, COLM.
- Journal Review: TPAMI, TKDE, FCS, IEEE Transactions on Big Data, AI Open, TOIS, Science China.



# 📝 Publications 

 <ul>
 * indicates equal contribution.
 </ul>
 <ul>
 # indicates corresponding author.
 </ul>

<h3><strong>2025</strong></h3>

- Mingyan Wu, <b>Zhenghao Liu</b>#, Yukun Yan, Xinze Li, Shi Yu, Zheni Zeng, Yu Gu, Ge Yu. RankCoT: Refining Knowledge for Retrieval-Augmented Generation through Ranking Chain-of-Thoughts. <i> ACL 2025. </i> [<A href="https://aclanthology.org/2025.acl-long.629.pdf" target="_blank">pdf</A>][<A href="https://github.com/NEUIR/RankCoT" target="_blank">codes</A>].

- Shuliang Liu, Xinze Li, <b>Zhenghao Liu</b>#, Yukun Yan, Cheng Yang, Zheni Zeng, Zhiyuan Liu, Maosong Sun, Ge Yu. Judge as A Judge: Improving the Evaluation of Retrieval-Augmented Generation through the Judge-Consistency of Large Language Models. <i> ACL 2025: Findings. </i> [<A href="https://aclanthology.org/2025.findings-acl.301.pdf" target="_blank">pdf</A>][<A href="https://github.com/OpenBMB/ConsJudge" target="_blank">codes</A>].

- Kunlun Zhu, Yifan Luo, Dingling Xu, Yukun Yan, <b>Zhenghao Liu</b>, Shi Yu, Ruobing Wang, Shuo Wang, Yishan Li, Nan Zhang, Xu Han, Zhiyuan Liu, Maosong Sun. RAGEval: Scenario Specific RAG Evaluation Dataset Generation Framework. <i> ACL 2025. </i> [<A href="https://aclanthology.org/2025.acl-long.418.pdf" target="_blank">pdf</A>][<A href="https://github.com/OpenBMB/RAGEval" target="_blank">codes</A>].


- Qiushi Xiong, Zhipeng Xu, <b>Zhenghao Liu</b>#, Mengjia Wang, Zulong Chen, Yue Sun, Yu Gu, Xiaohua Li, Ge Yu. Enhancing the Patent Matching Capability of Large Language Models via the Memory Graph. <i> SIGIR 2025. </i> [<A href="https://dl.acm.org/doi/10.1145/3726302.3729970" target="_blank">pdf</A>][<A href="https://github.com/NEUIR/MemGraph" target="_blank">codes</A>].


- Pengcheng Huang, <b>Zhenghao Liu</b>#, Yukun Yan, Haiyan Zhao, Xiaoyuan Yi, Hao Chen, Zhiyuan Liu, Maosong Sun, Tong Xiao, Ge Yu, Chenyan Xiong. ParamMute: Suppressing Knowledge-Critical FFNs for Faithful Retrieval-Augmented Generation. <i> NeurIPS 2025. </i> [<A href="https://openreview.net/forum?id=CyUq9D99vE" target="_blank">pdf</A>][<A href="https://openreview.net/forum?id=CyUq9D99vE" target="_blank">codes</A>].


- Xiaoang Xu, Shuo Wang, Xu Han, <b>Zhenghao Liu</b>, Huijia Wu, Peipei Li, Zhiyuan Liu, Maosong Sun, Zhaofeng He. A\*-Thought: Efficient Reasoning via Bidirectional Compression for Low-Resource Settings. <i> NeurIPS 2025. </i> [<A href="https://arxiv.org/abs/2505.24550" target="_blank">pdf</A>][<A href="https://github.com/AI9Stars/AStar-Thought" target="_blank">codes</A>].


- Xinze Li\*, Sen Mei\*, <b>Zhenghao Liu</b>#, Yukun Yan#, Shuo Wang, Shi Yu, Zheni Zeng, Hao Chen, Ge Yu, Zhiyuan Liu, Maosong Sun, Chenyan Xiong. RAG-DDR: Optimizing Retrieval-Augmented Generation Using Differentiable Data Rewards. <i> ICLR 2025. </i> [<A href="https://arxiv.org/abs/2410.13509" target="_blank">pdf</A>][<A href="https://github.com/OpenMatch/RAG-DDR" target="_blank">codes</A>].

- Shi Yu, Chaoyue Tang, Bokai Xu, Junbo Cui, Junhao Ran, Yukun Yan, <b>Zhenghao Liu</b>, Shuo Wang, Xu Han, Zhiyuan Liu, Maosong Sun. VisRAG: Vision-based Retrieval-augmented Generation on Multi-modality Documents. <i> ICLR 2025. </i> [<A href="https://arxiv.org/pdf/2410.10594" target="_blank">pdf</A>][<A href="https://github.com/openbmb/visrag" target="_blank">codes</A>].

- Lifan Yuan, Ganqu Cui, Hanbin Wang, Ning Ding, Xingyao Wang, Jia Deng, Boji Shan, Huimin Chen, Ruobing Xie, Yankai Lin, <b>Zhenghao Liu</b>, Bowen Zhou, Hao Peng, Zhiyuan Liu, Maosong Sun. Advancing llm reasoning generalists with preference trees. <i> ICLR 2025. </i> [<A href="https://arxiv.org/pdf/2404.02078" target="_blank">pdf</A>][<A href="https://github.com/OpenBMB/Eurus" target="_blank">codes</A>].

- <b>Zhenghao Liu</b>, Xingsheng Zhu, Tianshuo Zhou, Xinyi Zhang, Xiaoyuan Yi, Yukun Yan, Ge Yu, Maosong Sun. Benchmarking Retrieval-Augmented Generation in Multi-Modal Contexts. <i> MM 2025. </i> [<A href="https://dl.acm.org/doi/10.1145/3746027.3755625" target="_blank">pdf</A>][<A href="https://github.com/NEUIR/M2RAG" target="_blank">codes</A>].

- Sijia Yao\*, Pengcheng Huang\*,  <b>Zhenghao Liu</b>#, Yu Gu, Yukun Yan, Shi Yu, Ge Yu. ExpandR: Teaching Dense Retrievers Beyond Queries with LLM Guidance. <i> EMNLP 2025. </i> [<A href="https://aclanthology.org/2025.emnlp-main.963/" target="_blank">pdf</A>][<A href="https://github.com/NEUIR/ExpandR" target="_blank">codes</A>].

- Hao Chen\*, Yukun Yan\*, Sen Mei, Wanxiang Che#, <b>Zhenghao Liu</b>#, Qi Shi, Xinze Li, Yuchun Fan, Pengcheng Huang, Qiushi Xiong, Zhiyuan Liu, Maosong Sun. ClueAnchor: Clue-Anchored Knowledge Reasoning Exploration and Optimization for Retrieval-Augmented Generation. <i> EMNLP 2025: Findings. </i> [<A href="https://aclanthology.org/2025.findings-emnlp.1049/" target="_blank">pdf</A>][<A href="https://github.com/thunlp/ClueAnchor" target="_blank">codes</A>].

- Zhensheng Jin\*, Xinze Li\*, Yifan Ji, Chunyi Peng, <b>Zhenghao Liu</b>#, Qi Shi, Yukun Yan, Shuo Wang, Furong Peng, Ge Yu. ReCUT: Balancing Reasoning Length and Accuracy in LLMs via Stepwise Trails and Preference Optimization. <i> EMNLP 2025: Findings. </i> [<A href="https://aclanthology.org/2025.findings-emnlp.770/" target="_blank">pdf</A>][<A href="https://github.com/NEUIR/ReCUT" target="_blank">codes</A>].

- Zheni Zeng, Jiayi Chen, Huimin Chen, Yukun Yan, Yuxuan Chen, <b>Zhenghao Liu</b>, Zhiyuan Liu, Maosong Sun. PersLLM: A Personified Training Approach for Large Language Models. <i> EMNLP 2025: Findings. </i> [<A href="https://aclanthology.org/2025.findings-emnlp.457/" target="_blank">pdf</A>][<A href="https://github.com/Ellenzzn/PersLLM" target="_blank">codes</A>].

- Ruobing Wang, Qingfei Zhao, Yukun Yan, Daren Zha, Yuxuan Chen, Shi Yu, <b>Zhenghao Liu</b>, Yixuan Wang, Shuo Wang, Xu Han, Zhiyuan Liu, Maosong Sun. DeepNote: Note-Centric Deep Retrieval-Augmented Generation. <i> EMNLP 2025: Findings. </i> [<A href="https://aclanthology.org/2025.findings-emnlp.1073/" target="_blank">pdf</A>][<A href="https://github.com/thunlp/DeepNote" target="_blank">codes</A>].

- Zheni Zeng\*, Yuxuan Chen\*, Shi Yu, Ruobing Wang, Yukun Yan, <b>Zhenghao Liu</b>, Shuo Wang, Xu Han, Zhiyuan Liu, Maosong Sun. KBAlign: Efficient Self Adaptation on Specific Textual Knowledge Bases. <i> EMNLP 2025: Findings. </i> [<A href="https://aclanthology.org/2025.findings-emnlp.728/" target="_blank">pdf</A>][<A href="https://github.com/thunlp/KBAlign" target="_blank">codes</A>].


- Weiqing Yang, Hanbin Wang, <b>Zhenghao Liu</b>#, Xinze Li, Yukun Yan, Shuo Wang, Yu Gu, Minghe Yu, Zhiyuan Liu, Ge Yu. COAST: Enhancing the Code Debugging Ability of LLMs through Communicative Agent Based Data Synthesis. <i> NAACL 2025: Findings. </i> [<A href="https://arxiv.org/abs/2408.05006" target="_blank">pdf</A>][<A href="https://github.com/NEUIR/COAST" target="_blank">codes</A>].

- Mingxing Shao, Tiancheng Zhang, Minghe Yu, <b>Zhenghao Liu</b>, Yifang Yin, Hengyu Liu, Ge Yu. Leveraging Student Profiles and the Mamba Framework to Enhance Knowledge Tracing. <i> ECML-PKDD 2025. </i> [<A href="https://link.springer.com/chapter/10.1007/978-3-032-06109-6_12" target="_blank">pdf</A>][<A href="https://github.com/collegestu1231/DGMKT/tree/master" target="_blank">codes</A>].


- Yifan Ji\*, Zhipeng Xu\*, <b>Zhenghao Liu</b>#, Yukun Yan, Shi Yu, Yishan Li, Zhiyuan Liu, Yu Gu, Ge Yu, Maosong Sun. Learning Refined Document Representations for Dense Retrieval via Deliberate Thinking. <i> SIGIR-AP 2025. </i> [<A href="https://arxiv.org/abs/2502.12974" target="_blank">pdf</A>][<A href="https://github.com/OpenBMB/DEBATER" target="_blank">codes</A>].



<h3><strong>2024</strong></h3>

- Zhipeng Xu, <b>Zhenghao Liu</b>#, Yukun Yan, Zhiyuan Liu, Ge Yu, Chenyan Xiong. Cleaner Pretraining Corpus Curation with Neural Web Scraping. <i> ACL 2024. </i> [<A href="https://arxiv.org/abs/2402.14652" target="_blank">pdf</A>][<A href="https://github.com/OpenMatch/NeuScraper" target="_blank">codes</A>].

- Tianshuo Zhou, Sen Mei, Xinze Li, <b>Zhenghao Liu</b>#, Chenyan Xiong, Zhiyuan Liu, Yu Gu, Ge Yu. MARVEL: Unlocking the Multi-Modal Capability of Dense Retrieval via Visual Module Plugin. <i> ACL 2024. </i> [<A href="https://arxiv.org/abs/2310.14037" target="_blank">pdf</A>][<A href="https://github.com/OpenMatch/MARVEL" target="_blank">codes</A>].

- Hanbin Wang, <b>Zhenghao Liu</b>#, Shuo Wang, Ganqu Cui, Ning Ding, Zhiyuan Liu, Ge Yu . INTERVENOR: Prompting the Coding Ability of Large Language Models with the Interactive Chain of Repair. <i> ACL 2024: Findings. </i> [<A href="https://arxiv.org/abs/2311.09868" target="_blank">pdf</A>][<A href="https://github.com/NEUIR/INTERVENOR" target="_blank">codes</A>].

- Haoyu Wang, Shuo Wang, Yukun Yan, Xujia Wang, Zhiyu Yang, Yuzhuang Xu, <b>Zhenghao Liu</b>, Liner Yang, Ning Ding, Xu Han, Zhiyuan Liu, Maosong Sun. UltraLink: An Open-Source Knowledge-Enhanced Multilingual Supervised Fine-tuning Dataset. <i> ACL 2024. </i> [<A href="https://arxiv.org/abs/2402.04588" target="_blank">pdf</A>][<A href="https://github.com/OpenBMB/UltraLink" target="_blank">codes</A>].

- Zhiyu Yang, Zihan Zhou, Shuo Wang, Xin Cong, Xu Han, Yukun Yan, <b>Zhenghao Liu</b>, Zhixing Tan, Pengyuan Liu, Dong Yu, Zhiyuan Liu, Xiaodong Shi, Maosong Sun. MatPlotAgent: Method and Evaluation for LLM-Based Agentic Scientific Data Visualization. <i> ACL 2024: Findings. </i> [<A href="https://arxiv.org/abs/2402.11453" target="_blank">pdf</A>][<A href="https://github.com/thunlp/MatPlotAgent" target="_blank">codes</A>].

- <b>Zhenghao Liu</b>, Zulong Chen\*, Moufeng Zhang\*, Shaoyang Duan, Hong Wen, Liangyue Li, Nan Li, Yu Gu, Ge Yu. Modeling User Viewing Flow Using Large Language Models for Article Recommendation. <i> WebConf 2024. </i> [<A href="https://arxiv.org/abs/2311.07619" target="_blank">pdf</A>].

- Na Guo, Yaqi Wang, Wenli Sun, Yu Gu, Jianzhong Qi, <b>Zhenghao Liu</b>, Xiufeng Xia, Ge Yu. Chameleon: Towards Update-Efficient Learned Indexing for Locally Skewed Data. <i> ICDE 2024. </i> [<A href="https://ieeexplore.ieee.org/abstract/document/10597777/" target="_blank">pdf</A>].

- Cheng Gao, Chaojun Xiao, <b>Zhenghao Liu</b>, Huimin Chen, Zhiyuan Liu, Maosong Sun. Enhancing Legal Case Retrieval via Scaling High-quality Synthetic Query-Candidate Pairs. <i> EMNLP 2024. </i> [<A href="https://aclanthology.org/2024.emnlp-main.402.pdf" target="_blank">pdf</A>][<A href="https://github.com/thunlp/LEAD" target="_blank">codes</A>].

- Shi Yu, Chenghao Fan, Chenyan Xiong, David Jin, Zhiyuan Liu, <b>Zhenghao Liu#</b>. Fusion-in-T5: Unifying Variant Signals for Simple and Effective Document Ranking with Attention Fusion. <i> COLING 2024. </i> [<A href="https://arxiv.org/abs/2305.14685" target="_blank">pdf</A>][<A href="https://github.com/OpenMatch/FiT5" target="_blank">codes</A>].


- Ruining Chong, Luming Lu, Liner Yang, Jinran Nie, <b>Zhenghao Liu</b>, Shuo Wang, Shuhan Zhou, Yaoxin Li, Erhong Yang. MCTS: A Multi-Reference Chinese Text Simplification Dataset. <i> COLING 2024. </i> [<A href="https://arxiv.org/abs/2306.02796" target="_blank">pdf</A>][<A href="https://github.com/blcuicall/mcts/" target="_blank">codes</A>].

- Cheng Qian, Chenyan Xiong, <b>Zhenghao Liu</b>, Zhiyuan Liu. Toolink: Linking toolkit creation and using through chain-of-solving on open-source model. <i> NAACL 2024. </i> [<A href="https://arxiv.org/abs/2310.05155" target="_blank">pdf</A>][<A href="https://github.com/qiancheng0/Toolink" target="_blank">codes</A>].

- Xinze Li, Hanbin Wang, <b>Zhenghao Liu</b>#, Shi Yu, Shuo Wang, Yukun Yan, Yukai Fu, Yu Gu, Ge Yu. Building A Coding Assistant via the Retrieval-Augmented Language Model. <i> ACM Transactions on Information Systems (TOIS). </i> [<A href="https://dl.acm.org/doi/abs/10.1145/3695868" target="_blank">pdf</A>][<A href="https://github.com/NEUIR/CONAN" target="_blank">code</A>].

- Yumeng Song, Yu Gu, Tianyi Li, Jianzhong Qi, <b>Zhenghao Liu</b>, Christian S Jensen, Ge Yu. CHGNN: A Semi-Supervised Contrastive Hypergraph Learning Network. <i> IEEE Transactions on Knowledge and Data Engineering (TKDE). </i> [<A href="https://ieeexplore.ieee.org/abstract/document/10478209" target="_blank">pdf</A>][<A href="https://github.com/yumengs-exp/CHGNN" target="_blank">code</A>].

- Yuqing Lan, <b>Zhenghao Liu</b>#, Yu Gu#, Xiaoyuan Yi, Xiaohua Li, Liner Yang, Ge Yu. Multi-Evidence based Fact Verification via A Confidential Graph Neural Network. <i> IEEE Transactions on Big Data (TBD). </i> [<A href="https://ieeexplore.ieee.org/abstract/document/10535226" target="_blank">pdf</A>][<A href="https://github.com/NEUIR/CO-GAT" target="_blank">code</A>].


<h3><strong>2023</strong></h3>

- <b>Zhenghao Liu</b>, Chenyan Xiong, Yuanhuiyi Lv, Zhiyuan Liu, Ge Yu. Universal Multi-Modal Retrieval: Learning A Unified Representation Space for Vision Language Retrieval. <i> ICLR 2023. </i> [<A href="https://openreview.net/pdf?id=PQOlkgsBsik" target="_blank">pdf</A>][<A href="https://github.com/OpenMatch/UniVL-DR" target="_blank">codes</A>].

- <b>Zhenghao Liu\*#</b>, Sen Mei\*, Chenyan Xiong, Xiaohua Li, Shi Yu, Zhiyuan Liu, Yu Gu, Ge Yu. Text Matching Improves Sequential Recommendation by Reducing Popularity Biases. <i> CIKM 2023. </i> [<A href="https://dl.acm.org/doi/abs/10.1145/3583780.3615077" target="_blank">pdf</A>][<A href="https://github.com/OpenMatch/TASTE" target="_blank">codes</A>].


- Shi Yu, <b>Zhenghao Liu</b>, Chenyan Xiong, Zhiyuan Liu. OpenMatch-v2: An All-in-one Multi-Modality PLM-based Information Retrieval Toolkit. <i> SIGIR 2023. </i> [<A href="https://dl.acm.org/doi/10.1145/3539618.3591813" target="_blank">pdf</A>][<A href="https://github.com/OpenMatch/OpenMatch" target="_blank">codes</A>].

- Xinze Li, <b>Zhenghao Liu</b>#, Chenyan Xiong, Shi Yu, Yu Gu, Zhiyuan Liu, Ge Yu. Structure-Aware Language Model Pretraining Improves Dense Retrieval on Structured Data. <i>  ACL 2023: Findings. </i> [<A href="https://aclanthology.org/2023.findings-acl.734" target="_blank">pdf</A>][<A href="https://github.com/OpenMatch/SANTA" target="_blank">codes</A>].

- Ruining Chong, Cunliang Kong, Liu Wu, <b>Zhenghao Liu</b>, Ziye Jin, Liner Yang, Yange Fan, Hanghang Fan, Erhong Yang. Leveraging Prefix Transfer for Multi-Intent Text Revision. <i> ACL 2023. </i> [<A href="https://aclanthology.org/2023.acl-short.105/" target="_blank">pdf</A>].

<h3><strong>2022</strong></h3>

- <b>Zhenghao Liu</b>, Han Zhang, Chenyan Xiong, Zhiyuan Liu, Yu Gu, Xiaohua Li. Dimension Reduction for Efficient Dense Retrieval via Conditional Autoencoder. <i> EMNLP 2022. </i> [<A href="https://arxiv.org/abs/2205.03284" target="_blank">pdf</A>][<A href="https://github.com/NEUIR/ConAE" target="_blank">codes</A>].

- Xiaomeng Hu, Shi Yu, Chenyan Xiong, <b>Zhenghao Liu</b>#, Zhiyuan Liu, Ge Yu. P3 Ranker: Mitigating the Gaps between Pre-training and Ranking Fine-tuning with Prompt-based Learning and Pre-finetuning. <i> SIGIR 2022. </i> [<A href="https://arxiv.org/abs/2205.01886" target="_blank">pdf</A>][<A href="https://github.com/NEUIR/P3Ranker" target="_blank">codes</A>].

<h3><strong>2021</strong></h3>

- <b>Zhenghao Liu</b>, Xiaoyuan Yi, Maosong Sun, Liner Yang, Tat-Seng Chua. Neural Quality Estimation with Multiple Hypotheses for Grammatical Error Correction. <i> NAACL 2021. </i> [<A href="https://arxiv.org/pdf/2105.04443" target="_blank">pdf</A>][<A href="https://github.com/thunlp/VERNet" target="_blank">codes</A>].


- <b>Zhenghao Liu</b>\*, Kaitao Zhang\*, Chenyan Xiong, Zhiyuan Liu, Maosong Sun. OpenMatch: An Open Source Library for Neu-IR Research. <i>SIGIR 2021. </i> [<A href="https://arxiv.org/abs/2102.00166" target="_blank">pdf</A>][<A href="https://github.com/thunlp/OpenMatch" target="_blank">codes</A>].

- Shi Yu\*, <b>Zhenghao Liu</b>\*, Chenyan Xiong, Tao Feng, Zhiyuan Liu. Few-Shot Conversational Dense Retrieval. <i>SIGIR 2021.</i> [<A href="https://arxiv.org/abs/2105.04166" target="_blank">pdf</A>][<A href="https://github.com/thunlp/ConvDR" target="_blank">codes</A>].

- Yizhi Li\*, <b>Zhenghao Liu</b>\*, Chenyan Xiong, Zhiyuan Liu. More Robust Dense Retrieval with Contrastive Dual Learning. <i>The 2021 ACM SIGIR International Conference on the Theory of Information Retrieval (ICTIR 2021).</i> [<A href="https://arxiv.org/pdf/2107.07773" target="_blank">pdf</A>][<A href="https://github.com/thunlp/DANCE" target="_blank">codes</A>].

- Si Sun\*, <b>Zhenghao Liu</b>\*, Chenyan Xiong, Zhiyuan Liu and Jie Bao. Capturing Global Informativeness in Open Domain Keyphrase Extraction. <i>The CCF Conference on Natural Language Processing and Chinese Computing (NLPCC 2021).</i> [<A href="https://arxiv.org/pdf/2004.13639" target="_blank">pdf</A>][<A href="https://github.com/thunlp/BERT-KPE" target="_blank">codes</A>].


- Si Sun, Yingzhuo Qian, <b>Zhenghao Liu</b>, Chenyan Xiong, Kaitao Zhang, Jie Bao, Zhiyuan Liu, Paul Bennett. Few-Shot Text Ranking with Meta Adapted Synthetic Weak Supervision. <i>ACL 2021. </i> [<A href="https://arxiv.org/abs/2012.14862" target="_blank">pdf</A>][<A href="https://github.com/thunlp/MetaAdaptRank" target="_blank">codes</A>].

- Huiyuan Xie, <b>Zhenghao Liu</b>, Chenyan Xiong, Zhiyuan Liu and Ann Copestake
. TIAGE: A Benchmark for Topic-Shift Aware Dialog Modeling. <i>EMNLP 2021: Findings. </i> [<A href="https://arxiv.org/pdf/2109.04562" target="_blank">pdf</A>][<A href="https://github.com/HuiyuanXie/tiage" target="_blank">codes</A>]



<h3><strong>2020</strong></h3>

- <b>Zhenghao Liu</b>, Chenyan Xiong, Maosong Sun, Zhiyuan Liu. Fine-grained Fact Verification with Kernel Graph Attention Network. <i>ACL 2020. </i> [<A href="https://www.aclweb.org/anthology/2020.acl-main.655" target="_blank">pdf</A>][<A href="https://github.com/thunlp/KernelGAT" target="_blank">codes</A>].

- <b>Zhenghao Liu</b>, Chenyan Xiong, Zhuyun Dai, Si Sun, Maosong Sun, Zhiyuan Liu. Adapting Open Domain Fact Extraction and Verification to COVID-FACT through In-Domain Language Modeling. <i>EMNLP 2020: Findings. </i> [<A href="https://www.aclweb.org/anthology/2020.findings-emnlp.216" target="_blank">pdf</A>][<A href="https://github.com/thunlp/KernelGAT" target="_blank">codes</A>].

- Houyu Zhang\*, <b>Zhenghao Liu</b>\*, Chenyan Xiong, Zhiyuan Liu. Grounded Conversation Generation as Guided Traverses in Commonsense Knowledge Graphs. <i>ACL 2020. </i> [<A href="https://www.aclweb.org/anthology/2020.acl-main.184" target="_blank">pdf</A>][<A href="https://github.com/thunlp/ConceptFlow/" target="_blank">codes</A>].

- Chenyan Xiong\*, <b>Zhenghao Liu</b>\*, Si Sun\*, Zhuyun Dai\*, Kaitao Zhang\*, Shi Yu\*, Zhiyuan Liu, Hoifung Poon, Jianfeng Gao, Paul Bennett. CMT in TREC-COVID Round 2: Mitigating the Generalization Gaps from Web to Special Domain Search. [<A href="https://arxiv.org/abs/2011.01580" target="_blank">pdf</A>][<A href="https://github.com/thunlp/OpenMatch" target="_blank">codes</A>].

- Xiaoyuan Yi, <b>Zhenghao Liu</b>, Wenhao Li, Maosong Sun. 2020. Text Style Transfer via Learning Style Instance Supported Latent Space. <i>IJCAI 2019.</i> [<A href="https://www.ijcai.org/Proceedings/2020/0526.pdf" target="_blank">pdf</A>].

- Kaitao Zhang, Chenyan Xiong, <b>Zhenghao Liu</b>, Zhiyuan Liu. Selective Weak Supervision for Neural Information Retrieval. <i>WebConf 2020. </i> [<A href="https://dl.acm.org/doi/abs/10.1145/3366423.3380131" target="_blank">pdf</A>][<A href="https://github.com/thunlp/ReInfoSelect" target="_blank">codes</A>].

- Deming Ye, Yankai Lin, Jiaju Du, <b>Zhenghao Liu</b>, Peng Li, Maosong Sun, Zhiyuan Liu. Coreferential Reasoning Learning for Language Representation. <i>EMNLP 2020. </i> [<A href="https://www.aclweb.org/anthology/2020.emnlp-main.582/" target="_blank">pdf</A>][<A href="https://github.com/thunlp/CorefBERT" target="_blank">codes</A>].




<h3><strong>2019</strong></h3>

- <b>Zhenghao Liu</b>, Chenyan Xiong, Maosong Sun, Zhiyuan Liu. Explore Entity Embedding Effectiveness in Entity Retrieval. <i> Proceedings of Chinese National Conference on Computational Linguistics (CCL 2019).</i>[<A href="https://link.springer.com/chapter/10.1007/978-3-030-32381-3_9" target="_blank">pdf</A>][<A href="https://github.com/thunlp/EmbeddingEntityRetrieval" target="_blank">codes</A>].

- Yifan Qiao, Chenyan Xiong, <b>Zhenghao Liu</b>, Zhiyuan Liu. Understanding the Behaviors of BERT in Ranking. [<A href="https://arxiv.org/abs/1904.07531" target="_blank">pdf</A>].

- Yuan Yao, Deming Ye, Peng Li, Xu Han, Yankai Lin, <b>Zhenghao Liu</b>, Zhiyuan Liu, Lixin Huang, Jie Zhou, Maosong Sun. DocRED: A Large-Scale Document-Level Relation Extraction Dataset. <i>ACL 2019.</i>[<A href="https://arxiv.org/abs/1906.06127" target="_blank">pdf</A>][<A href="https://github.com/thunlp/DocRED" target="_blank">codes</A>].


<h3><strong>2018</strong></h3>
- <b>Zhenghao Liu</b>, Chenyan Xiong, Maosong Sun, Zhiyuan Liu. Entity-Duet Neural Ranking: Understanding the Role of Knowledge Graph Semantics in Neural Information Retrieval. <i>ACL 2018.</i>[<A href="https://www.aclweb.org/anthology/P18-1223" target="_blank">pdf</A>][<A href="https://github.com/thunlp/EntityDuetNeuralRanking" target="_blank">codes</A>].

<h3><strong>2017</strong></h3>
- Liner Yang, Maosong Sun, Jiacheng Zhang, <b>Zhenghao Liu</b>, Huanbo Luan, Yang Liu. Neural Parse Combination. <i> Journal of Computer Science and Technology (JCST).</i>[<A href="https://link.springer.com/article/10.1007/s11390-017-1756-5" target="_blank">pdf</A>].





