---
title: "CS-BWAMEM: A fast and scalable read aligner at the cloud scale for whole genome sequencing" 
publication_types:
  - "3"
authors:
  - Yu-Ting Chen
  - Jason Cong
  - Jie Lei
  - Sen Li
  - Myron Peto
  - Paul Spellman
  - Peng Wei
  - admin
publication: "High Throughput Sequencing, Algorithms & Applications, A SIG of IMSB/ECCB 2015"
abstract: The deep-coverage whole-genome sequencing (WGS) can generate billions
  of reads to be sequenced. It is time consuming for state-of-the-art aligners,
  such as BWA-MEM, to align the tremendous number of reads onto the reference
  genome. Inherently, the reads can be aligned using a massively parallel
  approach, and the alignment process should not be bounded by the limited
  number of computing cores of a single server. We present cloudscale BWAMEM
  (CS-BWAMEM), an ultrafast and highly scalable aligner built on top of cloud
  infrastructures. It leverages the abundant computing resources in a public or
  private cloud to fully exploit the parallelism obtained from the enormous
  number of reads. With CSBWAMEM, the pair-end whole-genome reads (30x) can be
  aligned within 80 minutes in a 25-node cluster with 300 cores.
draft: false
featured: false
links:
#- name: PDF
- name: Poster
  url: https://peipeizhou-eecs.github.io/uploads/poster/hitseq2015_CSBWAMEM_poster.pdf

tags:
  - HITSEQ
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2015-08-17T11:11:01.653Z
---
