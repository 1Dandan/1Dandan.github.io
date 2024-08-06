---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
{% include base_path %}

My current research focuses on the application and development of air quality modeling in combination with ground-based and satellite observations. Specifically, I use a chemical transport model [GEOS-Chem](https://geoschem.github.io/index.html) in its high-performance configuration (GCHP) to understand the effects of model spatial resolution on population exposure to air pollutants, investigate different emission source contributions to surface air pollution, and improve model aerosol, specifically mineral dust simulation against ground-based and satellite observations.

<ol>
<li style="padding-left: 6px;font-weight:bold;">
<b> Advances in Simulating the Global Spatial Heterogeneity of Air Quality and Source Sector Contributions </b>
<b style="font-weight: normal">
(<a href="https://doi.org/10.1021/acs.est.2c07253">Zhang et al., <i>Environ. Sci. Technol.</i>, 2023</a>)</b>

<p style="display:inline-block;font-weight: normal;">
<img src="/images/2023_EST_Zhang_TOCart.png" align="right" class="inline" width=500 height="auto" />

High-resolution simulations are essential to resolve fine-scale air pollution patterns due to localized emissions, nonlinear chemical feedbacks, and complex meteorology. However, high-resolution global simulations of air quality remain rare, especially of the Global South. In this study, we exploit recent developments to the GEOS-Chem model in its high performance implementation to conduct one-year simulations in 2015 at cubed-sphere C360 (~25 km) and C48 (~200 km) resolutions. We investigate the resolution dependence of population exposure and sectoral contributions to surface fine particulate matter (PM<sub>2.5</sub>) and nitrogen dioxide (NO<sub>2</sub>), focusing on understudied regions. Our results indicate population exposure in the Global South is more sensitive to resolution enhancement than globally due to more isolated cities. We find that the relative importance of different emission sectors is altered at high resolution, especially revealing lower contributions from open fire emissions relative to population collocated sectors in the Global South, with implications for location-specific air pollution control strategies. 
</p>
</li>

<li style="padding-left: 6px;font-weight:bold;">
<b> Impact of Model Spatial Resolution on Satellite-Derived PM<sub>2.5</sub> </b>
<b style="font-weight: normal">
(<a href="https://doi.org/10.1021/acsestair.4c00084">Zhang et al., <i>ACS ES&T Air</i>, 2024</a>)</b>

<p style="display:inline-block;font-weight: normal;">
<img src="/images/2024_ESTAir_Zhang.png" align="right" class="inline" width=500 height="auto" />

Global geophysical satellite-derived ambient fine particulate matter (PM<sub>2.5</sub>) inference relies upon a geophysical relationship (<i>&#951;</i>) from a chemical transport model to relate satellite retrievals of aerosol optical depth (AOD) to surface PM<sub>2.5</sub>. The resolution dependence of simulated η warrants further investigation. We found remarkable similarity (<i>R</i><sup>2</sup> = 0.96, slope = 1.03) of annual geophysical PM<sub>2.5</sub> across GCHP resolutions at ~25 km and ~200 km. This similarity in part reflects opposite resolution responses across components with increasing by 5% to 11% for primary species while decreasing by &minus;30% to &minus;5% for secondary species at fine resolution. Nonetheless, our results also identify larger resolution sensitivities of <i>&#951;</i> over isolated pollution sources and mountainous regions, where spatial contrast of aerosol concentration and composition are better represented at fine resolution. Our results highlight the resolution-dependence of representing near-surface concentrations and the vertical distribution of chemically different species with implications for inferring ground-level PM<sub>2.5</sub> from columnar AOD. 
</p>
</li>

</ol>