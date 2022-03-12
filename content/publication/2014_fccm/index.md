---
title: "A Fully Pipelined and Dynamically Composable Architecture of CGRA" 
publication_types:
  - "1"
authors:
  - Jason Cong
  - Hui Huang
  - Chiyuan Ma
  - Bingjun Xiao
  - admin
publication: "22nd IEEE International Symposium on Field-Programmable Custom Computing Machines (IEEE FCCM 14)"
abstract: Future processor chips will not be limited by the transistor
  resources, but will be mainly constrained by energy efficiency. Reconfigurable
  fabrics bring higher energy efficiency than CPUs via customized hardware that
  adapts to user applications. Among different reconfigurable fabrics,
  coarse-grained reconfigurable arrays (CGRAs) can be even more efficient than
  fine-grained FPGAs when bit-level customization is not necessary in target
  applications. CGRAs were originally developed in the era when transistor
  resources were more critical than energy efficiency. Previous work shares
  hardware among different operations via modulo scheduling and time
  multiplexing of processing elements. In this work, we focus on an emerging
  scenario where transistor resources are rich. We develop a novel CGRA
  architecture that enables full pipelining and dynamic composition to improve
  energy efficiency by taking full advantage of abundant transistors. Several
  new design challenges are solved. We implement a prototype of the proposed
  architecture in a commodity FPGA chip for verification. Experiments show that
  our architecture can fully exploit the energy benefits of customization for
  user applications in the scenario of rich transistor resources.
draft: false
featured: false

links:
#- name: PDF
- name: Slides
  url: https://peipeizhou-eecs.github.io/uploads/slides/FCCM_FPCA_talk_without_audio_final.ppt

tags:
  - FCCM
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2014-05-17T11:12:17.735Z
---
