---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

## The Finger Lakes 

The Finger Lakes are a series of lakes in central New York that were carved out during the retreat of the Laurentian Ice sheet ~12k years ago. While this region is enjoyed for its wine and recreation, several of these lakes are also used as municipal sources of water for nearby towns. 

Hydrologically, these lakes are defined by their short residence times, with most of the lakes replacing their water within 1 to 6 years (Seneca and Skaneateles exhibit the longest times of about 18 years). Also, many of the tributaries that feed these lakes are in gorges which exhibit flashy responses to incoming rainfall. 

My main focus on these lakes is tied to understanding how climatic shifts are changing these lakes in the long term. For example, these lakes have experienced an increased amount of harmful algal blooms (HABs) since 2014. While it is believed that the HABs are arising from an increased amount of rainfall over the region, I want to better understand how else we can observe climatic signals in the lakes and their tributaries. 

<figure>
<img src='/images/DJF_Rain_Per.pdf'>
<figcaption align = "middle">A triangular irregular network (TIN) extrapolation of the winter season rainfall across the Finger Lakes region. Color code represents the percent difference of the '91-'20 climate norms versus the '81-'10 climate norms
</figcaption>
</figure>

In order to disentangle how climate change is affecting these lakes, it is important to focus on a few different key aspects.

1) Precipitation
  * The region has seen a decrease of snow and increase of rain over the last 30 years, especially in the winter (December, January, and February). How has this shift affected the water quality of these lakes?
  
  * Where do the storms that fall into the lakes originate? Do they stem mostly from the Atlantic Ocean, Gulf of Mexico, or do the Great Lakes contribute a significant amount moisture? How do the origin of these storms affect the chemical behavior of the lakes on short/long time scales?

<figure>
<img src='/images/DJF_SNOW_per.pdf'>
<figcaption align = "middle">A triangular irregular network (TIN) extrapolation of the winter season snowfall across the Finger Lakes region. Color code represents the percent difference of the '91-'20 climate norms versus the '81-'10 climate norms
</figcaption>
</figure>

2) Tributaries
  * How do the rivers and gorges that feed the lakes respond to incoming precipitation, and how sensitive to changes are they on weekly, seasonal, and yearly scales?
  
  * Are there trends in isotopic enrichment/depletion that carry beyond multiple years? How do these trends culminate in what is observed with the lakes?
  
  * How do fluxes of chemical species into the lakes (Al, K, PO<sub>4</sub><sup>3-</sup>, Na, NO<sub>3</sub><sup>-</sup>, etc.) change in response to precipitation types throughout seasons? What can we expect to observe as the region sees more rain in the future?

<figure>
<img src='/images/O2.mov'>
<figcaption align = "middle">Saturated oxygen in Cascadilla Creek plotted against temperature during October, 2022
</figcaption>
</figure>


To tackle these challenges, I have been:
  * Using hysplit to back calculate the trajectories of storms that land in Ithaca and then cross compare these tracks with their isotopic composition. 
  
  * Collecting daily samples of a nearby stream to see how sensitive it is to seasonal changes.
  
  * Collecting samples of all 11 Finger Lakes twice per year, once in the summer and once in the winter. 


{% include base_path %}


{% for post in site.project %}
  {% include archive-single.html %}
{% endfor %}