---
layout  : paper
title   : A quantum computing approach to efficiently simulating correlated materials using impurity models and dynamical mean field theory
authors : Hogan N, K&#0246;kc&#0252; E, Steckmann T, Doak LP, Mejuto-Zaera C, Camps D, Van Beeumen R, de Jong WA, Kemper AF
year    : 2026
ref     : "N. Hogan et al., npj Comput. Mater. (2026)"
journal : "npj Computational Materials (2026)"
arxiv   : 2508.05738
image   : /images/papers/hogan-ec-qc-dmft.png
ncsu    : True
doi     : 10.1038/s41524-026-02289-2
funding : "NSF DMR-1752713"
---

# Abstract
The accurate theoretical description of materials with strongly correlated electrons is a formidable challenge in condensed matter physics and computational chemistry. Dynamical Mean Field Theory (DMFT) is a successful approach that predicts behaviors of such systems by incorporating some of the correlated behavior using an impurity model, but it is limited by the need to calculate the impurity Green’s function. This work proposes a framework for DMFT calculations on quantum computers, focusing on near-term applications. It leverages the structure of the impurity problem, combining a low-rank Gaussian subspace representation of the ground state and a compressed, short-depth quantum circuit that joins state preparation with time evolution to compute Green’s functions. We demonstrate the convergence of the DMFT algorithm using the Gaussian subspace in a noise-free setting, and show the hardware viability of circuit compression by extracting the impurity Green’s function on IBM quantum processors for a single impurity coupled to three bath orbitals (8 qubits, 1 ancilla). We discuss potential paths toward realizing this quantum computing use case in materials science.
