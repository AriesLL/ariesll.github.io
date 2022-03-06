---
title: Algorithm-hardware Co-design of Attention Mechanism on FPGA Devices 
publication_types:
  - "2"
authors:
  - Xinyi Zhang
  - Yawen Wu
  - admin
  - Xulong Tang
  - Jingtong Hu
publication: ACM Transactions on Embedded Computing Systems (TECS 21)
abstract: Multi-head self-attention (attention mechanism) has been employed in a variety of fields such as machine translation, language modeling, and image processing due to its superiority in feature extraction and sequential data analysis. This is benefited from a large number of parameters and sophisticated model architecture behind the attention mechanism. To efficiently deploy attention mechanism on resource-constrained devices, existing works propose to reduce the model size by building a customized smaller model or compressing a big standard model. A customized smaller model is usually optimized for the specific task and needs effort in model parameters exploration. Model compression reduces model size without hurting the model architecture robustness, which can be efficiently applied to different tasks. The compressed weights in the model are usually regularly shaped (e.g. rectangle) but the dimension sizes vary (e.g. differs in rectangle height and width). Such compressed attention mechanism can be efficiently deployed on CPU/GPU platforms as their memory and computing resources can be flexibly assigned with demand. However, for Field Programmable Gate Arrays (FPGAs), the data buffer allocation and computing kernel are fixed at run time to achieve maximum energy efficiency. After compression, weights are much smaller and different in size, which leads to inefficient utilization of FPGA on-chip buffer. Moreover, the different weight heights and widths may lead to inefficient FPGA computing kernel execution. Due to the large number of weights in the attention mechanism, building a unique buffer and computing kernel for each compressed weight on FPGA is not feasible. In this work, we jointly consider the compression impact on buffer allocation and the required computing kernel during the attention mechanism compressing. A novel structural pruning method with memory footprint awareness is proposed and the associated accelerator on FPGA is designed. The experimental results show that our work can compress Transformer (an attention mechanism based model) by 95x. The developed accelerator can fully utilize the FPGA resource, processing the sparse attention mechanism with the run-time throughput performance of 1.87 Tops in ZCU102 FPGA.

draft: false
featured: false
tags:
  - TECS 
  - ESWEEK
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2021-09-29T16:36:48.458Z
---
