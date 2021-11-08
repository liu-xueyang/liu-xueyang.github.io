---
title: 'Better machine learning in drones and resource-limited environments '
date: 2021-10-01
permalink: /posts/2021/10/interview/
tags:
  - FPGA
  - DNN
  - Software-Hardware Co-design
  - Interview
---


With machine learning applications flourishing across different platforms, from large-scale data centers to small Internet of Things (IoT) devices, the need for better performance and efficiency keeps growing. In the 2019 system design contest held by Design Automation Conference (DAC), Prof. [Cong Hao](https://sites.gatech.edu/ece-callie/) and her team won the first place with a special software-hardware co-design approach. 

The contest asks the contestants to design a hardware system that runs on real-life drones with Field-Programmable Gate Arrays (FPGA). The drone is tested at the conference with image recognition tasks, and hardware system is measured and compared based on both performance and energy efficiency, where energy efficiency is specifically important for drones because of limited battery resources.

Prof. Hao’s work proposed an software-hardware co-design infrastructure that generates both software machine learning model and FPGA hardware program. On the software side, the infrastructure searches in existing template space and stitch the building blocks to form a multi-layer neural network. On the hardware side, low-latency hardware templates provide an efficient mapping based on generated software model. The actual hardware performance also serves as feedback to the software generator by providing resource and latency analysis, and as datapoints for further optimization. 

Although machine learning acceleration has been a hot topic in computer architecture design, this paper is the first to propose a FPGA solution that applies software hardware co-design approach. The work not only won the first place in 2019 DAC system design contest, but also achieved 40% lower power and 2.5X energy efficiency against previous year first place winner.

During the interview, Prof. Hao mentioned that the DAC design contest served as an initial motivation of this research, and as a good reference point. Her strength in design automation was crucial for coming up with the software-hardware codesign idea. The contest also requires demonstrating on real-life hardware with sensors, cameras etc. and required very careful engineering. However, Prof. Hao mentioned that she was glad to have this opportunity to figure out every engineering detail for the idea to work in real-life systems. 

Prof. Cong Hao is a new faculty in Electrical and Computer Engineering (ECE) department working on accelerator design and hardware design automation. Prof. Hao’s research has been focused on efficient hardware design for machine learning algorithms, reconfigurable hardware, FPGA accelerator and design automation tools.

[Reference]
FPGA/DNN Co-Design: An Efficient Design Methodology for 1oT Intelligence on the Edge. Proceedings of IEEE/ACM Design Automation Conference (DAC), 2019. Cong Hao, Xiaofan Zhang, Yuhong Li, Sitao Huang, Jinjun Xiong, Kyle Rupnow, Wen-Mei Hwu, Deming Chen. [[link]](https://dl.acm.org/doi/10.1145/3316781.3317829)

The interview was motivated by CS 7001 at GaTech - introduction to Graduate Studies.
