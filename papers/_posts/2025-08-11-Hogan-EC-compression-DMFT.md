---
layout  : paper
title   : A quantum computing approach to efficiently simulating correlated materials using impurity models and dynamical mean field theory
authors : Hogan N, K&#0246;kc&#0252; E, Steckmann T, Doak LP, Mejuto-Zaera C, Camps D, Van Beeumen R, de Jong WA, Kemper AF
year    : 2025
ref     : "N. Hogan et al., arXiv:2508.05738"
journal : "arXiv:2508.05738"
arxiv   : 2508.05738
image   : /images/papers/hogan-ec-qc-dmft.png
ncsu    : True
funding : "NSF DMR-1752713"
---

# Abstract
The accurate theoretical description of materials with strongly correlated electrons is a formidable challenge, at the forefront of condensed matter physics and computational chemistry alike, and it is one of the targets for quantum computing.  Dynamical Mean Field Theory (DMFT) is a successful approach that predicts behaviors of such systems by incorporating some correlated behavior, but it is limited by the need to calculate the Green’s function for the impurity model. This work proposes a framework for DMFT calculations on quantum computers, focusing on near-term applications.  It leverages the structure of the impurity problem, combining a low-rank Gaussian subspace representation of the ground state and a compressed, short-depth quantum circuit that joins the Gaussian state preparation with the time evolution to compute the necessary Green's functions.  We demonstrate the convergence of the DMFT algorithm using the Gaussian subspace in a noise-free setting, and show the hardware viability of the circuit compression by extracting the impurity Green's function on IBM quantum processors for a single impurity coupled to three bath orbitals (8 physical qubits and 1 ancilla).  We discuss the potential paths forward towards realizing this use case of quantum computing in materials science.
