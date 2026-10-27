---
layout: page
title: Binary neutron star mergers
description: What happens when two neutron stars merge? How do the magnetic fields amplify and evolve? What are the main multimessenger signals from these events?
img: assets/img/bns.png
importance: 2
category: work
related_publications: true
---

<div class="row research-intro">
    <div class="col-md-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/bns.png" title="BNS merger schematic" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-md-8 mt-3 mt-md-0">
        <p>Binary neutron star (BNS) mergers are among the most energetic events in the universe, producing gravitational waves detectable by LIGO/Virgo, short gamma-ray bursts, kilonovae powered by r-process nucleosynthesis, and a variety of electromagnetic counterparts across the spectrum. The landmark detection of GW170817 and its electromagnetic counterparts opened the era of multimessenger astronomy with neutron stars.</p>
        <p>Understanding the physics of these mergers, from the inspiral dynamics to the post-merger remnant and the launching of relativistic jets, requires sophisticated numerical simulations that combine general relativity, magnetohydrodynamics, and nuclear physics.</p>
    </div>
</div>

<h2 class="research-papers-heading">Papers</h2>

<section class="paper-block">
  <p class="paper-meta">Phys. Rev. Lett. (accepted) · 2026</p>
  <h3 class="paper-title">Turbulent dynamo action in binary neutron star mergers</h3>
  <p>In {% cite Gutierrez_etal2026arXiv260120953G %}, we studied how weak, pulsar-like magnetic fields are amplified during the merger. When the two stars touch, the shear layer between them becomes unstable to the Kelvin-Helmholtz instability, and the vortices it produces drive a fast turbulent small-scale dynamo that fills the remnant with strong, tangled magnetic fields.</p>
  <div class="paper-figure">
    {% include figure.liquid loading="eager" path="assets/img/dynamo_fig1.jpg" class="img-fluid rounded z-depth-1" %}
    <p class="caption">(a) Temperature in the orbital plane at merger, with a zoom into the shear layer between the stars and its velocity field. (b) Magnetic field strength at t ≃ 0.25 ms, as Kelvin-Helmholtz vortices develop along the shear layer. (c) The turbulent remnant at t ≃ 1.5 ms, with successive zoom-ins. (d) 3D volume rendering of the magnetic field strength.</p>
  </div>
  <p>Resolving this dynamo requires extremely fine grids. We ran a series of simulations with grid spacings down to a few meters, and found that the magnetic energy grows by about five orders of magnitude within roughly 2 ms of merger at the highest resolutions, where large-scale coherent structures also begin to emerge. This suggests that strong and ordered magnetic fields may be present shortly after merger, with consequences for the electromagnetic and gravitational-wave signals of the remnant.</p>
  <div class="row justify-content-center paper-figure">
    <div class="col-md-5">
      {% include figure.liquid path="assets/img/dynamo_amplification.png" class="img-fluid rounded z-depth-1" %}
      <p class="caption">Growth of the magnetic field strength (top) and magnetic energy (bottom) for grid spacings from 92 m down to 2.9 m.</p>
    </div>
  </div>
</section>

<section class="paper-block">
  <p class="paper-meta">Phys. Rev. D 114, 063049 · 2026</p>
  <h3 class="paper-title">Magnetic field configurations I: post-merger remnant and disk</h3>
  <div class="row">
    <div class="col-md-8">
      <p>In {% cite Gutierrez_etal2025arXiv250618995G %}, we performed a systematic study of how different initial magnetic field configurations evolve in the post-merger remnant and the surrounding accretion disk. Using high-resolution GRMHD simulations with various initial field geometries, we found that the field is amplified soon after merger by the Kelvin-Helmholtz instability, and identified how the magnetic field topology affects the disk structure and outflows.</p>
    </div>
    <div class="col-md-4 paper-figure mt-md-0">
      {% include figure.liquid path="assets/img/bns_bfield.jpg" class="img-fluid rounded z-depth-1" %}
      <p class="caption">Toroidal magnetic field structure in a BNS post-merger remnant.</p>
    </div>
  </div>
</section>

<section class="paper-block">
  <p class="paper-meta">Phys. Rev. D 114, 063050 · 2026</p>
  <h3 class="paper-title">Magnetic field configurations II: inspiral, merger and ejecta</h3>
  <p>In the companion paper {% cite Cook_etal2025arXiv250819342C %}, led by William Cook, we followed the same set of magnetic field configurations through the inspiral and merger. We studied how the initial field shapes the gravitational-wave signal, the global amplification of the field, and the properties of the ejected material, and found that the choice of initial field can noticeably affect the phase differences between the dominant and subdominant gravitational-wave modes.</p>
</section>

<section class="paper-block">
  <p class="paper-meta">Phys. Rev. D 111, 063031 · 2025</p>
  <h3 class="paper-title">Cocoon shock breakout emission</h3>
  <p>In {% cite Gutierrez_etal2025PhRvD.111f3031G %}, I investigated a novel electromagnetic precursor to the main kilonova emission: the cocoon shock breakout signal. I developed a theoretical framework to predict the properties of this early-time emission, which could serve as an important target for follow-up observations of future BNS merger events.</p>
  <div class="paper-figure">
    {% include figure.liquid path="assets/img/cocoon.png" class="img-fluid rounded z-depth-1" %}
    <p class="caption">Schematic diagram of the cocoon shock breakout emission from a BNS merger.</p>
  </div>
</section>

<section class="paper-block">
  <p class="paper-meta">Numerical methods</p>
  <h3 class="paper-title">Code development</h3>
  <p>I also contribute to the development of the next generation of numerical relativity codes used for these simulations:</p>
  <ul>
    <li>Binary neutron star mergers with neutrino transport in GR-Athena++ {% cite 2026PhRvD.114d4062D %}.</li>
    <li>A comparison of cell- and vertex-centered adaptive meshes for compact binary simulations {% cite 2025PhRvD.112j3006D %}.</li>
    <li>Finite-solid-angle Boltzmann radiation transport on dynamical spacetimes in AthenaK {% cite 2026arXiv260822020Z %}.</li>
  </ul>
</section>
