# Code as Policies & Embodied Robot Learning

按 4 类整理的参考文献清单，包含论文链接与 GitHub 仓库（如有）。

> 说明：若论文未公开代码，GitHub 一栏标注为「暂无」；部分仓库为项目主页或相关实现，非官方完整复现。

---

## 1. LLM / VLA for Robot Control

大语言模型、视觉-语言-动作模型直接生成代码/策略，以及 Code-as-Policies 及其扩展。

- Code as Policies: Language Model Programs for Embodied Control (Liang et al., ICRA 2023)
  - Paper: https://arxiv.org/abs/2209.07753
  - GitHub: https://github.com/google-research/google-research/tree/master/code_as_policies

- How to Prompt Your Robot: A PromptBook for Manipulation Skills with Code as Policies (Arenas et al., ICRA 2024)
  - Paper: https://doi.org/10.1109/icra57147.2024.10610784
  - GitHub: https://github.com/google-research/google-research/tree/master/code_as_policies

- Towards Reliable Code-as-Policies: A Neuro-Symbolic Framework for Embodied Task Planning (Ahn et al., NeurIPS 2025)
  - Paper: https://arxiv.org/abs/2510.21302
  - GitHub: 暂无

- ExploRLLM: Guiding Exploration in Reinforcement Learning with Large Language Models (Ma et al., ICRA 2025)
  - Paper: https://arxiv.org/abs/2403.09583
  - GitHub: 暂无（项目页：https://explorllm.github.io/）

- GenSwarm: Scalable Multi-Robot Code-Policy Generation and Deployment via Language Models (Ji et al., npj Robotics 2026)
  - Paper: https://doi.org/10.1038/s44182-025-00065-w
  - GitHub: https://github.com/WindyLab/GenSwarm

- Growing with Your Embodied Agent: A Human-in-the-Loop Lifelong Code Generation Framework (Meng et al., 2025)
  - Paper: https://arxiv.org/abs/2509.18597
  - GitHub: 暂无

- Embodied Long Horizon Manipulation with Closed-loop Code Generation (Meng et al., 2025)
  - Paper: https://arxiv.org/abs/2503.21969
  - GitHub: https://github.com/Ghiara/DAHLIA

- Robotic Programmer: Video Instructed Policy Code Generation for Robotic Manipulation (Xie et al., IROS 2025)
  - Paper: https://arxiv.org/abs/2501.04268
  - GitHub: 暂无（项目页：https://video2code.github.io/RoboPro-website/）

- ALRM: Agentic LLM for Robotic Manipulation (Santos et al., 2026)
  - Paper: https://arxiv.org/abs/2601.19510
  - GitHub: 暂无

- GROOT: GPT-based Human-RObOT Interface (Maniar et al., 2025)
  - Paper: https://doi.org/10.1109/iccr67607.2025.11372068
  - GitHub: 暂无

- CaP-X: A Framework for Benchmarking and Improving Coding Agents for Robot Manipulation (Fu et al., 2026)
  - Paper: https://arxiv.org/abs/2603.22435
  - GitHub: https://github.com/capgym/cap-x

- Maestro: Orchestrating Robotics Modules with Vision-Language Models for Zero-Shot Generalist Robots (Shi et al., 2025)
  - Paper: https://arxiv.org/abs/2511.00917
  - GitHub: 暂无（项目页：https://maestro-robot.github.io/）

- HyCodePolicy: Hybrid Language Controllers for Multimodal Monitoring and Decision (Liu et al., 2025)
  - Paper: https://arxiv.org/abs/2508.02629
  - GitHub: https://github.com/RoboTwin-Platform/RoboTwin

- Manipulate-Anything: Automating Real-World Robots using Vision-Language Models (Duan et al., CoRL 2024)
  - Paper: https://arxiv.org/abs/2406.18915
  - GitHub: https://github.com/Robot-MA/manipulate-anything

- Vision-Language-Conditioned Learning Policy for Robotic Manipulation (Liu et al., 2024)
  - Paper: 暂无公开 arXiv 链接
  - GitHub: 暂无

- Language to Rewards for Robotic Skill Synthesis (Yu et al., CoRL 2023)
  - Paper: https://arxiv.org/abs/2306.08647
  - GitHub: https://github.com/google-deepmind/language_to_reward_2023

- Natural Language as Policies: Reasoning for Coordinate-Level Embodied Control with LLMs (Mikami et al., 2024)
  - Paper: https://arxiv.org/abs/2403.13801
  - GitHub: https://github.com/shure-dev/NLaP

- RL-GPT: Integrating Reinforcement Learning and Code-as-Policy (Liu et al., NeurIPS 2024)
  - Paper: https://arxiv.org/abs/2402.19299
  - GitHub: 暂无

- Playful Agentic Robot Learning (Zhang et al., 2026)
  - Paper: https://arxiv.org/abs/2606.19419
  - GitHub: https://github.com/Playful-RATs/RATs

---

## 2. Policy Learning & Transfer

强化学习、模仿学习、Sim2Real、世界模型与策略迁移等经典学习方法论。

- Transferring Policy of Deep RL from Simulation to Reality (Ju et al., Nature Machine Intelligence 2022)
  - Paper: https://doi.org/10.1038/s42256-022-00573-6
  - GitHub: 暂无

- Hardware Conditioned Policies for Multi-Robot Transfer Learning (Chen et al., 2022)
  - Paper: https://arxiv.org/abs/1811.09864
  - GitHub: 暂无

- DayDreamer: World Models for Physical Robot Learning (Wu et al., CoRL 2022)
  - Paper: https://arxiv.org/abs/2206.14176
  - GitHub: https://github.com/danijar/daydreamer

- Offline Robotic World Model: Learning Robotic Policies without a Physics Simulator (Li et al., 2025)
  - Paper: https://arxiv.org/abs/2504.16680
  - GitHub: https://github.com/leggedrobotics/robotic_world_model_lite

- Video2Policy: Scaling up Manipulation Tasks in Simulation through Internet Videos (Ye et al., 2025)
  - Paper: https://arxiv.org/abs/2502.09886
  - GitHub: 暂无（项目页：https://yewr.github.io/video2policy/）

- Scaling Up and Distilling Down: Language-Guided Robot Skill Acquisition (Ha et al., CoRL 2023)
  - Paper: https://arxiv.org/abs/2307.14535
  - GitHub: https://github.com/real-stanford/scalingup

- Training Robots Without Robots: Deep Imitation Learning for Master-to-Robot Policy Transfer (Kim et al., RA-L 2023)
  - Paper: https://doi.org/10.1109/lra.2023.3262423
  - GitHub: 暂无

- On-Policy Robot Imitation Learning from a Converging Supervisor (Balakrishna et al., CoRL 2019)
  - Paper: https://arxiv.org/abs/1907.03423
  - GitHub: 暂无

- Bayesian Disturbance Injection: Robust Imitation Learning of Flexible Policies (Oh et al., 2023)
  - Paper: https://doi.org/10.1016/j.neunet.2022.11.008
  - GitHub: 暂无

- FuRL: Visual-Language Models as Fuzzy Rewards for Reinforcement Learning (Fu et al., ICML 2024)
  - Paper: https://arxiv.org/abs/2406.00645
  - GitHub: https://github.com/fuyw/FuRL

- Kernel Dynamic Policy Programming (Cui et al., 2018)
  - Paper: https://doi.org/10.1016/j.neunet.2017.06.007
  - GitHub: 暂无

- Reinforcement Learning Control of Robotic Knee with Human-in-the-Loop (Gao et al., 2022)
  - Paper: https://doi.org/10.1109/TNNLS.2021.3071727
  - GitHub: 暂无

- Learning a Group-Aware Policy for Robot Navigation (Katyal et al., IROS 2022)
  - Paper: https://doi.org/10.1109/iros47612.2022.9981183
  - GitHub: 暂无

- Research on Robot Obstacle Avoidance and Generalization Methods (Wang et al., 2025)
  - Paper: https://doi.org/10.3390/biomimetics10080493
  - GitHub: 暂无

- Learning Ambidextrous Robot Grasping Policies (Mahler et al., Science Robotics 2021)
  - Paper: https://doi.org/10.1126/scirobotics.aau4984
  - GitHub: https://github.com/BerkeleyAutomation/gqcnn

---

## 3. Hierarchical & Modular Control

分层策略、模块化控制、策略组合与多智能体协调。

- HAMSTER: Hierarchical Action Models for Open-World Robot Manipulation (Li et al., ICLR 2025)
  - Paper: https://arxiv.org/abs/2502.05485
  - GitHub: https://github.com/liyi14/HAMSTER_beta

- Hierarchical Reinforcement Learning with Universal Policies for Multistep Robotic Manipulation (Yang et al., 2021)
  - Paper: https://doi.org/10.1109/tnnls.2021.3059912
  - GitHub: 暂无

- Hierarchical Policy Learning with Demonstration Learning for Peg-in-Hole Assembly (Yan et al., 2023)
  - Paper: https://doi.org/10.1109/tii.2023.3240936
  - GitHub: 暂无

- Learning Modular Robot Control Policies (Whitman et al., T-RO 2023)
  - Paper: https://doi.org/10.1109/tro.2023.3284362
  - GitHub: 暂无

- Learning Modular Policies for Robotics (Neumann et al., 2014)
  - Paper: https://doi.org/10.3389/fncom.2014.00062
  - GitHub: 暂无

- Hierarchical Learning of Robotic Contact Policies (Simonic et al., 2023)
  - Paper: https://doi.org/10.1016/j.rcim.2023.102657
  - GitHub: 暂无

- PoCo: Policy Composition from and for Heterogeneous Robot Learning (Wang et al., RSS 2024)
  - Paper: https://arxiv.org/abs/2402.02511
  - GitHub: 暂无（项目页：https://liruiw.github.io/policycomp/）

- RMP2: A Structured Composable Policy Class for Robot Learning (Li et al., RSS 2021)
  - Paper: https://arxiv.org/abs/2103.05922
  - GitHub: https://github.com/UWRobotLearning/rmp2

- Robot Fleet Learning via Policy Merging (Wang et al., ICLR 2024)
  - Paper: https://arxiv.org/abs/2310.01362
  - GitHub: https://github.com/liruiw/Fleet-Tools

- Policy-Conditioned Policies for Multi-Agent Task Solving (Lin et al., 2025)
  - Paper: https://arxiv.org/abs/2512.21024
  - GitHub: 暂无

- Skill Transformer: A Monolithic Policy for Mobile Manipulation (Huang et al., ICCV 2023)
  - Paper: https://arxiv.org/abs/2308.09873
  - GitHub: https://github.com/WhoKnowsssss/skill_transformer

---

## 4. Foundations & Future Directions

综述、框架、安全伦理、终身学习与历史/交叉文献。

- What Foundation Models Can Bring for Robot Learning in Manipulation: A Survey (Li et al., IJRR 2025)
  - Paper: https://doi.org/10.1177/02783649251390579
  - GitHub: 暂无

- Ark: An Open-Source Python-Based Framework for Robot Learning (Dierking et al., 2025)
  - Paper: https://arxiv.org/abs/2506.21628
  - GitHub: https://github.com/Robotics-Ark/ark_framework

- Don't Let Your Robot Be Harmful: Responsible Robotic Manipulation via Safety-as-Policy (Ni et al., RA-L 2025)
  - Paper: https://arxiv.org/abs/2411.18289
  - GitHub: https://github.com/kodenii/Responsible-Robotic-Manipulation

- How Robots Can Learn to Follow a Moral Code (Savage, Nature 2023)
  - Paper: https://doi.org/10.1038/d41586-023-03258-1
  - GitHub: 暂无

- Encoding Primitives Generation Policy Learning for Catastrophic Forgetting (Xiong et al., 2020)
  - Paper: https://doi.org/10.1016/j.neunet.2020.06.003
  - GitHub: 暂无

- Efficient and Adaptive Language-Conditioned Robot Learning (Zhou, PhD Thesis 2025)
  - Paper: https://repository.asu.edu/（Arizona State University 学位论文）
  - GitHub: 暂无

- Progressive Learning and Its Application to Robot Impedance Learning (Yang & Asada, 2012)
  - Paper: https://doi.org/10.1109/72.508937
  - GitHub: 暂无

- Manifold Learning for Robot Navigation (Keeratipranon et al., 2007)
  - Paper: https://doi.org/10.1142/S0129065706000780
  - GitHub: 暂无

- The Learning Curve in Robotic Pancreaticoduodenectomy (Napoli et al., 2017)
  - Paper: https://doi.org/10.1159/000445015
  - GitHub: 暂无

---

## 文件说明

| 文件 | 说明 |
|------|------|
| `references.bib` | 原始参考文献（含重复条目） |
| `references_clean.bib` | 去重后的 BibTeX 格式 |

## 引用

如需在 LaTeX 中使用，可将 `references_clean.bib` 加入文档：

```latex
\bibliography{references_clean}
```
