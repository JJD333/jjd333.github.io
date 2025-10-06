---
layout: page
title: Publications
subtitle: My published research
---

Below you can find a full list of my research publications (organised by date)

---

[**Investigating the Influence of Asymmetric Errors on Retrievals of Exoplanet Transmission Spectra**](https://arxiv.org/abs/2507.19223)

_Submitted to Royal Astronomical Society Techniques and Instruments_

**Authors:** <u>Jack J. Davey</u>, Kai Hou Yip, Quentin Changeat and Ingo P. Waldmann

**Affiliation:** University College London, University of Groningen

**Abstract:** In studies of exoplanet atmospheres using transmission spectroscopy, Bayesian retrievals are the most popular form of analysis. In these procedures it is common to adopt a Gaussian likelihood. However, this implicitly assumes that the upper and lower error bars on the spectral points are equal. With recent observations from the James Webb Space Telescope (JWST) offering higher quality of data, it is worth revisiting this assumption to understand the impact that an asymmetry between the error bars may have on retrieved parameters. In this study, we challenge the approximation by comparing retrievals using a symmetric, Gaussian likelihood, and an asymmetric, split normal likelihood. We find that the influence of this assumption is minimal at the scales of asymmetry observed in JWST observations of WASP-39 b (with a maximum asymmetry of 77%) but we show that it would become critical with greater levels of asymmetry (e.g. an average asymmetry of 80%). Furthermore, we stress the importance of the shape of the asymmetric distribution and the difficulty in fitting this distribution from three summary statistics (the median and an upper and lower bound on the transit depth). An asymmetric likelihood sampler will incorrectly predict parameters if the shape of the likelihood does not match that of the underlying noise distribution even when the levels of asymmetry are equal in both. Overall, we find that it is safe to use the Gaussian likelihood assumption for current datasets but it is worth considering the potential bias if greater asymmetries are observed.

---

[**The effect of spectroscopic binning on atmospheric retrievals**](https://academic.oup.com/mnras/article/536/3/2618/7922859#498928734)

_Published in Monthly Notices of the Royal Astronomical Society_

_Davey J. J., Yip K. H., Al-Refaie A. F., Waldmann I. P., 2024, MNRAS, 536, 2618-2644_

**Authors:** <u>Jack J. Davey</u>, Kai Hou Yip, Ahmed F. Al-Refaie and Ingo P. Waldmann

**Affiliation:** University College London

**Abstract:** With the JWST offering higher resolution data in space-based transmission spectroscopy, understanding the capabilities of our current atmospheric retrieval pipelines is essential. These new data cover wider wavelength ranges and at much higher spectral resolution than previous instruments have been able to offer. Therefore, it is often appealing to bin spectra to fewer points, better constrained in their transit depth, before using them as inputs for atmospheric retrievals. As such, we produce a simulation replicating the observations of WASP-39b by the Near Infrared Spectrograph (NIRSpec) instrument on board JWST using the PRISM dispersion element. Then, we assess the accuracy and consistency of retrievals while varying both the resolution and the average photometric error of this simulated spectrum. We repeat this analysis on three different simulation setups where each includes an opaque cloud layer at a different height in the atmosphere. In agreement with previous studies, we find that a much greater resolution is needed in the case of a high cloud deck since features are already heavily muted by the presence of the clouds. In the other two cases, there are large 'safe zones' in the parameter space where accurate estimations are made. If these maps can be generalized, they could be used to inform future observations on how long to observe a given target in order to achieve the most accurate retrieval results. We also find that the resolution required to fully resolve the degeneracies between the parameters contributing to the spectra is much greater than that needed to constrain the marginalized posterior distributions for each parameter individually.
