---
title: 'Data-driven Low-rank Approximation for Electron-hole Kernel and Acceleration of Time-dependent GW Calculations'
authors:
- 'Bowen Hou'
- Jinyuan Wu
- Victor Chang Lee
- Jiaxuan Guo
- Luna Y. Liu
- Diana Y Qiu
date: '2025-02-08'
publishDate: '2025-02-08T18:40:22.097091Z'
publication_types:
- article-journal
publication: '*arXiv*'

abstract: Many-body electron-hole interactions are essential for understanding non-linear optical processes and ultrafast spectroscopy of materials. Recent first principles approaches based on nonequilibrium Green's function formalisms, such as the time-dependent adiabatic GW (TD-aGW) approach, can predict the nonequilibrium dynamics of excited states including electron-hole interactions. However, the high dimensionality of the electron-hole kernel poses significant computational challenges for scalability. Here, we develop a data-driven low-rank approximation for the electron-hole kernel, leveraging localized excitonic effects in the Hilbert space of crystalline systems. Through singular value decomposition (SVD) analysis, we show that the subspace of non-zero singular values, containing the key information of the electron-hole kernel, retains a small size even as the k-grid grows, ensuring computational feasibility with extremely dense k-grids for converged calculations. Utilizing this low-rank property, we achieve at least 95% compression of the kernel and an order-of-magnitude speedup of TD-aGW calculations. Our method, rooted in physical interpretability, outperforms existing machine learning approaches by avoiding intensive training processes and eliminating time-accumulated errors, providing a general framework for high-throughput, nonequilibrium simulation of light-driven dynamics in materials.

featured: true
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

url_pdf: https://arxiv.org/abs/2502.05635
---
