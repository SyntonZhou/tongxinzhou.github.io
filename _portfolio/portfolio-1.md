---
title: "Edge Foundation Models: Hardware/Software Co-Optimization for Efficient MoE Inference"
excerpt: "Research on quantization, storage organization, and FPGA validation for efficient deployment of mixture-of-experts models on resource-constrained platforms.<br/><img src='/images/portfolio-moe-fpga.png'>"
collection: portfolio
---

This project studies **hardware/software co-optimization for edge deployment of foundation models**, with a particular focus on **mixture-of-experts (MoE) inference** under tight resource constraints.

My work centers on how algorithmic compression techniques can be translated into **real hardware efficiency** rather than remaining only as software-side improvements. In this project, I explored the interaction among **quantization strategy, parameter layout, storage organization, and hardware execution flow** for MoE models.

## What I worked on

- Investigated **hardware-aware quantization methods for MoE models**, focusing on the efficiency–quality trade-off in practical deployment scenarios.
- Designed and optimized **storage-oriented hardware modules** to improve parameter access efficiency.
- Reorganized quantized weights and scaling factors so that the model representation better matched hardware execution patterns.
- Participated in **FPGA-based validation**, including bitstream bring-up, data writing, debugging, and iterative RTL refinement.

## Why this project matters

Large models are increasingly constrained not only by arithmetic cost, but also by **memory movement, parameter management, and deployment complexity**. This project helped me develop a systems-level view of efficient inference: model compression becomes most valuable when it is co-designed with the target architecture, memory hierarchy, and execution schedule.

## My role

I contributed to both the **algorithm–hardware interface** and the **implementation side**, especially in quantization-oriented hardware adaptation, storage-module design, parameter reordering, and FPGA bring-up.

**Status:** Ongoing laboratory research project at Nanjing University.  
**Related output:** Contributed to a manuscript on quantization techniques for MoE models.
