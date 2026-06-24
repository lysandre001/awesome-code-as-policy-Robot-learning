# Awesome Code-as-Policy for Robot Learning

LLM 生成可执行程序作为机器人策略（Code as Policy）及相关工作精选列表。

> 范围：**A（核心）+ B（邻近）**，共 19 篇。已移除广义 robot policy / RL / 分层控制等与 CaP 弱相关的条目。

---

## A. Core — Code-as-Policy

直接做代码策略生成、闭环修复、benchmark，或 CaP 的明确扩展。

- Code as Policies: Language Model Programs for Embodied Control
  -- Paper: https://arxiv.org/abs/2209.07753
  -- GitHub: https://github.com/google-research/google-research/tree/master/code_as_policies

- How to Prompt Your Robot: A PromptBook for Manipulation Skills with Code as Policies
  -- Paper: https://doi.org/10.1109/icra57147.2024.10610784
  -- GitHub: https://github.com/google-research/google-research/tree/master/code_as_policies

- Towards Reliable Code-as-Policies: A Neuro-Symbolic Framework for Embodied Task Planning
  -- Paper: https://arxiv.org/abs/2510.21302
  -- GitHub: 暂无

- GenSwarm: Scalable Multi-Robot Code-Policy Generation and Deployment via Language Models
  -- Paper: https://doi.org/10.1038/s44182-025-00065-w
  -- GitHub: https://github.com/WindyLab/GenSwarm

- Growing with Your Embodied Agent: A Human-in-the-Loop Lifelong Code Generation Framework
  -- Paper: https://arxiv.org/abs/2509.18597
  -- GitHub: 暂无

- Embodied Long Horizon Manipulation with Closed-Loop Code Generation and Incremental Few-Shot Adaptation
  -- Paper: https://arxiv.org/abs/2503.21969
  -- GitHub: https://github.com/Ghiara/DAHLIA

- Robotic Programmer: Video Instructed Policy Code Generation for Robotic Manipulation
  -- Paper: https://arxiv.org/abs/2501.04268
  -- GitHub: 暂无（项目页：https://video2code.github.io/RoboPro-website/）

- ALRM: Agentic LLM for Robotic Manipulation
  -- Paper: https://arxiv.org/abs/2601.19510
  -- GitHub: 暂无

- GROOT: GPT-based Human-RObOT Interface
  -- Paper: https://doi.org/10.1109/iccr67607.2025.11372068
  -- GitHub: 暂无

- CaP-X: A Framework for Benchmarking and Improving Coding Agents for Robot Manipulation
  -- Paper: https://arxiv.org/abs/2603.22435
  -- GitHub: https://github.com/capgym/cap-x

- Maestro: Orchestrating Robotics Modules with Vision-Language Models for Zero-Shot Generalist Robots
  -- Paper: https://arxiv.org/abs/2511.00917
  -- GitHub: 暂无（项目页：https://maestro-robot.github.io/）

- HyCodePolicy: Hybrid Language Controllers for Multimodal Monitoring and Decision in Embodied Agents
  -- Paper: https://arxiv.org/abs/2508.02629
  -- GitHub: https://github.com/RoboTwin-Platform/RoboTwin

- Natural Language as Policies: Reasoning for Coordinate-Level Embodied Control with LLMs
  -- Paper: https://arxiv.org/abs/2403.13801
  -- GitHub: https://github.com/shure-dev/NLaP

- RL-GPT: Integrating Reinforcement Learning and Code-as-Policy
  -- Paper: https://arxiv.org/abs/2402.19299
  -- GitHub: 暂无

- Playful Agentic Robot Learning
  -- Paper: https://arxiv.org/abs/2606.19419
  -- GitHub: https://github.com/Playful-RATs/RATs

---

## B. Related — Same Lineage / Baseline / Complement

同团队脉络、CaP 论文中的对比方法，或与 LLM+代码/规划强相关的互补工作。

- ExploRLLM: Guiding Exploration in Reinforcement Learning with Large Language Models
  -- Paper: https://arxiv.org/abs/2403.09583
  -- GitHub: 暂无（项目页：https://explorllm.github.io/）

- Manipulate-Anything: Automating Real-World Robots using Vision-Language Models
  -- Paper: https://arxiv.org/abs/2406.18915
  -- GitHub: https://github.com/Robot-MA/manipulate-anything

- Language to Rewards for Robotic Skill Synthesis
  -- Paper: https://arxiv.org/abs/2306.08647
  -- GitHub: https://github.com/google-deepmind/language_to_reward_2023

- Scaling Up and Distilling Down: Language-Guided Robot Skill Acquisition
  -- Paper: https://arxiv.org/abs/2307.14535
  -- GitHub: https://github.com/real-stanford/scalingup

---

## BibTeX

| 文件 | 说明 |
|------|------|
| `references_clean.bib` | 上述 19 篇的 BibTeX |
| `references.bib` | 原始未筛选文献（含已移除条目） |
