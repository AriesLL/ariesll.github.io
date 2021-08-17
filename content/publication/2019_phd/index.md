---
title: 2019_phd
publication_types:
  - "7"
authors:
  - admin
abstract: >-
  This dissertation investigates design target, modeling, and optimization for
  field-programmable gate array (FPGA) customized computing at chip-level,
  node-level and cluster-level. FPGAs have gained popularity in the acceleration
  of a wide range of applications with 10x-100x performance/energy efficiency
  over the general-purpose processors. The design choices of FPGA accelerators
  for different targets at different levels are enormous. To guide the designers
  to find the best design choices, modeling is inevitable.


  Chip-level performance and energy modeling for embedded and low-power devices. We first study the single chip performance and energy model for FPGA-based pipelined design. Customized pipeline designs that minimize the pipeline initiation interval (II) maximize the throughput of FPGA accelerators designed with high-level synthesis (HLS). However, II>1 can reduce dynamic energy below II=1 due to interconnect savings. We use analytic models to describe accelerator performance and energy, explore the trade-offs of energy and accelerator performance. and find the energy optimal design point.


  Chip-level performance and frequency improvement through locality-aware transformation in HLS. We then study timing degradation problems in HLS-based accelerator design and classify four patterns: scatter, gather, broadcast, and reduce in the context of on-chip data movement. We observe that the on-chip data path delay in these patterns scales up when the design size increases, but HLS tools do not estimate the interconnect delay correctly or make a conscientious effort to control or cap the growth of long interconnect delays at the HLS level. We propose a Latte microarchitecture that features pipelined transfer controllers (PTC) to reduce critical path and improves timing by 1.50x on average.


  Node-level performance and cost modeling for FPGA-enabled, storage-optimized public cloud instances. At node level, We study performance and cost models for customized computing in light of the fact that performance and cost are primary concerns when deploying applications and services in a pay-as-you-go public cloud. The performance and cost modeling are discussed in two aspects, computation resources, with CPUs and locally PCIe-attached accelerators, and storage resources including SSDs and HDDs.


  For computation resources, improved performance using accelerators is accompanied by a higher cost per hour. We discuss the performance and cost modeling of deploying FPGA accelerators, offer insights on accelerator kernel design, and discuss when we should scale up by using FPGA in a node or by choosing a larger instance which has more CPU cores per node. For storage resources, storage systems (SSD/HDD) need to be carefully chosen to match the performance improvement introduced by accelerators while achieving the optimal cost. We conduct quantitative performance analysis on the Spark-based production-quality genome analysis toolkit. We then propose I/O-aware performance analysis and modeling for a broad set of Spark applications. Based on the model, we optimize the cost of genome sequencing in the public cloud by 38%, compared to a configuration recommended by the Spark Official website.


  Cluster-level performance and cost modeling for sharing FPGAs among different instances. From a node-level performance and cost model, we learn that simply offloading accelerated kernels from CPU hosts to PCIe-based FPGAs does not guarantee improvement in terms of out-of-pocket cost when using pay-as-you-go services in a public cloud. We analyze the application execution and conclude that the extra cost is attributable to insufficient application-level speedup by Amdahl’s law. To achieve cost saving with the use of FPGA accelerators in the public cloud, we propose to share one FPGA among multiple CPU instances when the number of CPU cores in one instance cannot fully utilize the FPGA accelerator computation resource. By implementing this idea, we present Mocha framework in this dissertation as a distributed runtime system to optimize the out-of-pocket cost while keeping high speedup and throughput.


  To demonstrate the performance improvement and cost saving of modeling in customized computing, we use genome pipeline optimization in the public cloud and private cloud as case studies showing how to conduct optimal scheduling under certain constraints. In the public cloud, where cost is the primary concern, we formulate how to select instances and schedule genome stages to achieve the least cost given certain deadline constraints as a MILP (mixed integer linear programming) problem. In a private cloud, where hardware (CPU cores, storage disks) is given, we formulate the scheduling of multiple genomes to achieve the least latency, as a MILP problem.
draft: false
featured: false
tags:
  - Thesis
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2021-08-17T11:18:19.911Z
---
