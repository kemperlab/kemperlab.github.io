---
layout  : paper
title   : Denoising of Imaginary Time Response Functions with Hankel projections
authors : Yu Y, Kemper AF, Yang C, Gull E
year    : 2024
ref     : "Y. Yang et al., arXiv:2403.12349"
journal : arXiv:2403.12349
arxiv   : "2403.12349"
image   : /images/papers/imag_gf_positivity.png
ncsu    : True
github  : https://github.com/CQMP/HankelProjection
---

# Abstract
Imaginary-time response functions of finite-temperature quantum systems are often obtained with methods that exhibit stochastic or systematic errors. Reducing these errors comes at a large computational cost -- in quantum Monte Carlo simulations, the reduction of noise by a factor of two incurs a simulation cost of a factor of four. In this paper, we relate certain imaginary-time response functions to an inner product on the space of linear operators on Fock space. We then show that data with noise typically does not respect the positive definiteness of its associated Gramian. The Gramian has the structure of a Hankel matrix. As a method for denoising noisy data, we introduce an alternating projection algorithm that finds the closest positive definite Hankel matrix consistent with noisy data. We test our methodology at the example of fermion Green's functions for continuous-time quantum Monte Carlo data and show remarkable improvements of the error, reducing noise by a factor of up to 20 in practical examples. We argue that Hankel projections should be used whenever finite-temperature imaginary-time data of response functions with errors is analyzed, be it in the context of quantum Monte Carlo, quantum computing, or in approximate semianalytic methodologies. 
