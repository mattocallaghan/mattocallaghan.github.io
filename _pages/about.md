---
permalink: /
title: "<ins>Personal Homepage</ins>"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# About Me

Hello! I'm Matthew, a fourth year PhD student at the University of Cambridge, where I am working with Gerry Gilmore and Kaisey Mandel at the Institute of Astronomy. 

My research focuses on the dusty interstellar medium at high Galactic latitudes for understanding dust geometry within the context of CMB polarization surveys. I also work on developing robust simulation-based inference methods.




## Current Research

### Astronomy
##### Data driven reddenings using probabilistic machine learning:
I am using Gaia distances and photometric surveys to develop a neural conditional density estimator of the photometric colors of negligible-extinction stars conditional on the Galactic cylindrical coordinates and absolute magntiude. This approach learns a prior distribution of intrinsic photometric colours as a probabilistic surfance instead of the regularly adopted functional fit of the colour-colour relations. This aids towards percise and accurate extinction posteriors at high Galactic latitudes  when I marginalize over the prior. Future work will build on these priors to generate small-scale dust maps in regions of the Galaxy where dust is diffuse. 
##### SBI with BPRP Spectra
SBI methods aims to embed high dimensional data into a lower dimensional sufficient statistic surface. I am looking at using the methods developed in my theoretical SBI work to aim for robust and reliable stellar parameter posteriors using Gaia BPRP Spectra.
### Robust Simulation-Based Inference: Bridging the Gap Between Simulation and Observation
Recent advances in neural density estimation have enabled powerful simulation-based inference (SBI) methods that can flexibly approximate Bayesian inference for intractable stochastic models. Although these methods have demonstrated accurate posterior estimation when the simulator accurately represents the underlying data generative process (DGP), they have been shown to perform poorly in the presence of model misspecification. My work focuses on bridging the gap between simulation and observation in likelihood-based methods, assuming that the simulator outputs can be embedded into a lower-dimensional summary statistic surface.

### Ideal Neural Conditional Estimator Architectures for Hamiltonian Monte Carlo
My work involves constructing normalizing flow architectures that ensure geometric ergodicity of the No U-Turn Sampler (NUTS) Kernel. This is essential for succesfully including a normalizing flow as a prior or likelihood function in a differentiable hierarchical model which uses the NUTS algorithm.

### Earth Atmospheric Physics 
I also work at the National Obvervatory of Athens where I am building a probabilistic model to understand the optical properties of irregular shaped particles in our atmosphere. This work will significantly speed up the calculation of complex properties of irregularly shaped particles.

## Past Research

### Astronomy
I have explored the information available at high Galactic latitudes for inferring extinction, contributing to a better understanding of the interstellar medium and its properties. [My first paper](https://academic.oup.com/mnras/article/535/3/2149/7831690) showed that degeneracies between extinction and other stellar parameters are particularly difficult to overcome in these regions and will have a particular impact on CMB experiments. We also showed that using models of stellar evolution for a zero-extinction sample of stars contains systematics which are very problematic for inferring low variation in extinction. Moreover, inferring extinction in these regions is prior dominated and accounting for the systematics in correctly matching priors introduces a systematic in the extinction calculations which is difficult to overcome. We are solving this problem by working entirely from a data-driven perspective.

### Symplectic Geometry
In 2020-2021 I completed the Part III masters in Mathematics at the University of Cambridge. I was awarded a distinction for my paper [Symplectic Reduciton and Poisson Geometry](http://philsci-archive.pitt.edu/19515/1/Symplectic_Reduction_and_Poisson_Geometry_of_Three_Dimensional_Lie_Groups%20(14).pdf), which provided a background on the topic and proceeded to look at the coadjoint orbits of the Bianchi Lie group and derived the Hamiltonian dynamics for the corresponding cosmologies.

Feel free to reach out if you are interested in my work or have any questions!
