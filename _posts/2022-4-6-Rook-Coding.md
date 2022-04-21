---
title: "Rook Coding for Batch Matrix Multiplication"
categories:
  - Journal Publication
tags:
  - matrix multiplication
  - erasure coding
  - coding theory
  - distributed computing
  - information theory
---

Matrix multiplication is a fundamental building block in various distributed computing algorithms. In order to multiply large matrices, it is common practice to distribute the computation into multiple tasks running on different nodes. In order to tolerate stragglers among such nodes, various coding schemes have been proposed by adding additional coded tasks. However, most existing coding schemes for matrix multiplication are constructed for only one matrix multiplication, while batch matrix multiplication is common in large-scale distributed computing workloads. In this paper, we propose Rook Coding (RC), a novel polynomial-based coding framework for computing the multiplication of n pairs of matrices in batch. Designed to achieve lower encoding time in practice, we construct RC as polynomials of much simpler forms than existing coding schemes for batch matrix multiplication, achieving a recovery threshold of O(nlog2 3). Compared to existing coding schemes, RC achieves a lower encoding complexity in practice, because of its simpler forms in the encoding polynomials. Through extensive experiments, we show that RC can save the time of the whole job thanks to its low overhead of encoding.

<cite><a href="https://ieeexplore.ieee.org/abstract/document/9750133">Link to the Publication</a></cite>
