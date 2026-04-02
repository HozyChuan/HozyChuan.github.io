---
permalink: /
title: "Zhou Dong - Homepage"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# About Me
Hello 👋, I am **Zhou Dong**, a third-year undergraduate student at <img width="16" height="16" alt="image" src="https://github.com/user-attachments/assets/8f36759d-254b-49a4-ae35-49660c0bddfb" /> [Hohai University](https://www.hhu.edu.cn/), majoring in Communication Engineering, with research focused on **Computer Vision, 3D Generation, and Channel Knowledge Map**.

Research Interest ❤: **Computer Vision, 3D Generation, Channel Knowledge Map, AI for communication**.

Previously, I led a research project on **3D Channel Knowledge Map Construction** as the primary leader which is a great honor to be guided by the Associate Professor [Ruoguang Li](https://jszy.hhu.edu.cn/lrg/).

Before that, I worked on **multi-modal human detection in smoke environments** and end-to-end vision fusion systems, achieving efficient feature extraction and real-time target recognition.

I hold my undergraduate study from Hohai University (211), with strong academic performance and solid programming skills in Python and C.

If everything goes as expected, I will obtain the qualification for direct admission to graduate school this year.I am actively seeking  for **Research Internship, Master's degree or directly pursuing a doctoral degree**.

---

## Scientific Research Experience
### 1.Discrimination of human targets in thick smoke environments
**Competition**：中国大学生服务外包创新创业大赛 💻[Demo Code](https://github.com/XoomitLXH/Smoke-Human-Detection.git)

**Time**：2024.12 – 2025.04

<img width="320" height="180" alt="7d341c2e5fcfb1ac2143a1ad65db8ee" src="https://github.com/user-attachments/assets/c6814210-3d29-4b57-8e26-4a4c89d70d46" />

- **Project Brief**: Aiming to prove the performance degradation of visible light sensors and the rescue response delay of conventional firefighting robots in dense smoke environments, this project integrates multiple advanced techniques: spatiotemporal alignment, dual-branch multimodal fusion, contrast-guided dehazing, dark-channel-prior-based smoke removal, and the RT-DETR human detection algorithm. By realizing end-to-end fusion of visible light and thermal imaging data, coupled with human identification, the system achieves a detection accuracy of **87.2%** and a single-frame processing latency of less than **300 ms**.
- **My Main Work**: Led the design and implementation of a multi-modal fusion module, using **CSPdarknet53-Tiny** to extract features in parallel, concatenate channels, and fuse features at different scales for robust input to the RT-DETR human detection algorithm. Worked on the project documentation and presented the results at the competition.



### 2. 简易自行瞄准装置
**赛事**：全国大学生电子设计竞赛 &emsp; **角色**：第一负责人 &emsp; **时间**：2025.07 – 2025.08
- 项目内容：基于TI MSPM0G3507、灰度传感器、编码电机、K230视觉模块，实现双电池独立供电的自行瞄准系统，支持100cm×100cm赛道多圈循迹、直角转向、参数脱机配置、激光打靶（平均耗时**1.87s**，离靶最远**1.1cm**）。
- 主要工作：硬件集成、整体结构设计、传感器数据处理、PID闭环控制、状态机计数代码编写与硬件电路连接。
- 项目成果：省赛**三等奖**（全省前15%）。

### 3. 三维信道知识地图的构建
**单位**：河海大学李若光副教授课题组 &emsp; **角色**：第一负责人 &emsp; **时间**：2025.10 – 至今
- 项目内容：基于UrbanRadio3D数据集，用Triplane Fitting实现三平面隐式表示与共享MLP训练，结合Triplane Diffusion加噪去噪，输入环境信息即可生成高保真3D信道知识地图，替代高开销3D CNN与伪3D分层方法。
- 主要工作：Triplane Fitting与Triplane Diffusion代码编写、模型训练、消融实验/对比实验、论文撰写。
