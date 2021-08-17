---
title: SODA Stencil with Optimized Dataflow Architecture (🔥Best Paper Nominee).
publication_types:
  - "0"
authors:
  - Yuze Chi
  - Jason Cong
  - Peng Wei
  - admin
publication: 2018 International Conference On Computer Aided Design
abstract: >-
  Stencil computation is one of the most important kernels in many application
  domains such as image processing, solving partial diferential equations, and
  cellular automata. Many of the stencil kernels are complex, usually consist of
  multiple stages or iterations, and are often computation-bounded. Such kernels
  are often off-loaded to FPGAs to take advantages of the efficiency of
  dedicated hardware. However, implementing such complex kernels efficiently is
  not trivial, due to complicated data dependencies, difficulties of programming
  FPGAs with RTL, as well as large design space.

  In this paper we present SODA, an automated framework for implementing Stencil algorithms with Optimized Datalow Architecture on FPGAs. The SODA microarchitecture minimizes the on-chip reuse bufer size required by full data reuse and provides flexible and scalable fine-grained parallelism. The SODA automation framework takes high-level user input and generates efficient, high-frequency datalow implementation. This significantly reduces the difficulty of programming FPGAs efficiently for stencil algorithms. The SODA design-space exploration framework models the resource constraints and searches for the performance-optimized coniguration with accurate models for post-synthesis resource utilization and on-board execution throughput. Experimental results from on-board execution using a wide range of benchmarks show up to 3.28x speed up over 24-thread CPU and our fully automated framework achieves better performance compared with manually designed state-of-the-art FPGA accelerators.
draft: false
featured: false
url_pdf: http://vast.cs.ucla.edu/~chiyuze/pub/iccad18.pdf
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2021-08-17T08:44:06.201Z
---
