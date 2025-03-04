---
layout: page
title: Presentations
subtitle: Conference talks and poster presentations
---

Below you can find a full list of my academic presentations (organised by date)

---

**PRESENTATIONS**

**The Effect of Binning Transmission Spectra for Exoplanet Atmospheric Retrievals**

**Conference:** _Presented at EPSC2024, Berlin (September, 2024)_

**DOI:** [https://doi.org/10.5194/epsc2024-592](https://doi.org/10.5194/epsc2024-592)

**Abstract:** With the James Webb Space Telescope (JWST) offering higher resolution data in space-based transmission spectroscopy, understanding the capabilities of our current atmospheric retrieval pipelines is essential. These new data cover wider wavelength ranges and at much higher spectral resolution than previous instruments have been able to offer. Therefore, it is often appealing to bin spectra to fewer points, better constrained in their transit depth, before using them as inputs for atmospheric retrievals. However, little quantitative analysis of the trade-off between spectral resolution and signal-to-noise ratio has been conducted thus far.

_(For the full abstract, please follow the DOI link)_

---

**POSTERS**

**The Effect of Binning Transmission Spectra for Exoplanet Atmospheric Retrievals**

**Conference:** _Presented at Exoplanets V, Leiden (June, 2024)_

**Abstract:** With transmission spectroscopy data of higher resolution now being offered by spaced-based observatories such as the James Webb Space Telescope (JWST), it is imperative that we understand the capabilities of our retrieval pipelines. Towards this aim, we present a sensitivity study aiming to quantify the deviation of retrieved parameters from their true values as a function of spectral resolution and observed photometric error. We use simulated WASP-39b transmission spectra across the wavelength range of the NIRSpec PRISM instrument and bin the data to various regimes. We find that caution is warranted when binning to resolutions below R=100 and that the cloud deck in the spectrum heavily influences the resolution to which spectra can be binned for effective retrievals. Further to this, shifts in the wavelength binning grid can introduce significant offsets in the retrieved parameters so the method used to bin spectra is a key consideration.

**Approximate Bayesian Computation (ABC) in Retrievals of Exoplanet Atmospheres**

**Conference:** _Presented at Planets ESLAB, Leiden (March 2023)_

**Abstract:** While Approximate Bayesian Computation (ABC) and other likelihood free (LF) methods for Bayesian inference have been adopted in many areas of scientific research including cosmology, they have seen limited application in exoplanetary science. Cosmologists have been dealing with the problem of intractable likelihoods for a number of years and have implemented these techniques in order to bypass the need to define a likelihood function. With the launch and first observations of the James Webb Space Telescope (JWST), there is a strong expectation that assumptions in the likelihood could bias results of atmospheric retrievals on exoplanet transmission spectra so the need for LF methods is evident now more than ever. Here, we implement ABC with the atmospheric retrieval code TauREx3 (using the PyMC library) with the aims of revealing and mitigating the effects of non-gaussianity in spectral data sets. To this end we will study effects due to non-gaussian noise in simulated data sets of hot Jupiter spectra. This will allow us to identify any biases on specific parameters and we will then go on to perform a reanalysis of Hubble and JWST early release science observations to identify any non-gaussian bias in retrievals performed with these data.
