---
title: "MOCHA: Multinode Cost Optimization in Heterogeneous Clouds with Accelerators"
publication_types:
  - "1"
authors:
  - admin
  - Jiayi Sheng
  - Cody Hao Yu
  - Peng Wei
  - Jie Wang
  - Di Wu
  - Jason Cong
publication: 2021 ACM/SIGDA International Symposium on Field Programmable Gate Arrays (FPGA ’21)
abstract: FPGAs have been widely deployed in public clouds, e.g., Amazon Web
  Services (AWS) and Huawei Cloud. However, simply offloading accelerated
  kernels from CPU hosts to PCIe-based FPGAs does not guarantee out-of-pocket
  cost savings in a pay-as-you-go public cloud. Taking Genome Analysis Toolkit
  (GATK) applications as case studies, although the adoption of FPGAs reduces
  the overall execution time, it introduces 2.56× extra cost, due to
  insufficient application-level speedup by Amdahl’s law. To optimize the
  out-of-pocket cost while keeping high speedup and throughput, we propose Mocha
  framework as a distributed runtime system to fully utilize the accelerator
  resource by accelerator sharing and CPU-FPGA partial task offloading.
  Evaluation results on HaplotypeCaller (HTC) and Mutect2 in GATK show that on
  AWS, Mocha saves on the application cost by 2.82x for HTC, 1.06x for Mutect2
  and on Huawei Cloud by 1.22x, 1.52x respectively than straightforward CPU-FPGA
  integration solution with less than 5.1% performance overhead.

draft: false
featured: true
links:
- name: Slides
  url: "FPGA_2021Mocha.pptx"
- icon: youtube
  icon_pack: fab
  name: Video
  url: https://www.youtube.com/watch?v=bdlyJkILENc

#links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://vast.cs.ucla.edu/~peipei/papers/fpga21_mocha.pdf
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides = "FPGA_2021Mocha.pptx"
#url_source: '#'
#url_video: '#'
projects:
  - mocha
slides: mocha
tags:
  - FPGA
image:
  filename: mocha_thumbnail.jpg
  focal_point: Smart
  preview_only: false
date: 2021-05-14T09:27:29.087Z
---
