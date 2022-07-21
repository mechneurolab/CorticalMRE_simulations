# Cortical MRE simulations
Simulated displacement data and accompanying inversions to test the accuracy of recovering mechanical properties of cortical regions with high-resolution MRE. Data accompanying Hiscox (2022) [1].

Realistic simulations were created from geometry of older adult brains with a range of stiffness (μ=2|G*|2/(G'+|G*|)) and damping ratio (ξ=G"/2G') assigned for several cortical regions defined by Freesurfer parcellations. Displacement data were created with finite-element simulation platform [2] using subject-specific boundary conditions from MRE data acquired at 1.25 mm isotropic resolution [3]. Inversions were performed with the nonlinear inversion algorithm [4] and soft prior regularization [5].

This research was supported by grants from the National Institutes of Health R01-AG058853, R01- EB027577, and U01-NS112120.

# References:
[1] Hiscox LV, McGarry MDJ, Johnson CL. “Evaluation of Cerebral Cortex Viscoelastic Property Estimation with Nonlinear Inversion Magnetic Resonance Elastography,” Physics in Medicine & Biology, 2022; 67:095002. https://iopscience.iop.org/article/10.1088/1361-6560/ac5fde

[2] McGarry MDJ, Van Houten EEw, Guertler CA, Okamoto RJ, Smith DR, Sowinski D, Johnson CL, Bayly PV, Weaver JB, Paulsen KD, “A Heterogeneous, Time Harmonic, Nearly Incompressible Transverse Isotropic Finite Element Brain Simulation Platform for MR Elastography,” Physics in Medicine & Biology, 2021; 66(5):055029. https://iopscience.iop.org/article/10.1088/1361-6560/ab9a84

[3] Delgorio PL, Hiscox LV, Daugherty AM, Sanjana F, Pohlig RT, Ellison JM, Martens CR, Schwarb H, McGarry MDJ, Johnson CL, “Effect of Aging on the Viscoelastic Properties of Hippocampal Subfields Assessed with High-Resolution MR Elastography,” Cerebral Cortex, 2021; 31(6):2799–2811. https://academic.oup.com/cercor/article/31/6/2799/6102671

[4] McGarry MDJ, Van Houten EEW, Johnson CL, Georgiadis JG, Sutton BP, Weaver JB, Paulsen KD, “Multiresolution MR Elastography Using Nonlinear Inversion,” Medical Physics, 2012; 39(10):6388-6396. https://aapm.onlinelibrary.wiley.com/doi/abs/10.1118/1.4754649

[5] McGarry MDJ, Johnson CL, Sutton BP, Van Houten EEW, Georgiadis JG, Weaver JB, Paulsen KD, “Including Spatial Information in Nonlinear Inversion MR Elastography Using Soft Prior Regularization,” IEEE Transactions on Medical Imaging, 2013; 32(10):1901-1909. https://ieeexplore.ieee.org/document/6542013
