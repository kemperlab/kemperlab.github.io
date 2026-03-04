---
layout  : paper
title   : JIMWLK on a quantum computer
authors : Agrawal AA, Budd E, Kemper AF, Skokov VV, Tarasov A, Tiwari S
year    : 2026
ref     : "Agrawal et al., arXiv:2602.02516"
journal : "arXiv:2602.02516"
arxiv   : 2602.02516
image   : /images/papers/agrawal-jimwlk.png
ncsu    : True
funding : DE-SC0025430, DARPA
---

# Abstract
We propose a method for solving the Jalilian-Marian–Iancu–McLerran–Weigert–Leonidov–Kovner (JIMWLK) evolution equation on quantum computers. Our approach exploits the reformulation of the JIMWLK equation as a Lindblad master equation governing the rapidity evolution of the hadronic density matrix, as established in prior work. To render the problem tractable for quantum simulation, we introduce several  approximations: the two-dimensional transverse plane is reduced to a one-dimensional radial lattice by assuming azimuthal symmetry of the jump operators; the gauge group is restricted to SU(2); and the infinite Wilson lines of the JIMWLK equation are replaced by finite Wilson links along the light-cone direction. The resulting bosonic Hilbert space is truncated using the electric field basis familiar from Hamiltonian lattice gauge theory, with states restricted to angular momenta j <= jmax. We derive the matrix elements of the JIMWLK Lindblad jump operators in this basis. As a benchmark, we demonstrate rapid convergence of the fundamental dipole expectation value with jmax for both pure and mixed Gaussian initial density matrices. For the simplest truncation, jmax = 1/2, we implement the Lindblad evolution
using a quantum simulation algorithm verified with the Qiskit statevector simulator by decomposing the non-unitary evolution operator into a linear combination of unitaries. This work establishes a concrete pathway toward quantum simulation of high-energy QCD evolution equations, with direct relevance to the physics program of the Electron-Ion Collider.
