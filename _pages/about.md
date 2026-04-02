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

I hold my undergraduate study from Hohai University (211,Double First-Class), with strong academic performance and solid programming skills in Python and C.

If everything goes as expected, I will obtain the qualification for direct admission to graduate school this year.I am actively seeking  for **Research Internship, Master's degree or directly pursuing a doctoral degree**.

---

## Scientific Research Experience & Competition

### 1.Triplane Diffusion for 3DCKM construction
- **Project Brief**:现有3DCKM的构建方法多基于计算开销大的3D CNN方法(3D-RadioDiff)以及伪3D的分层方法(CKMDiff)。项目基于UrbanRadio3D数据集，利用Tripane Fitting和Triplane Diffusion对三维数据进行压缩以及加噪与去噪。针对新场景将环境信息作为条件，将扩散模型所得结果送入预训练的MLP即可构建高保真的信道知识地图。
- **My Main Work**:①在Triplane Fitting阶段采用任务重现与权重更新策略分两阶段联合训练数据集的三平面表示以及共享MLP；②在Triplane Diffusion阶段以环境信息为条件，使用条件概率扩散模型对所得三平面进行加噪与去噪；③消融实验和对比实验。


### 2.Discrimination of human targets in thick smoke environments
**Competition**：中国大学生服务外包创新创业大赛 💻[Demo Code](https://github.com/XoomitLXH/Smoke-Human-Detection.git)

**Time**：2024.12 – 2025.04

<img width="320" height="180" alt="framework" src="https://github.com/user-attachments/assets/c6814210-3d29-4b57-8e26-4a4c89d70d46" />

- **Project Brief**: Aiming to prove the performance degradation of visible light sensors and the rescue response delay of conventional firefighting robots in dense smoke environments, this project integrates multiple advanced techniques: spatiotemporal alignment, dual-branch multimodal fusion, contrast-guided dehazing, dark-channel-prior-based smoke removal, and the RT-DETR human detection algorithm. By realizing end-to-end fusion of visible light and thermal imaging data, coupled with human identification, the system achieves a detection accuracy of **87.2%** and a single-frame processing latency of less than **300 ms**.
- **My Main Work**: Led the design and implementation of a multi-modal fusion module, using **CSPdarknet53-Tiny** to extract features in parallel, concatenate channels, and fuse features at different scales for robust input to the RT-DETR human detection algorithm. Worked on the project documentation and presented the results at the competition.


### 3.Simple automatic shooting device
**Competition**：全国大学生电子设计竞赛

**Time**：2025.07 – 2025.07

<img src="https://github.com/user-attachments/assets/7064feab-caae-4d1b-963c-b9d1eb24f5d4" alt="自动射击装置示意图1" width="300" /> 
<img src="https://github.com/user-attachments/assets/1d6c2878-0ad9-48ce-a325-7c3613f5cd15" alt="自动射击装置示意图2" width="300" />

- **Project Brief**: By utilizing **TI MSPM0G3507**, grayscale sensor, encoded motor, **K230** vision module and other peripheral devices, a simple automatic shooting device was designed and implemented. The system can complete the specified number of laps on a 1m×1m black square track (each lap takes approximately 18 seconds), right-angle turns, and offline parameter configuration (tracking speed, turning speed, PID parameters), and control the two-dimensional gimbal servo to perform laser target shooting (the average shooting time is 1.87 seconds, and the farthest distance from the target is 1.1 cm).
- **My Main Work**: ①Responsible for the hardware circuit design and connection; ② Code logic design and writing for grayscale tracking sensors, encoded motors, PID closed-loop control, and state machine multi-loop counting.

