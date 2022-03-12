---
title: Bandwidth Optimization Through On-Chip Memory Restructuring for HLS 
publication_types:
  - "1"
authors:
  - Jason Cong
  - Peng Wei
  - Cody Hao Yu
  - admin
publication: "54th Annual Design Automation Conference (ACM DAC 17), acceptance rate: 161/676 = 24%"
abstract: >
  High-level synthesis (HLS) is getting increasing attention from both academia
  and industry for high-quality and high-productivity designs. However, when
  inferring primitive-type arrays in HLS designs into on-chip memory buffers,
  commercial HLS tools fail to effectively organize FPGAs’ on-chip BRAM building
  blocks to realize high-bandwidth data communication; this often leads to
  suboptimal quality of results. This paper addresses this issue via automated
  on-chip buffer restructuring. Specifically, we present three buffer
  restructuring approaches and develop an analytical model for each approach to
  capture its impact on performance and resource consumption. With the proposed
  model, we formulate the process of identifying the optimal design choice into
  an integer non-linear programming (INLP) problem and demonstrate that it can
  be solved efficiently with the help of a one-time C-to-HDL(hardware
  description language) synthesis. The experimental results show that our
  automated source-to-source code transformation tool improves the performance
  of a broad class of HLS designs by averagely 4.8x.
draft: false
featured: false

links: 
#- name: PDF

tags:
  - DAC
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2017-06-17T11:07:12.497Z
---
