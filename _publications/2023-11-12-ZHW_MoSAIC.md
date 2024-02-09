---
title: "Accelerator integration in a tile-based SoC: lessons learned with a hardware floating point compression engine"
collection: publications
permalink: /publication/2023-11-ZHW-MoSAIC
#excerpt: '.'
date: 2023-11-12
venue: 'SC-W '23: Proceedings of the SC '23 Workshops of The International Conference on High Performance Computing, Network, Storage, and Analysis'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3624062.3624245'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

Heterogeneous Intellectual Property (IP) hardware acceleration engines have emerged as a viable path forward to improving performance in the waning of Moore’s Law and Dennard scaling. In this study, we design, prototype, and evaluate the HPC-specialized ZHW floating point compression accelerator as a resource on a System on Chip (SoC). Our full hardware/software implementation and evaluation reveal inefficiencies at the system level that significantly throttle the potential speedup of the ZHW accelerator. By optimizing data movement between CPU, memory, and accelerator, 6.9X is possible compared to a RISC-V64 core, and 2.9X over a Mac M1 ARM core.
