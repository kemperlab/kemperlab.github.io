---
layout  : paper
title   : Geometric Quantum Machine Learning with Horizontal Quantum Gates
authors : Wiersema R, Kemper AF, Bakalov B, Killoran N
year    : 2025
ref     : "R Wiersema et al., arXiv:2406.04418"
journal : Accepted for publication in PRR
arxiv   : "2406.04418"
image   : /images/papers/horizontal_gates.png
ncsu    : True
funding : "2325080: STAQ II"
---

# Abstract
In the current framework of Geometric Quantum Machine Learning, the canonical method for constructing a variational ansatz that respects the symmetry of some group action is by forcing the circuit to be equivariant, i.e., to commute with the action of the group. This can, however, be an overzealous constraint that greatly limits the expressivity of the circuit, especially in the case of continuous symmetries.
    We propose an alternative paradigm for the symmetry-informed construction of variational quantum circuits, based on homogeneous spaces, relaxing the overly stringent requirement of equivariance.
    We achieve this by introducing horizontal quantum gates, which only transform the state with respect to the directions orthogonal to those of the symmetry. 
    We show that horizontal quantum gates are much more expressive than equivariant gates, and thus can solve problems that equivariant circuits cannot. For instance, a circuit comprised of horizontal gates can find the ground state of an SU(2)-symmetric model where the ground state spin sector is unknown--a task where equivariant circuits fall short.
    Moreover, for a particular subclass of horizontal gates based on symmetric spaces, we can obtain efficient circuit decompositions for our gates through the KAK theorem. Finally, we highlight a particular class of horizontal quantum gates that behave similarly to general SU(4) gates, while achieving a quadratic reduction in the number of parameters for a generic problem. 
