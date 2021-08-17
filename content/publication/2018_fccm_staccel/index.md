---
title: 2018_fccm_staccel
publication_types:
  - "1"
authors:
  - Zhenyuan Ruan
  - Tong He
  - Bojie Li
  - admin
  - Jason Cong
publication: "2018 IEEE International Symposium on Field-Programmable Custom Computing Machines (FCCM'18), full paper acceptance ratio: 22/106 = 20.7%"
abstract: >-
  In recent years we have witnessed the emergence of the FPGA in many
  high-performance systems. This is due to FPGA's high reconfigurability and
  improved user-friendly programming environment. OpenCL, supported by major
  FPGA vendors, is a high-level programming platform that liberates hardware
  developers from having to deal with the complex and error-prone HDL
  development. While OpenCL exposes a GPU-like programming model, which is
  well-suited for compute-intensive tasks, in many state-of-art systems that
  deploy FPGA, we observe that the workloads are streaming-like, which is
  communication-intensive. This mismatch leads to low throughput and high
  end-to-end latency.

  In this paper, we propose ST-Accel, a new high-level programming platform for streaming applications on FPGA. It has the following advantages: (i) ST-Accel adopts the multiprocessing programming model to capture the inherent pipeline-level parallelism of streaming applications while reducing the end-to-end latency. (ii) A message-passing-based host/FPGA communication model is used to avoid the coherency issue of shared memory, thus enabling host/FPGA communication during kernel execution. (iii) ST-Accel provides a high-level abstraction for I/O devices to support direct I/O device access that eliminates the overhead of host CPU and reduces the I/O latency. (iv) ST-Accel enables the decoupled access/execute architecture to maximize the utilization of I/O devices. (v) The host/FPGA communication interface is redesigned to cater to the demands of both latency-critical and throughput-critical scenarios. The experimental results on the Amazon AWS cloud and local machine show that ST-Accel can achieve 1.6X-166X throughput and 1/3 latency for typical streaming workloads when compared to OpenCL.
draft: false
featured: false

url_pdf: http://vast.cs.ucla.edu/sites/default/files/publications/st-accel-high.pdf
tags:
  - FCCM
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2018-05-16T11:04:02.914Z
---
