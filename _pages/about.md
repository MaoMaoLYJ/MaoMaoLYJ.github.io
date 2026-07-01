---
permalink: /
title: ""
excerpt: ""
lang: zh-CN
author_profile: true
redirect_from:
  - /about/
  - /about.html
  - /zh-cn/
---

<span class='anchor' id='about-me'></span>

**欢迎来到李源浚的主页！**

我叫李源浚，目前是山东大学人工智能学院计算机科学与技术专业硕士研究生，导师是[徐志伟老师](https://xuleek.tech/)。我的研究方向包括多智能体强化学习、自主控制与智能决策、大模型增强的强化学习等。我关注强化学习在复杂协作场景中的高效决策、信用分配与探索问题，并持续参与科研平台和多智能体系统相关项目。

<span class='anchor' id='education'></span>

# 🎓 学历
- *2025.09 - 2028.06*, [山东大学](https://www.sdu.edu.cn/) 推免硕士，人工智能学院，计算机科学与技术专业，山东济南
- *2021.09 - 2025.06*, [中国矿业大学](https://cumt.edu.cn/) 本科，信息与控制工程学院，人工智能专业，江苏徐州
  - 加权绩点：4.21/5.00；加权成绩：89.37；综合排名：5/106（4.72%）；英语水平：CET-6

<span class='anchor' id='publications'></span>

# 📝 论文专利

### 论文
- **QSIM: Mitigating Overestimation in Multi-Agent Reinforcement Learning via Action Similarity Weighted Q-Learning.**<br>
  *2026 International Conference on Automated Planning and Scheduling (ICAPS, CCF-B CORE A\*)*, 第一作者, 2025.12<br>
  **摘要：** 针对多智能体强化学习中的 Q 值高估问题，本文提出 QSIM 框架。该框架构建“近贪婪联合动作空间”，并引入动作相似度度量，通过相似度加权聚合重构 TD Target，以替代传统贝尔曼最优方程中的 max 算子，从而抑制高估误差。SMAC、MPE 等基准实验表明，QSIM 具备较强通用性，可无缝结合多种值分解算法，在有效缓解 Q 值高估的同时显著提升算法收敛速度与性能。<br>
  [论文链接](https://arxiv.org/abs/2602.22786)

- **QLLM: Do We Really Need a Mixing Network for Credit Assignment in Multi-Agent Reinforcement Learning.**<br>
  *2026 European Conference on Machine Learning (ECML, CCF-B CORE A) 在投*, 第一作者, 2026.03<br>
  **摘要：** 针对多智能体强化学习中传统混合网络需额外训练且可解释性不足的问题，本文提出 QLLM 框架。该框架采用“编码器-评估器”LLM 架构，零样本生成非线性、免训练的信用分配函数（TFCAF），直接替代传统值分解算法中的信用分配网络。SMAC、GRF 等复杂环境实验表明，QLLM 可显著减少可学习参数、加速收敛并提升算法性能，同时具备良好的算法兼容性与语义可解释性。<br>
  [论文链接](https://arxiv.org/abs/2504.12961)

- **Identification of Nonlinear Multi-Input Multi-Output Systems Based on Maximum Likelihood Principle.**<br>
  *IEEE 2023 China Automation Congress (CAC, CAA-A)*, 学生一作, 2023.12<br>
  **摘要：** 针对非线性输入的 MIMO 工业系统块结构建模问题，本文提出一种引入自适应遗忘因子的最大似然参数辨识算法，实现了非线性静态与动态参数解耦及系统建模。<br>
  [论文链接](https://ieeexplore.ieee.org/document/10450725)

- **LSTM-GAT networks based on ResNet structure for prediction of complex multivariable systems.**<br>
  *IEEE 36th Chinese Control and Decision Conference (CCDC)*, 2024.03<br>
  **摘要：** 针对复杂多变量系统预测问题，本文结合 LSTM 的时序建模能力、GAT 的变量关联建模能力与 ResNet 的残差结构，构建面向复杂系统动态预测的深度网络模型，以提升多变量时序预测的表达能力和稳定性。<br>
  [论文链接](https://ieeexplore.ieee.org/document/10587396)

- **Temporal Skill Reuse for Efficient Exploration in Multi-Agent Reinforcement Learning.**<br>
  *在研论文*, 主要负责人<br>
  **摘要：** 针对强化学习中的低效探索与长时序决策问题，本文提出 Temporal Skill Reuse 框架。该方法从历史轨迹中挖掘高价值时序片段作为宏动作技能，并基于状态匹配在训练过程中进行复用，以引导策略向高回报行为模式学习。在多智能体环境 SMAC 与单智能体环境 Atari 上的实验表明，该方法可提升探索效率、加速收敛并改善性能。

### 专利
- **针对时变不确定性间歇过程的交叉耦合迭代学习控制方法**<br>
  *发明专利（已授权）*, 2022.12-2023.02<br>
  [专利链接](https://xueshu.baidu.com/usercenter/paper/show?paperid=1t510as0e27d02003w5e04d09g291855&site=xueshu_se)

<span class='anchor' id='projects'></span>

# 💼 项目经历
- **山东大学科研匹配平台 \| 基于 LLM 与 RAG 架构的高校专家智能匹配系统**<br>
  *2025.12 - 2026.02*<br>
  爬取并解析高校教师个人主页信息，完成教师科研数据的结构化入库；采用 BGE-M3 模型生成语义 Embedding，结合余弦相似度检索与 Rerank 重排序，实现企业需求与专家画像的精准匹配，并自动生成专家推荐报告与合作建议。

- **山东大学科研助手 \| 基于 OpenClaw 的多智能体科研协作系统**<br>
  *2026.02 - 2026.05*<br>
  面向企业、科研院与教师等用户构建 Docker 隔离环境；设计多智能体任务通信机制，打通企业需求提交、专家匹配、教师授权确认与结果返回的闭环流程，并结合私有专家库实现候选专家生成、审核与多轮人机协同交互。

<span class='anchor' id='awards'></span>

# 🏅 竞赛奖项
- *2022.11* 国际大学生物理竞赛 铜奖（国际级）
- *2022.11* 江苏省普通高校高等数学竞赛 二等奖（省级）
- *2024.07* 全国大学生电子设计竞赛 二等奖（省级）
- *2026.04* 腾讯开悟智能体决策算法竞赛区域赛第四名

<span class='anchor' id='student-service'></span>

# 💻 学生工作
- *2021.09 - 2022.09*, 班级班长，策划和组织班级活动，在学院官网发布新闻稿，代表班级参加各种会议。
- *2021.09 - 2025.06*, 班级学习委员，组织考试前的辅导活动，分享笔记以及解题方法，为班级营造良好的学习氛围。
