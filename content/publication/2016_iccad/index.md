---
title: "Caffeine: Towards Uniformed Representation and Acceleration for Deep Convolutional Neural Networks"
publication_types:
  - "1"
authors:
  - Chen Zhang
  - Zhenman Fang
  - admin
  - Peichen Pan
  - Jason Cong
publication: "36th International Conference on Computer-Aided Design (ACM ICCAD 16), acceptance rate: 97/408 = 23.8%"
abstract: >
  With the recent advancement of multilayer convolutional neural networks (CNN),
  deep learning has achieved amazing success in many areas, especially in visual
  content understanding and classification. To improve the performance and
  energy-efficiency of the computation-demanding CNN, the FPGA-based
  acceleration emerges as one of the most attractive alternatives. In this paper
  we design and implement Caffeine, a hardware/soft-ware co-designed library to
  efficiently accelerate the entire CNN on FPGAs. First, we propose a uniformed
  convolutional matrix-multiplication representation for both
  computation-intensive con-volutional layers and communication-intensive fully
  connected (FCN) layers. Second, we design Caffeine with the goal to maximize
  the underlying FPGA computing and bandwidth resource utilization , with a key
  focus on the bandwidth optimization by the memory access reorganization not
  studied in prior work. Moreover , we implement Caffeine in the portable
  high-level synthesis and provide various hardware/software definable
  parameters for user configurations. Finally, we also integrate Caffeine into
  the industry-standard software deep learning framework Caffe. We evaluate
  Caffeine and its integration with Caffe by implementing VGG16 and AlexNet
  network on multiple FPGA platforms. Caffeine achieves a peak performance of
  365 GOPS on Xilinx KU060 FPGA and 636 GOPS on Virtex7 690t FPGA. This is the
  best published result to our best knowledge. We achieve more than 100x speedup
  on FCN layers over previous FPGA accelerators. An end-to-end evaluation with
  Caffe integration shows up to 7.3x and 43.5x performance and energy gains over
  Caffe on a 12-core Xeon server, and 1.5x better energy-efficiency over the GPU
  implementation on a medium-sized FPGA (KU060). Performance projections to a
  system with a high-end FPGA (Virtex7 690t) shows even higher gains.
draft: false
featured: false

links:
#- name: PDF
- name: Slides
  url: https://peipeizhou-eecs.github.io/uploads/slides/ICCAD2016_5th_withoutAudio.pptx
- name: SlidesWithAudio
  url: https://peipeizhou-eecs.github.io/uploads/slides/ICCAD2016_5th_withAudio.pptx
- name: Poster
  url: https://peipeizhou-eecs.github.io/uploads/poster/ICCAD_HALO_Caffeine_poster_2.pdf 

tags:
  - ICCAD
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2016-11-17T11:08:12.200Z
---
