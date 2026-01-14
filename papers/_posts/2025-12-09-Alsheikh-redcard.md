---
layout  : paper
title   : RedCarD&#58; A Quantum Assisted Algorithm for Fixed-Depth Unitary Synthesis via Cartan Decomposition
authors : Alsheikh O, K&#0246;kc&#0252; E, Bakalov BN, Kemper AF
year    : 2025
ref     : "Alsheikh et al., arXiv:2512.06070" 
journal : "arXiv:2512.06070"
arxiv   : "2512.06070"
image   : /images/papers/redcard.png
ncsu    : True
funding : "2325080: STAQII"
---

# Abstract
A critical step in developing circuits for quantum simulation is to synthesize a desired unitary operator using the circuit building blocks.  Studying unitaries and their generators from the Lie algebraic perspective has given rise to several algorithms for synthesis based on a Cartan decomposition of the dynamical Lie algebra.  For unitaries of the form $e^{-itH}$, such as time-independent Hamiltonian simulation, the resulting circuits have depth that does not depend on simulation time $t$.  However, finding such circuits has a large classical overhead in the cost function evaluation and the high dimensional optimization problem.  In this work, by further partitioning the dynamical Lie algebra, we break down the optimization problem into smaller independent subproblems.  Moreover, the resulting algebraic structure allows us to easily shift the evaluation of the cost function to the quantum computer, further cutting the classical overhead of the algorithm.  As an application of the new hybrid algorithm, we synthesize the time evolution unitary for the 4-site transverse field Ising model on several IBM devices and Quantinuum's H1-1 quantum computer.
