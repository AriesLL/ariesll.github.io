---
title: "ARAPrototyper: Enabling Rapid Prototyping and Evaluation for Accelerator-Rich Architecture" 
publication_types:
  - "3"
authors:
  - Yu-Ting Chen
  - Jason Cong
  - Zhenman Fang
  - admin
publication: "24th ACM/SIGDA International Symposium on Field-Programmable Gate Arrays (ACM/SIGDA FPGA 16)"
abstract: Compared to conventional general-purpose processors, accelerator-rich
  architectures (ARAs) can provide orders-of-magnitude performance and energy
  gains. In this paper we design and implement the ARAPrototyper to enable rapid
  design space explorations for ARAs in real silicons and reduce the tedious
  prototyping efforts. First, ARAPrototyper provides a reusable baseline
  prototype with a highly customizable memory system, including interconnect
  between accelerators and buffers, interconnect between buffers and last-level
  cache (LLC) or DRAM, coherency choice at LLC or DRAM, and address translation
  support. To provide more insights into performance analysis, ARAPrototyper
  adds several performance counters on the accelerator side and leverages
  existing performance counters on the CPU side. Second, ARAPrototyper provides
  a clean interface to quickly integrate a user?s own accelerators written in
  high-level synthesis (HLS) code. Then, an ARA prototype can be automatically
  generated and mapped to a Xilinx Zynq SoC. To quickly develop applications
  that run seamlessly on the ARA prototype, ARAPrototyper provides a system
  software stack and abstracts the accelerators as software libraries for
  application developers. Our results demonstrate that ARAPrototyper enables a
  wide range of design space explorations for ARAs at manageable prototyping
  efforts and 4,000 to 10,000X faster evaluation time than full-system
  simulations. We believe that ARAPrototyper can be an attractive alternative
  for ARA design and evaluation.
draft: false
featured: false
links:
- name: PDF
  url: https://arxiv.org/abs/1610.09761
- name: Poster
  url: https://peipeizhou-eecs.github.io/uploads/poster/ARAPrototyper_FPGA_2016_poster.pdf

tags:
  - FPGA
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2016-02-17T11:10:10.250Z
---
