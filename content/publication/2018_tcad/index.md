---
title: "Caffeine: Towards Uniformed Representation and Acceleration for Deep Convolutional Neural Networks (🔥Best Paper)" 
publication_types:
  - "2"
authors:
  - Chen Zhang
  - Guangyu Sun
  - Zhenman Fang
  - admin
  - Peichen Pan
  - Jason Cong
publication: "IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems ( Volume: 38, Issue: 11, Nov. 2019)"
abstract: With the recent advancement of multilayer convolutional neural
  networks (CNN) and fully connected networks (FCN), deep learning has achieved
  amazing success in many areas, especially in visual content understanding and
  classification. To improve the performance and energy efficiency of the
  computation-demanding CNN, the FPGAbased acceleration emerges as one of the
  most attractive alternatives. In this paper we design and implement Caffeine,
  a hardware/ software co-designed library to efficiently accelerate the entire
  CNN and FCN on FPGAs. First, we propose a uniformed convolutional
  matrixmultiplication representation for both computation-bound convolutional
  layers and communication-bound fully connected (FCN) layers. Based on this
  representation, we optimize the accelerator micro-architecture and maximize
  the underlying FPGA computing and bandwidth resource utilization based on a
  revised roofline model. Moreover, we design an automation flow to directly
  compile high-level network definitions to the final FPGA accelerator. As a
  case study, we integrate Caffeine into the industry-standard software deep
  learning framework Caffe. We evaluate Caffeine and its integration with Caffe
  by implementing VGG16 and AlexNet networks on multiple FPGA platforms.
  Caffeine achieves a peak performance of 1,460 GOPS on a medium-sized Xilinx
  KU060 FPGA board; to our knowledge, this is the best published result. It
  achieves more than 100x speed-up on FCN layers over prior FPGA accelerators.
  An end-to-end evaluation with Caffe integration shows up to 29x and 150x
  performance and energy gains over Caffe on a 12-core Xeon server, and 5.7x
  better energy efficiency over the GPU implementation. Performance projections
  for a system with a high-end FPGA (Virtex7 690t) show even higher gains.
draft: false
featured: false

#url_pdf: https://ieeexplore.ieee.org/abstract/document/8497058/

tags:
  - TCAD
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2018-11-17T11:13:57.518Z
---
