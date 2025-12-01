---
layout: page
title: Nonthermal processes in hot accretion flows
description: What role do nonthermal particles play in hot accretion flows?
img: assets/img/riaf_cartoon.png
importance: 1
category: work
related_publications: true
---

<div class="row">
    <div class="col-md-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/riaf_cartoon.png" title="RIAF schematic" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-md-6 mt-3 mt-md-0">
        <p>Hot accretion flows, also known as radiatively inefficient accretion flows (RIAFs), are optically thin and geometrically thick inflows onto compact objects, characterized by low densities and very low radiative efficiencies. In these systems, most of the gravitational energy released by accretion is not radiated away, but rather advected into the compact object or carried off by outflows and jets. RIAFs are widely believed to power low-luminosity active galactic nuclei (LLAGN) such as Sgr A* and M87*, as well as the hard and quiescent states of X-ray binaries.</p>

    </div>
</div>

<p>Because of their low densities and high temperatures, Coulomb collisions between particles are inefficient at establishing thermal equilibrium. As a result, the electron and ion populations can have distinct temperatures and may develop a nonthermal component through various plasma processes, such as magnetic reconnection, shocks, and turbulence. The presence of a nonthermal populations significantly alters the emitted spectrum, affecting both the shape and variability of the radiation across the electromagnetic spectrum. These populations of nonthermal particles may also produce copious amounts of neutrinos, making RIAF promising multimessenger sources. I study how particle acceleration, cooling, and transport modify the radiation from the innermost regions around black holes, and what observational signatures can these processes reveal.</p>

<p>
In {% cite Gutierrez_etal2020ApJ...891L..36G %}, I proposed a model to account for an unprecedentedly bright near-infrared flare in Sgr A*. I hypothesized that a strong magnetic reconnection event in the flow's innermost region may have triggered rapid electron acceleration and subsequent emission. I developed a numerical code to solve the time-dependent transport equation for the evolution of these electrons, and I reproduced the observed light curve for this event with high accuracy.
In {% cite Gutierrez_etal2021A&A...649A..87G %}, I presented a more comprehensive and general model for studying nonthermal processes occurring in RIAFs. I solved the coupled multizone transport equations for primary and secondary relativistic particles and estimated the spectral energy distribution produced by several radiative processes as well as the neutrino production. By treating the inhomogeneous nature of the flow, I was able to constrain the region in the flow where nonthermal emission can occur in Seyfert galaxies' coronae.
Finally, in {% cite RomeroGutierrez2020Univ....6...99R %}, I investigated how various processes occurring in a RIAF produce neutral particles which might load relativistic jets with leptons and baryons.
</p>

<div class="row justify-content-center">
  <div class="col-sm-12 mt-3">
    {% include figure.liquid path="assets/img/NIR_flare.jpg" class="img-fluid rounded z-depth-1" %}
    <div class="caption">Near-infrared light curve of a bright flare in Sgr A*. From {% cite Gutierrez_etal2020ApJ...891L..36G %}.</div>
  </div>
</div>
