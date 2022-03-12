---
title: "Doppio: I/O-Aware Performance Analysis, Modeling and Optimization for In-Memory Computing Framework(🔥Best Paper Nominee)"
publication_types:
  - "1"
authors:
  - admin
  - Zhenyuan Ruan
  - Zhenman Fang
  - Megan Shand
  - David Roazen
  - Jason Cong
publication: "2018 IEEE International Symposium on Performance Analysis of Systems and Software (ISPASS 18)"
abstract: "In conventional Hadoop MapReduce applications, I/O used to play a
  heavy role in the overall system performance. More recently, a study from the
  Apache Spark community—state-of-the-art in-memory cluster computing
  framework—reports that I/O is no longer the bottleneck and has a marginal
  performance impact on applications like SQL processing. However, we observe
  that simply replacing HDDs with SSDs in a Spark cluster can have over 10x
  performance improvement for certain stages in large-scale production-quality
  genome processing. Therefore, one key question arises: How does I/O
  quantitatively impact the performance of today’s big data applications
  developed using in-memory cluster computing frameworks like Apache Spark? In
  this paper we select an important yet complex application—the Spark-based
  Genome Analysis ToolKit (GATK4)—to guide our modeling. We first use different
  combinations of HDDs and SSDs to measure the I/O impact on GATK4 and change
  the CPU core number to discover the relation between computation and I/O
  access. Combining with Spark underlying implementations, we further analyze
  the inherent cause of the above observations and build our model based on the
  analysis. Although building upon GATK4, our model maintains generality to
  other applications. Experimental results show that we can achieve an
  performance prediction error rate within 10% for typical Spark applications of
  both iterative and shuffle-heavy algorithms. Finally, we further extend our
  model to a broader area - that of optimal configuration selection in the
  public cloud. In Google Cloud, our model enables us to save 38% to 57% cost
  for genome sequencing compared with its recommended default configurations.
  Currently, more and more companies are adopting cloud computing for specific
  workloads. Our proposed model can have a huge impact on their choices, while
  also enabling them to significantly reduce their costs."
draft: false
featured: false
links:
#- name: PDF
- name: Slides
  url: https://peipeizhou-eecs.github.io/uploads/slides/ISPASS18_Doppio_withoutAudio.pptx
- name: SlidesWithAudio
  url: https://peipeizhou-eecs.github.io/uploads/slides/ISPASS18_Doppio_withAudio.pptx

tags:
  - ISPASS
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2018-05-18T11:06:06.481Z
---
