---
layout: page
title: Forced Oscillation Localization 
description: A Complex-LASSO Approach for Localizing Forced Oscillations in Power Systems
img: 
importance: 2
category: work
---

We study the problem of localizing multiple sources of forced oscillations (FOs) and estimating their characteristics, such as frequency, phase, and amplitude, using noisy PMU measurements. For each source location, we model the input oscillation as a sum of unknown sinusoidal terms. This allows us to obtain a linear relationship between measurements and the inputs at the unknown sinusoids' frequencies in the frequency domain. We determine these frequencies by thresholding the empirical spectrum of the noisy measurements. Assuming sparsity in the number of FOs' locations and the number of sinusoids at each location, we cast the location recovery problem as an ℓ1-regularized least squares problem in the complex domain -- i.e., complex-LASSO (linear shrinkage and selection operator). We numerically solve this optimization problem using the complex-valued coordinate descent method, and show its efficiency on the IEEE 68-bus, 16 machine and WECC 179-bus, 29-machine systems.

**Aknowledgments:**
This material is based upon work supported by the National Science
Foundation under Grant No. OAC-1934766 and PSERC project S-87

<a href="https://ieeexplore.ieee.org/document/9916993">Link to the paper</a>