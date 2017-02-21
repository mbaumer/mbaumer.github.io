---
layout: page
title: Research
permalink: /research/
order : 2
---

# Three-point correlation functions in DES

Traditional analyses of galaxy clustering analyze pairs of galaxies--you find that more of them than you'd expect are close together, because of gravity. This measurement is a popular and powerful tool for constraining cosmology, but as an angularly-symmetric measurement, much of the signal from the filamentary structure of the cosmic web is not captured. By measuring the scale and configuration dependence of galaxy triangles rather than pairs, the computational challenge increases significantly (for N galaxies, there are N^2 pairs, but N^3 triangles to consider!), but but the payoff is a direct measurement of the cosmic web which sheds light on how galaxies form in dark matter halos. Three-point functions also probe cosmology with different covariances, which allow degeneracies that occur at the two-point level to be ameliorated. I am currently working on a measurement of the galaxy three-point correlation function in DES Year 1 data.

# Camera Systematics

If the pixels in your iPhone weren't aligned in a perfect grid, you'd expect the picture to be blurry. In survey astronomy, even the slightest distortion of the pixel grid could have a big effect on our observations. A few years ago, [we noticed](https://arxiv.org/abs/1504.06088) that the pixels in a prototype CCD for the Large Synoptic Survey Telescope (LSST) were stealing area from their neighbors--the pixel grid wasn't perfectly aligned! We've been studying how these (small) imperfections might affect our measurements of brightnesses, locations, and shapes of stars and galaxies, and have a paper currently under internal review with both LSST and the DES collaboration (which also is dealing with these pixel grid distortions).

# Lensed Quasar Hunting
With SLAC Staff Scientist [Dr. Phil Marshall](http://www.slac.stanford.edu/~pjm/Site/Welcome.html), and Stanford undergraduate [Jenny Kim](https://github.com/jennykim1016), I work on developing machine learning methods to look for needles (lensed quasars) in haystacks (massive galaxy catalogs). On the ML side, we're training Random Forests and using [Extreme Deconvolution](https://arxiv.org/abs/0905.2979) (basically a Gaussian Mixture Model that's aware of observational uncertainties). Right now, we are working on creating realistic training data for these algorithms using the [OM10](https://github.com/drphilmarshall/OM10) catalog, colorized using template SEDs. 
