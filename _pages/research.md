---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Research interests

I investigate how climate and tectonics control the structure and organisation of fluvial networks, such as the drainage density, channel steepness, and planform geometry of networks. I use high-resolution topographic data to explore the links between climate, tectonics, and fluvial network structure from a range of landscapes, and combine this with detailed fieldwork and cosmogenic radionuclide dating.

![](/images/google-earth-view-2042.jpg "River networks from Google Earth View")
_Credit: Google Earth View_

---
### Valley geometry and sediment storage

Wide, flat valley floors tend to be where sediment generated at high elevations is stored as it is transported downstream to ocean basins. This floodplain sediment is an important control on flood hazard: sediment deposition can reduce channel conveyance capacity, therefore increasing flood risk. As floods travel downstream, they can also entrain sediment stored within the valley floor. This causes sediment-rich flows, which travel vast distances compared to clearwater flows, causing loss of life and damage to infrastructure. Sediment stored within mountain valleys therefore acts as a linking node between upstream hazards, i.e. earthquakes, landsliding, debris flows, and downstream hazards, i.e. floods.

Sediment storage is controlled by valley shape, yet we are currently unable to explain what controls the size and dynamics of mountain floodplains. We lack data on the morphology of valley floors and the rates of lateral erosion and are hence unable to predict floodplain evolution. I have recently developed new tools to quantify valley width from digital elevation models, published in [Earth Surface Dynamics](https://esurf.copernicus.org/articles/10/437/2022/). I have then been using these tools to explore climatic and tectonic controls on valley formation across orogens, such as my work on the Himalaya published in [Nature Geoscience](https://www.nature.com/articles/s41561-023-01238-8).

<img src="/images/himalaya_width.jpg" alt="Valley width across the Himalayan orogen" width="800" align="center"/>


---
### Tectonics from topography

I'm interested in understanding how we can best quantify the shape of Earth's topography and relate it to tectonic motion. I couple analysis of hilltops, hillslopes, and rivers, to explore both spatial and temporal variations in tectonic uplift. An example of this is my work on the Mendocino Triple Junction, California, published in [Geology](https://pubs.geoscienceworld.org/gsa/geology/article/48/2/184/579528/Differences-in-channel-and-hillslope-geometry), and our work on the Bolinas Ridge along the San Andreas Fault, published in [Earth and Planetary Science Letters](https://www.sciencedirect.com/science/article/pii/S0012821X19303577).

<img src="/images/san_andreas.jpg" alt="san andreas" width="1000"/>
_Credit: U.S. Geological Survey_

You can watch a talk I gave on this research as part of the [Landscapes Live](https://osur.univ-rennes1.fr/LandscapesLive/) online seminar series here:

[![Landscapes Live Seminar](http://img.youtube.com/vi/zPFLuPouSLk/0.jpg)](http://www.youtube.com/watch?v=zPFLuPouSLk "Landscapes Live Seminar")

---

### Open source software for topographic analysis

<img src="/images/LSD-logo_horizontal.png" alt="LSDTopoTools" width="600" align="center"/>

A large part of my research is developing open-source software for analysing topographic data. I particularly focus on dealing with high-resolution data derived from lidar point clouds.

I’ve been developing this software, called LSDTopoTools, since my PhD along with colleagues at the University of Edinburgh,  University of Glasgow, and Queen Mary University of London.

You can see our [LSDTopoTools website](lsdtopotools.github.io) for more details, or check out our [GitHub organisation](https://github.com/LSDtopotools).

We have developed lots of novel techniques for analysing topography, such as extracting channel networks, delineating floodplains and river terraces, and calculating hilltop and hillslope metrics.

I have developed techniques for clustering river profiles to identify landscape heterogeneity, such as varying rock types or climatic and tectonic gradients. I separate the river network by stream order, and then use agglomerative hierarchical clustering to find groups of streams with similar morphologies.  This technique has lots of exciting applications, including mapping of landscape transience, detection of debris flow domains from topography, and improving our ability to map channel steepness. The code for the clustering is freely available on [GitHub](https://github.com/UP-RS-ESP/river-clusters).