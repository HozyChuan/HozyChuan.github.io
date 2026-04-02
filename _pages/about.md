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

<img width="320" height="180" alt="Triplane Diffusion frame for 3DCKM Construction)" src="https://github.com/user-attachments/assets/82b41608-7a6f-4e1d-b063-05cac0e96782" />

- **Project Brief**:The existing construction methods of 3DCKM are mostly based on computationally expensive 3D CNN methods (3D-RadioDiff) and pseudo-3D slice methods (CKMDiff). The project is based on the UrbanRadio3D dataset and uses Tripane Fitting and Triplane Diffusion to compress data and then add noise and remove noise from the triplanes data. For new scenes, environmental information is used as a condition, and the results obtained from the diffusion model are sent to the pre-trained MLP to construct a high-fidelity channel knowledge map.
- **My Main Work**:① In the Triplane Fitting stage, the task replay and Identity-aware Weight Consolidation (IWC) regularizer
are used to jointly train the Triplane representations and shared MLP of the data set in two stages; ② In the Triplane Diffusion stage, using the environmental information as a condition, the conditional probability diffusion model is employed to add noise and remove noise to the obtained Triplanes; ③ Abandonment experiments and comparison experiments.I'm struggling to complete this idea and hoping for a paper.
- **Sionna**:I wrote a 3DCKM construction code using sionna.[Click here](https://github.com/HozyChuan/Voxel-CKMDataSet-by-Sionna.git) for the code.

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

