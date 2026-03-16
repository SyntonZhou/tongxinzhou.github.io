---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

You may download a PDF version of my CV here: [Download PDF CV]({{ base_path }}/files/Tongxin_Zhou_CV.pdf)

Education
======
**Nanjing University (NJU)**  
M.S. in Integrated Circuit Science and Engineering, Sep. 2025 – Jun. 2028 (expected)  
School of Integrated Circuits, Nanjing, China  
GPA: 4.0/5.0

**Sun Yat-sen University (SYSU)**  
B.Eng. in Microelectronic Science and Engineering, Sep. 2021 – Jun. 2025  
School of Integrated Circuits, Guangzhou, China  
GPA: 86.17/100, Rank: 7/87

Research Interests
======
Hardware/software co-design for efficient AI systems; AI accelerator architecture; efficient LLM inference and compression; FPGA/RTL prototyping; memory systems and dataflow optimization.

Research Experience
======
**VLSI Lab, Nanjing University**  
*Master's Researcher*, Jan. 2025 – Present  
Advisor: Yuxiang Fu

* Investigating hardware/software co-optimization for edge foundation models.
* Studying hardware-aware quantization for mixture-of-experts (MoE) models.
* Designing storage-oriented hardware modules for efficient parameter access.
* Reorganizing quantized weights and scaling factors to better match hardware execution.
* Participating in FPGA validation, including bitstream bring-up, data loading, debugging, and RTL refinement.

**Sun Yat-sen University**  
*Undergraduate Thesis Researcher*, Sep. 2024 – Jun. 2025

* Studied model merging methods for Chinese large language models.
* Explored the integration of LLM merging and quantization for better efficiency-quality trade-offs.
* Investigated how merged models can absorb domain knowledge without increasing model size.
* Thesis recognized as **Excellent Graduation Thesis**.

Publications
======
<ul>
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

Selected Projects
======
**FPGA Processor for Monocular Depth Estimation in Robotic Vision**  
*Undergraduate Innovation and Training Program*

* Designed an FPGA-based hardware processor for machine-learning-based monocular depth estimation.
* Evaluated quantization strategies and developed corresponding hardware acceleration solutions.
* Built a multi-layer hardware prototype toward real-time edge deployment.

**Low-Power, High-Resolution Sigma-Delta Modulator for MEMS Capacitive Accelerometers**  
*Undergraduate Innovation and Training Program, Team Leader*

* Conducted circuit-level research on a low-power sigma-delta modulator.
* Responsible for parameter modeling, circuit design, report writing, and final defense.
* Achieved 16-bit effective resolution, 1.67 μW power consumption, and 101 dB quantization SNR.
* Project recognized as an excellent undergraduate innovation project.

**LAV: LoongArch-Based Accelerator for Vision Workloads**  
*8th National College Student IC Innovation and Entrepreneurship Competition*

* Proposed a customized hardware architecture for visual inference acceleration.
* Contributed to coding, circuit design, simulation testing, board debugging, and live demonstration.
* Awarded **Second Prize, South China Region**.

Honors & Awards
======
* First-Class Outstanding Student Scholarship, Nanjing University, 2025
* Outstanding Graduate of the School, Sun Yat-sen University, 2025
* Third-Class Outstanding Student Scholarship, Sun Yat-sen University, 2024
* Outstanding Core Member, ChipFire Science and Technology Innovation Association, 2024
* Second Prize, South China Region, National College Student IC Innovation and Entrepreneurship Competition, 2024
* National Scholarship, 2023
* First-Class Outstanding Student Scholarship, Sun Yat-sen University, 2023
* First Prize, College Career Planning Competition, Sun Yat-sen University, 2023
* Outstanding Individual, “Three Rurals” Summer Social Practice Campaign, Sun Yat-sen University, 2023
* Second Prize, Guangdong Province, National College Student Electronics Design Contest, 2023
* Special Scholarship, Sun Yat-sen University, 2022
* Second Prize, Guangdong Division, National Mathematical Modeling Contest, 2022

Technical Skills
======
* **Programming:** C, Python, Markdown
* **Hardware / FPGA / RTL:** FPGA prototyping, hardware acceleration design, RTL-based implementation
* **EDA Tools:** Cadence EDA Suite, Vivado, Altium Designer, Proteus, AutoCAD
* **Research Areas:** Quantization, accelerator design, efficient LLM inference, hardware/software co-design

Leadership & Service
======
* Class Monitor for four consecutive years at Sun Yat-sen University
* Vice President, ChipFire Science and Technology Innovation Association
* Graduate Student Union service at Nanjing University
* Organizer for major campus cultural and technology events

English Proficiency
======
* TOEFL iBT: 80/120
* CET-4: 550/710
* CET-6: 485/710

Referees
======
Available upon request — I will do my best to contact them and arrange references.
