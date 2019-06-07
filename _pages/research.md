---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Structure and organisation of fluvial networks

I investigate how climate and tectonics control the structure and organisation of fluvial networks, such as the drainage density, channel steepness, and planform geometry of networks. I use high-resolution topographic data to explore the links between climate, tectonics, and fluvial network structure from a range of landscapes.

![](/images/google-earth-view-2042.jpg "River networks from Google Earth View")

### Landscapes and tectonics along the San Andreas Fault

<img src="/images/field_site.png" alt="Basins along the Mendocino Triple Junction" width="500" align="right"/>
I'm interested in understanding how the shape of the topography is related to the tectonic motion along the San Andreas Fault.  I’m currently working at the Mendocino Triple Junction, California, where there is a large variation in uplift rates along the strike of the fault.

I'm analysing a series of river basins along the Californian coast where uplift varies from a maximum of 4 mm/year at Cape Mendocino, to 0.5 mm/year near Fort Bragg. I’m looking to see whether we can detect a signature of this change in the steepness of the rivers, hillslopes, and hilltops.

Alongside this work, I am also interested in understanding how the morphology of river profiles along the entire San Andreas fault is related to both long-term uplift rates from thermochronometry, and short-term uplift rates from GPS data.  More on this coming soon!


### Clustering techniques for river profiles

As part of my post-doctoral work at the University of Potsdam, I’m working on developing techniques for clustering river profiles to identify landscape heterogeneity, such as varying rock types or climatic and tectonic gradients. I separate the river network by stream order, and then use agglomerative hierarchical clustering to find groups of streams with similar morphologies.  This technique has lots of exciting applications, including mapping of landscape transience, detection of debris flow domains from topography, and improving our ability to map channel steepness.

The code for the clustering is freely available on [GitHub](https://github.com/UP-RS-ESP/river-clusters). Tutorials for how to run it are coming soon!

### Landscape evolution modelling

I like to use numerical models of landscape evolution to test new techniques for analysing topography. I'm a big fan of the [Fastscape](https://github.com/fastscape-lem) model, as well as our own implementation of the Fastscape algorithm in [MuddPILE](https://lsdtopotools.github.io/LSDTT_documentation/LSDTT_MuddPILE.html).

I have been running some simple models with varying bedrock lithology to test my clustering algorithm.  See below for an example of how different the speed of propagation of transient signals through a river network can be based on a simple change in erodibility!

<figure class="video_container">
<video width="500" height="340" controls="true">
  <source src="/videos/spatial_K_movie.mp4" type="video/mp4">
</video>
</figure>

_Top half of the model domain is a harder rock type, bottom half is a softer rock type. Note the difference in dissection time between the two!_

## Open source software for topographic analysis

<img src="/images/LSD-logo_horizontal.png" alt="LSDTopoTools" width="600" align="center"/>

A large part of my research is developing open-source software for analysing topographic data. I particularly focus on dealing with high-resolution data derived from lidar point clouds.

I’ve been developing this software, called LSDTopoTools, since my PhD along with colleagues at the University of Edinburgh,  University of Glasgow, and Queen Mary University of London.

You can see our [LSDTopoTools website](lsdtopotools.github.io) for more details, or check out our [GitHub organisation](https://github.com/LSDtopotools).

We have developed lots of novel techniques for analysing topography, such as extracting channel networks, delineating floodplains and river terraces, and calculating hilltop and hillslope metrics.
