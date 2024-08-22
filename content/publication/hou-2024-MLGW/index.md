---
title: 'Unsupervised Learning of Individual Kohn-Sham States: Interpretable Representations and Consequences for Downstream Predictions of Many-Body Effects'
authors:
- '**Bowen Hou**'
- Jinyuan Wu
- Diana Y Qiu
date: '2024-04-24'
publishDate: '2023-12-19T18:40:22.097091Z'
publication_types:
- article-journal
publication: '*arXiv*'

abstract: Representation learning for the electronic structure problem is a major challenge of machine learning in computational condensed matter and materials physics. Within quantum mechanical first principles approaches, Kohn-Sham density functional theory (DFT) is the preeminent tool for understanding electronic structure, and the high-dimensional wavefunctions calculated in this approach serve as the building block for downstream calculations of correlated many-body excitations and related physical observables. Here, we use variational autoencoders (VAE) for the unsupervised learning of high-dimensional DFT wavefunctions and show that these wavefunctions lie in a low-dimensional manifold within the latent space. Our model autonomously determines the optimal representation of the electronic structure, avoiding limitations due to manual feature engineering and selection in prior work. To demonstrate the utility of the latent space representation of the DFT wavefunction, we use it for the supervised training of neural networks (NN) for downstream prediction of the quasiparticle bandstructures within the GW formalism, which includes many-electron correlations beyond DFT. The GW prediction achieves a low error of 0.11 eV for a combined test set of metals and semiconductors drawn from the Computational 2D Materials Database (C2DB), suggesting that latent space representation captures key physical information from the original data. Finally, we explore the interpretability of the VAE representation and show that the successful representation learning and downstream prediction by our model is derived from the smoothness of the VAE latent space, which also enables the generation of wavefunctions on arbitrary points in latent space. Our work provides a novel and general machine-learning framework for investigating electronic structure and many-body physics.

featured: true
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

url_pdf: https://arxiv.org/abs/2404.14601v1
---
