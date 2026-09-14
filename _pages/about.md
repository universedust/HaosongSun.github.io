---
permalink: /
title: "Haosong Sun"
excerpt: "Robotics master's student researching embodied intelligence, vision-language models, and visual reasoning."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Hello, I am **Haosong Sun**, a master's student in Robotics at the Faculty of Engineering, The Chinese University of Hong Kong (CUHK). I received my B.Eng. in Electronic Information Engineering from the School of Information and Communication Engineering at Beijing University of Posts and Telecommunications (BUPT), where I ranked in the top 15% of my class.

My research focuses on **embodied intelligence, vision-language models (VLMs/VLAs), and visual reasoning**. I am interested in building agents that can understand complex environments, plan long-horizon tasks, and act reliably in the real world.

[Download Resume PDF (Chinese)]({{ site.baseurl }}/files/CV_HaosongSun.pdf){: .btn .btn--primary}
[View Online CV]({{ site.baseurl }}/cv/){: .btn .btn--inverse}

## Research Interests

- **Embodied intelligence**: VLMs/VLAs, WAM architectures, long-horizon task planning, and real-robot deployment
- **Multimodal reasoning**: GRPO, reasoning self-consistency verification, and visual-evidence verification
- **Computer vision**: complex-scene exposure assessment, intrinsic decomposition, and Deep Unfolding

## Education

**The Chinese University of Hong Kong (CUHK), Faculty of Engineering** · M.Sc. in Robotics  
2026 - 2028

**Beijing University of Posts and Telecommunications (BUPT), School of Information and Communication Engineering** · B.Eng. in Electronic Information Engineering  
2022 - 2026 · Ranked in the top 15% of the class

## Industry Experience

### Beijing Humanoid Robot Innovation Center

**Large Model Algorithm Engineer** · 2026.04 - 2026.07

- **Long-horizon planning benchmark**: Built an evaluation benchmark from daily-task data collected by the Tiangong robot, covering subtask planning and replanning across 150+ tasks and approximately 2,000 video-question pairs; evaluated open-source VLM/VLA families for long-horizon planning and general multimodal capabilities.
- **VLM Planner training**: Performed SFT on Qwen3.5-9B with failure recovery, planning, spatial & physical, and general-purpose data, improving performance on Paibench-U and a self-built benchmark.
- **WAM architecture validation**: Contributed to ablation studies, training, and evaluation of two generations: Qwen3-VL & Decoupled Timestep and Qwen3.5 & Chunk-AR, exploring joint video-action diffusion and chunk-level autoregressive training.
- **Real-robot deployment**: Trained on data from multiple robot embodiments and simulation environments, and completed real-robot inference deployment.

## Research Experience

### Enhancing Visual Reasoning with Dual-Path Verification GRPO

2025.11 - 2026.01

- Added reasoning self-consistency verification and visual-evidence verification on top of the accuracy reward; designed reward rules based on sufficiency relationships to provide fine-grained credit assignment for visual reasoning quality.
- Designed self-supervised quality signals without external stronger models or human annotations. Policy self-reward enabled self-verification, while the visual-evidence bonus was used only during within-group relative ranking.
- Trained open-source model families on a self-built visual reasoning dataset. Reinforcement learning consistently improved accuracy and reasoning quality while preserving capabilities on other task types, outperforming other Vision-R1-style approaches.

### Exposure Assessment for Images in Complex Scenes (Under Review)

2025.08 - 2026.01

- Modeled exposure distortion caused by spatially non-uniform illumination and its coupling with object albedo as a pixel-level optimization problem, enabling fine-grained characterization of local exposure information loss.
- Jointly modeled exposure zoning and intrinsic decomposition, explicitly separating object albedo from illumination changes to improve exposure identification in complex scenes.
- Built a variational-optimization-based Deep Unfolding model and a new dataset of approximately 60k samples covering extreme albedo and mixed-exposure scenes. The method significantly outperformed more than 20 baseline methods on SSIM and PSNR.

## Publication

**Pelican-Unify 1.0: A Unified Embodied Intelligence Model for Understanding, Reasoning, Imagination and Action.**  
Technical Report · [arXiv:2605.15153](https://arxiv.org/abs/2605.15153)

## Skills & Contact

- **Programming**: Python
- **English**: IELTS 7.0
- **Email**: <mrsun666@126.com>
- **Phone / WeChat**: 13341123095

## Honors

- Third-Class Scholarship, Beijing University of Posts and Telecommunications, 2024/2025 academic year
- Third-Class Scholarship, Beijing University of Posts and Telecommunications, 2023/2024 academic year
