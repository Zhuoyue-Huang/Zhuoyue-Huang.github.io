---
title: 'SigDiffusions: Score-Based Diffusion Models for Time Series via Log-Signature Embeddings'

# Authors
authors:
  - Barbora Barancikova
  - admin
  - Cristopher Salvi

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'
#   - ''

date: '2025-01-22T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-01-22T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *The Thirteenth International Conference on Learning Representations*
publication_short: In *ICLR 2025*

abstract: Score-based diffusion models have recently emerged as state-of-the-art generative models for a variety of data modalities. Nonetheless, it remains unclear how to adapt these models to generate long multivariate time series. Viewing a time series as the discretisation of an underlying continuous process, we introduce SigDiffusion, a novel diffusion model operating on log-signature embeddings of the data. The forward and backward processes gradually perturb and denoise log-signatures while preserving their algebraic structure. To recover a signal from its log-signature, we provide new closed-form inversion formulae expressing the coefficients obtained by expanding the signal in a given basis (e.g. Fourier or orthogonal polynomials) as explicit polynomial functions of the log-signature. Finally, we show that combining SigDiffusions with these inversion formulae results in high-quality long time series generation, competitive with the current state-of-the-art on various datasets of synthetic and real-world examples.

# Summary. An optional shortened abstract.
summary: A novel approach combining score-based diffusion models with log-signature embeddings for advanced time series modeling and generation.

tags:
  - Diffusion Models
  - Time Series
  - Signature Methods
  - Machine Learning

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: "10.48550/arXiv.2406.10354"

# Custom links
links:
  - type: pdf
    url: "7265_SigDiffusions_Score_Based.pdf"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
projects: []

# Slides (optional).
slides: ""
---

<!-- This work introduces SigDiffusions, a groundbreaking method that bridges the gap between the rich mathematical theory of signatures and the powerful generative capabilities of diffusion models for time series data.

The log-signature embedding provides a principled way to capture the essential characteristics of temporal sequences while preserving their geometric structure. When combined with score-based diffusion models, this approach enables robust generation and modeling of complex time series patterns.

Key contributions include:
- A novel framework combining signature methods with diffusion models
- Theoretical analysis of the approach's properties
- Empirical validation on diverse time series datasets
- Demonstration of improved performance over existing methods -->