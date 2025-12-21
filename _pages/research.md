---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
{% include base_path %}

My current research focuses on the implementation of the stretched-grid high-performance GEOS-Chem model into the [Intergrated Methane Inversion model (IMI)](https://carboninversion.com/) for a global fine-resolution methane inversion. 

Prior research focuses on the application and development of air quality modeling in combination with ground-based and satellite observations. Specifically, I use a chemical transport model [GEOS-Chem](https://geoschem.github.io/index.html) in its high-performance configuration ([GCHP](https://gchp.readthedocs.io/en/latest/)) to understand the effects of model spatial resolution on population exposure to air pollutants, investigate different emission source contributions to surface air pollution, and improve model aerosol, specifically mineral dust simulation against ground-based and satellite observations.

<ol reversed>

<li style="padding-left: 6px;font-weight:bold;">
<b> Improving Annual Fine Mineral Dust Representation from the Surface to the Column in GEOS-Chem 14.4.1</b><br>
<b style="font-weight: normal">
  (<a href="https://doi.org/10.5194/gmd-18-6767-2025">
    Zhang et al., <i>Geoscientific Model Development</i>, 2025
  </a>)
</b>

<p style="font-weight: normal;">
<img src="{{ '/images/2025_GMD_Zhang.png' | relative_url }}" class="pub-figure-right" alt="Zhang et al., Geoscientific Model Development, 2025 figure">
Accurate simulation of mineral dust remains challenging in global models due to uncertainties in emissions, size distributions, and removal processes. Using the high-performance configuration of GEOS-Chem, this study improves the annual simulation of fine dust by incorporating updated emission physics, size partitioning, and scavenging processes, and by reconciling model and observational size definitions. The updates substantially reduce biases in surface PM<sub>2.5</sub> dust relative to SPARTAN measurements while maintaining comparable skill in column aerosol optical depth against satellite and ground-based observations.
</p>
</li>


<li style="padding-left: 6px;font-weight:bold;">
<b> Impact of Model Spatial Resolution on Satellite-Derived PM<sub>2.5</sub> </b><br>
<b style="font-weight: normal">
  (<a href="https://doi.org/10.1021/acsestair.4c00084">
    Zhang et al., <i>ACS ES&amp;T Air</i>, 2024
  </a>)
</b>

<p style="font-weight: normal;">
<img src="{{ '/images/2024_ESTAir_Zhang.png' | relative_url }}" class="pub-figure-right" alt="Zhang et al., ACS ES&amp;T Air, 2024 figure">
Satellite-derived PM<sub>2.5</sub> inference relies on a model-based geophysical relationship linking aerosol optical depth to surface concentrations. Using GEOS-Chem in its high-performance configuration, we show that annual PM<sub>2.5</sub> inferred from this relationship is largely consistent between coarse (~200 km) and fine (~25 km) global simulations, but exhibits enhanced sensitivity near isolated pollution sources and complex terrain. These results highlight the role of model resolution in representing near-surface and vertical aerosol structure for satellite-based PM<sub>2.5</sub> inference.
</p>
</li>


<li style="padding-left: 6px;font-weight:bold;">
<b> Advances in Simulating the Global Spatial Heterogeneity of Air Quality and Source Sector Contributions </b><br>
<b style="font-weight: normal">
  (<a href="https://doi.org/10.1021/acs.est.2c07253">
    Zhang et al., <i>Environ. Sci. Technol.</i>, 2023
  </a>)
</b>

<p style="font-weight: normal;">
<img src="{{ '/images/2023_EST_Zhang_TOCart.png' | relative_url }}" class="pub-figure-right" alt="Zhang et al., Environ. Sci. Technol., 2023 figure">
High-resolution modeling is critical for capturing fine-scale air pollution patterns driven by localized emissions, nonlinear chemistry, and complex meteorology, yet such global simulations remain rare, particularly for the Global South. Using the high-performance configuration of GEOS-Chem, we conduct one-year simulations at ~25 km and ~200 km resolution to examine how model resolution affects population exposure and sectoral contributions to surface PM<sub>2.5</sub> and NO<sub>2</sub>. We find that population exposure in the Global South is more sensitive to resolution enhancement than the global mean due to more spatially isolated urban centers. Higher resolution also alters inferred sectoral contributions, revealing reduced relative importance of open fires compared to population-collocated emissions, with implications for region-specific air quality mitigation strategies.
</p>
</li>

</ol>
