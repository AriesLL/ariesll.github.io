---
title: 2022_todaes
publication_types:
  - "2"
authors:
  - Yue Tang
  - Xinyi Zhang
  - Peipei Zhou
  - Jingtong Hu
abstract: Conventionally, DNN models are trained once in the cloud and deployed
  in edge devices such as cars, robots, or unmanned aerial vehicles (UAVs) for
  real-time inference. However, there are many cases that require the models to
  adapt to new environments, domains, or new users. In order to realize such
  domain adaption or personalization, the models on devices need to be
  continuously trained on the device. In this work, we design EF-Train, an
  efficient DNN training accelerator with a unified channel-level
  parallelism-based convolution kernel that can achieve end-to-end training on
  resource-limited low-power edge-level FPGAs. It is challenging to implement
  on-device training on resource-limited FPGAs due to the low efficiency caused
  by different memory access patterns among forward, backward propagation, and
  weight update. Therefore, we developed a data reshaping approach with
  intra-tile continuous memory allocation and weight reuse. An analytical model
  is established to automatically schedule computation and memory resources to
  achieve high energy efficiency on edge FPGAs. The experimental results show
  that our design achieves 46.99 GFLOPS and 6.09GFLOPS/W in terms of throughput
  and energy efficiency, respectively.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2022-02-25T08:04:37.024Z
---
