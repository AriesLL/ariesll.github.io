---
title: "Algorithm-Hardware Co-design for BQSR Acceleration in Genome Analysis ToolKit"
publication_types:
  - "1"
authors:
  - Michael Lo
  - Zhenman Fang
  - Jie Wang
  - admin
  - Mau-Chung Frank Chang
  - Jason Cong
publication: 2020 IEEE International Symposium on Field-Programmable Custom Computing Machines (FCCM'20)
abstract: "Genome sequencing is one of the most important applications in healthcare and has a great potential to realize precision medicine and personalized healthcare. However, its computing process is very time consuming. Even pre-processing the raw sequence data of a whole genome for a single person to the analysis ready data can take several days on a single-core CPU.

In this paper, we propose to accelerate the performance of the widely used Genome Analysis ToolKit (GATK) using FPGAs. More specifically, we focus on the algorithm and hardware codesign for the Base Quality Score Re-calibration (BQSR) step in GATK, which is an important and time-consuming step to correct systematic errors made by a sequencing machine. Prior studies did not consider hardware acceleration for BQSR because it requires a large amount of memory with random access and has a lot of control flow. To address these challenges, we first adapt the algorithm to resolve the random memory access conflicts to achieve a fully pipelined accelerator design and reduce its dataset size. Second, we leverage the newly introduced large-capacity UltraRAM (URAM) in Xilinx UltraScale+ FPGAs to buffer BQSR’s large dataset on chip, and further optimize its operating frequency. Finally, we also explore the coarse-grained pipeline and parallelism to improve the overall performance of the BQSR accelerator. Compared to the latest software implementation of GATK 4.1 running on single-thread and 56-thread CPUs (14nm Xeon E5-2680 v4), our FPGA accelerator running on Xilinx 16nm UltraScale+ VCU1525 board achieves up to 40.7x and 8.5x speedups, respectively."

draft: false
featured: true
#links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://vast.cs.ucla.edu/~peipei/papers/fccm20_BQSR_2020.pdf
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'
projects:
slides: 
date: 2021-08-17T09:27:29.087Z
---
