---
permalink: /en/
title: ""
excerpt: ""
lang: en
author: li_yuanjun_en
author_profile: true
---

<span class='anchor' id='about-me'></span>

**Welcome to Yuanjun Li's homepage!**

I am Yuanjun Li, a master's student in Computer Science and Technology at the School of Artificial Intelligence, Shandong University. My advisor is [Prof. Zhiwei Xu](https://xuleek.tech/). My research interests include multi-agent reinforcement learning, Reinforcement Learning for LLM Post-Training, autonomous control and intelligent decision-making, and LLM-enhanced reinforcement learning. I focus on efficient decision-making, credit assignment, and exploration in complex cooperative scenarios, and I also work on research platforms and multi-agent collaboration systems.

<span class='anchor' id='education'></span>

# 🎓 Education
- *2025.09 - 2028.06*, <img class="edu-logo" src="{{ '/images/sdu-logo.svg' | relative_url }}" alt="Shandong University logo"> [Shandong University](https://www.sdu.edu.cn/), M.S. student by recommendation, School of Artificial Intelligence, Computer Science and Technology, Jinan, Shandong
- *2021.09 - 2025.06*, <img class="edu-logo" src="{{ '/images/cumt-logo.png' | relative_url }}" alt="China University of Mining and Technology logo"> [China University of Mining and Technology](https://cumt.edu.cn/), B.E., School of Information and Control Engineering, Artificial Intelligence, Xuzhou, Jiangsu
  - GPA: 4.21/5.00; weighted average: 89.37; ranking: 5/106 (top 4.72%); CET-6

<span class='anchor' id='publications'></span>

# 📝 Research Outputs

### Publications
- **ASPECT: Agent-Specific Parameter-Efficient Core Tuning for Multi-Agent LLM Workflows**<br>
  *2027 International Conference on Learning Representations (**ICLR**, CCF-A CORE A\*), under review*, First Author, 2026.09<br>
  **Abstract:** To address role dominance and same-role gradient amplification during reinforcement learning post-training of multi-agent LLM systems, this work proposes ASPECT. It constructs shared, frozen low-rank LoRA bases through task calibration and singular value decomposition, and assigns an independent core matrix to each agent to isolate gradient updates in a parameter-efficient manner. Experiments across models and workflows on mathematics and coding tasks show that ASPECT achieves higher task accuracy with less than 10% of the trainable parameters required by conventional LoRA allocation.

- **DUPAR: Dual-Path Conversational Retrieval via Speech Retriever with Cross-Turn Evidence Caching**<br>
  *2027 International Conference on Acoustics, Speech, and Signal Processing (**ICASSP**, CCF-B CORE B), under review*, First Author, 2026.09<br>
  **Abstract:** To address ASR error propagation and latency in conventional speech retrieval, this work proposes DUPAR, a dual-path conversational retrieval framework. An audio encoder aligned with text embeddings directly retrieves evidence from a cross-turn cache, with full-corpus retrieval combining audio and transcribed text as a fallback. The cache is updated through graph-based expansion to neighboring nodes of the previous turn's retrieval results. Experiments show that the audio encoder achieves retrieval accuracy close to text-based retrieval, provides approximately 3.75 times query-side speedup over an ASR-cascaded retrieval pipeline, and is more robust to synthetic noise and variations in speaking style.

- **From Trajectories to Skills: Temporal Skill Reuse for Efficient Exploration in Cooperative MARL**<br>
  *2027 Association for the Advancement of Artificial Intelligence (**AAAI**, CCF-A CORE A\*), under review*, Co-first Author (second-listed), 2026.06<br>
  **Abstract:** To improve inefficient exploration and long-horizon decision-making in reinforcement learning, this work proposes Temporal Skill Reuse. The method mines high-value temporal segments from historical trajectories as macro-action skills and reuses them during training through state matching, guiding policies toward high-reward behavior patterns. Experiments on multi-agent SMAC and single-agent Atari environments show improved exploration efficiency, faster convergence, and stronger performance.

- **QLLM: Do We Really Need a Mixing Network for Credit Assignment in Multi-Agent Reinforcement Learning.**<br>
  *2027 Association for the Advancement of Artificial Intelligence (**AAAI**, CCF-A CORE A\*), under review*, First Author, 2026.03<br>
  **Abstract:** To reduce the training burden and limited interpretability of traditional mixing networks in multi-agent reinforcement learning, this work proposes QLLM. It uses an encoder-evaluator LLM architecture to generate nonlinear, training-free credit assignment functions (TFCAF) in a zero-shot manner, directly replacing the credit assignment network in value decomposition algorithms. Experiments on SMAC and GRF show that QLLM reduces learnable parameters, accelerates convergence, improves performance, and provides strong algorithmic compatibility and semantic interpretability.<br>
  [Paper](https://arxiv.org/abs/2504.12961)

- **QSIM: Mitigating Overestimation in Multi-Agent Reinforcement Learning via Action Similarity Weighted Q-Learning.**<br>
  *2026 International Conference on Automated Planning and Scheduling (**ICAPS**, CCF-B CORE A\*)*, First Author, 2025.12<br>
  **Abstract:** To address Q-value overestimation in multi-agent reinforcement learning, this work proposes QSIM. It constructs a near-greedy joint action space and introduces an action-similarity metric to rebuild the TD target through similarity-weighted aggregation, replacing the max operator in the conventional Bellman optimality equation. Experiments on SMAC, MPE, and other benchmarks show that QSIM is broadly compatible with value decomposition methods, effectively mitigates overestimation, and improves convergence speed and performance.<br>
  [Paper](https://doi.org/10.1609/icaps.v36i1.42882) | [Arxiv](https://arxiv.org/abs/2602.22786)

- **LSTM-GAT networks based on ResNet structure for prediction of complex multivariable systems.**<br>
  *IEEE 36th Chinese Control and Decision Conference (**CCDC**)*, 2024.03<br>
  **Abstract:** This work addresses prediction for complex multivariable systems by combining LSTM temporal modeling, GAT-based variable-relation modeling, and a ResNet residual structure. The resulting deep network improves representation ability and stability for multivariable time-series prediction.<br>
  [Paper](https://ieeexplore.ieee.org/document/10587396)

- **Identification of Nonlinear Multi-Input Multi-Output Systems Based on Maximum Likelihood Principle.**<br>
  *IEEE 2023 China Automation Congress (**CAC**, CAA-A)*, Student First Author, 2023.12<br>
  **Abstract:** This paper studies block-structured modeling for nonlinear-input MIMO industrial systems and proposes a maximum-likelihood parameter identification algorithm with an adaptive forgetting factor. The method decouples nonlinear static parameters and dynamic parameters to support system modeling.<br>
  [Paper](https://ieeexplore.ieee.org/document/10450725)

### Patents
- **Cross-coupled iterative learning control method for time-varying uncertain batch processes.**<br>
  *Granted invention patent*, 2022.12-2023.02<br>
  [Patent](https://xueshu.baidu.com/usercenter/paper/show?paperid=1t510as0e27d02003w5e04d09g291855&site=xueshu_se)

<span class='anchor' id='projects'></span>

# 💼 Projects
- <span class="project-heading"><span class="project-heading__title"><strong>Shandong University Research Matching Platform | Intelligent University Expert Matching System Based on LLM and RAG</strong> <img class="project-logo" src="{{ '/images/山东大学图标.jpg' | relative_url }}" alt="Shandong University" width="353" height="117"></span><em class="project-heading__date">2025.12 - 2026.02</em></span>
  Crawled and parsed faculty homepage information, structured teacher research data, generated semantic embeddings with BGE-M3, and combined cosine-similarity retrieval with rerank ranking to match enterprise needs with expert profiles and automatically generate expert recommendation reports and collaboration suggestions.

- <span class="project-heading"><span class="project-heading__title"><strong>Shandong University Research Assistant | Multi-agent Research Collaboration System Based on OpenClaw</strong> <img class="project-logo" src="{{ '/images/山东大学图标.jpg' | relative_url }}" alt="Shandong University" width="353" height="117"></span><em class="project-heading__date">2026.02 - 2026.05</em></span>
  Built Docker-isolated environments for enterprises, research institutes, and faculty users; designed multi-agent task communication mechanisms; connected the full workflow from enterprise demand submission, expert matching, faculty authorization, and result delivery; and used a private expert database to support candidate expert generation, review, and multi-round human-agent collaboration.

- <span class="project-heading"><span class="project-heading__title"><strong>Li Auto Multi-Agent Collaboration Platform | Agent-based Intelligent Business Collaboration System</strong> <img class="project-logo" src="{{ '/images/理想汽车图标.jpg' | relative_url }}" alt="Li Auto" width="319" height="106"></span><em class="project-heading__date">2026.06 - 2026.09</em></span>
  Connected enterprise data, knowledge bases, and business tools, enabling multiple agents to collaborate on business question answering, data analysis, and automated tasks. Primarily responsible for historical context management and long-term memory optimization in the Agent Harness, improving information completeness and agent stability during long conversations.

<span class='anchor' id='awards'></span>

# 🏅 Awards
- *2026.04* National Third Prize, Tencent Kaiwu Agent Decision Algorithm Competition
- *2025.09* First Prize Freshman Scholarship, Shandong University
- *2025.06* Outstanding Graduate, China University of Mining and Technology
- *2024.12* University-level Outstanding Student, China University of Mining and Technology (First Prize Scholarship)
- *2024.07* Second Prize, National Undergraduate Electronic Design Contest
- *2024.06* Second Prize, Jiangsu May Day Mathematical Modeling Competition
- *2023.12* University-level Outstanding Student, China University of Mining and Technology (First Prize Scholarship)
- *2022.12* University-level Outstanding Class Cadre, China University of Mining and Technology (First Prize Scholarship)
- *2022.11* Bronze Award, University Physics Competition
- *2022.11* Second Prize, Jiangsu Higher Mathematics Competition for Colleges and Universities
- *2022.10* Higher Mathematics Learning Star, China University of Mining and Technology (ranked 1/4725 in Higher Mathematics)

<span class='anchor' id='student-service'></span>

# 💻 Student Service
- *2021.09 - 2022.09*, Class monitor: planned and organized class activities, published news articles on the college website, and represented the class in meetings.
- *2021.09 - 2025.06*, Class study committee member: organized pre-exam tutoring, shared notes and problem-solving methods, and supported a strong learning atmosphere.
