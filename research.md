---
layout: page
title: Research
permalink: /research
---

**Focus areas**: RNA-seq simulation and benchmarking · Gaussian–Cox hierarchical simulators · Deconvolution & tumor microenvironment · ML/LLM integration for biological interpretability.

### Benchmarking RNA-seq Simulators
I evaluated seven widely used RNA-seq simulators (CompcodeR, Seqgendiff, SimSeq, SPsimseq, Splatter, PowsimR, SimBu) for their ability to reproduce dispersion patterns, mean–variance trends, differential expression signals, PCA structure, and gene–gene covariance. The study highlights trade-offs between statistical fidelity and biological realism, informing best practices for benchmarking.

### Gaussian–Cox–Inspired Simulator
I developed a biologically grounded simulator that integrates Negative Binomial marginals with a Gaussian copula to encode gene–gene dependencies and sample-level structure. Pathway diffusion kernels (MSigDB) inform gene-level covariance, while optional AR(1) kernels capture progressive sample relationships. The simulator preserves both univariate and multivariate properties, enabling realistic in silico experiments.

### Deconvolution and Integrative Modeling
Next, I aim to integrate simulation with cell-type deconvolution and multi-omics analysis to improve interpretability of complex tissue signals in cancer and rare diseases. This includes using simulated datasets to stress-test and refine algorithms (e.g., BayesPrism, MuSiC, CIBERSORTx) under challenging regimes.

**Download:** [Research Statement (PDF)](/assets/docs/research_statement_placeholder.pdf)
