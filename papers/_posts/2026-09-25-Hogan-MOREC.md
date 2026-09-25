---
layout  : paper
title   : Compact representation of Strongly Correlated Green's Functions&#58; the MOR+EC way to explore phase space
authors : Hogan N, Kemper AF, Mejuto-Zaera C
year    : 2026
ref     : "N. Hogan et al., arXiv:2609.28647"
journal : "arXiv:2609.28647"
arxiv   : 2609.28647
image   : /images/papers/hogan-morec.png
ncsu    : True
funding : "DE-SC0025430"
---

# Abstract
Repeated evaluation of the single-particle Green's function (GF) across parameter space is a recurring bottleneck in many-body methods, limiting the resolution at which phase boundaries may be probed and the frequency resolution of computed spectra. We introduce MOR+EC, a framework that constructs reusable reduced-order models for computing single-particle Green's function by combining eigenvector continuation (EC) for parameter space exploration and model order reduction (MOR) for extrapolation in frequency space. Contrary to conventional parameterized MOR, we construct these reduced-order models with a parameter-independent resolvent, further reducing the number of required full-space evaluations. Benchmarking against exact diagonalization as the impurity solver for our example case of DMFT calculations for single- and two-band models, MOR+EC reproduces the DMFT-converged impurity GF to an average relative error of 1E-4, with a median wall-time speedup of 16-91x. This accuracy and efficiency together resolve a fine-grained scan of the impurity occupation as doping is tuned and produce a high-resolution phase diagram of an orbital-selective Mott transition. The reduced-order model aslo reproduces real- and imaginary-frequency spectra at no additional cost in full-space evaluations. This framework applies broadly to GF-based methods requiring repeated parametric evaluation and high resolution of the frequency axis.
