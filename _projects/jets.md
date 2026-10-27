---
layout: page
title: Relativistic Jets from AGNs
description: What properties of relativistic jets can we infer through broadband SED modeling?
img: assets/img/m87_map.png
importance: 3
category: work
related_publications: true
---

<div class="row research-intro">
    <div class="col-md-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/m87_map.png" title="M87 jet" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-md-8 mt-3 mt-md-0">
        <p>Relativistic jets are collimated outflows of plasma launched from the vicinity of accreting compact objects. These jets can extend over distances of Mpc and are among the most powerful persistent phenomena in the Universe. In active galactic nuclei (AGN), jets are responsible for a significant fraction of the observed emission across the entire electromagnetic spectrum, from radio waves to gamma rays.</p>
    </div>
</div>

<div class="research-intro">
<p>Understanding the composition, structure, and emission mechanisms of these jets is fundamental to unraveling the physics of accretion and outflow in extreme environments. The broadband spectral energy distribution (SED) of relativistic jets encodes information about the particle populations, magnetic field strength, and geometry of the emitting regions. Through detailed modeling of the observed SEDs, we can constrain key physical parameters such as the jet power, bulk Lorentz factor, and the properties of the accelerated particle distributions. I have worked on understanding both the radiative processes in jets and the fundamental question of how jets are loaded with matter in the first place.</p>
</div>

<h2 class="research-papers-heading">Papers</h2>

<section class="paper-block">
  <p class="paper-meta">Submitted · arXiv:2610.26434 · 2026</p>
  <h3 class="paper-title">The accretion flow and jet of M87 across spatial scales</h3>
  <p>In {% cite Gutierrez_etal2026arXiv261026434G %}, together with my master's student Tomás Mazzei and Santiago del Palacio, we modeled the broadband emission of M87 across spatial scales. The Event Horizon Telescope multi-wavelength campaigns showed that a single emission zone cannot reproduce the source, so we combined a thermal radiatively inefficient accretion flow (RIAF) with winds and a new multizone jet model that starts magnetically dominated, with continuous injection, advection, and cooling of nonthermal electrons and synchrotron self-absorption along the jet.</p>
  <p>Instead of fitting the total jet emission, we integrated it only up to the height that matches the effective aperture of each instrument, from 7.3 to 3.5×10<sup>5</sup> gravitational radii, and compared it with the flux measured at that angular scale in the 2017 EHT multi-wavelength campaign. We also computed synthetic 43 GHz maps and spectral-index maps between 22, 43 and 86 GHz.</p>
  <p>We found that the compact 230 GHz emission seen by the EHT is produced by the accretion flow rather than the jet, with an accretion rate at the horizon of about 10<sup>-5</sup> of the Eddington rate, consistent with EHT polarimetry. The jet dominates the lower-frequency radio, optical/UV, and X-ray emission, but cannot account for the observed γ-rays. The two jets carry roughly a quarter of the accretion power, about 10<sup>43</sup> erg s<sup>-1</sup> each.</p>
  <p>The model codes, data, and scripts that reproduce every figure and number of the paper are available in a <a href="https://github.com/eduardomgutierrez/m87-riaf-jet-repro" target="_blank" rel="noopener noreferrer">public reproduction package</a>.</p>
  <div class="paper-figure">
    {% include figure.liquid path="assets/img/jet_sed.jpg" class="img-fluid rounded z-depth-1" %}
    <p class="caption">Spectral energy distribution modeling of the M87 jet.</p>
  </div>
</section>

<section class="paper-block">
  <p class="paper-meta">Universe 6, 99 · 2020</p>
  <h3 class="paper-title">The origin of matter at the base of relativistic jets</h3>
  <p>In {% cite RomeroGutierrez2020Univ....6...99R %}, I investigated the origin of matter at the base of relativistic jets in AGN. We analyzed various mechanisms through which jets can be loaded with leptons and baryons, including processes occurring in the hot accretion flow surrounding the black hole. Understanding jet composition is crucial because it determines the jet's dynamics, stability, and ultimately its radiative properties.</p>
</section>
