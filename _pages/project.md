---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

My current projects and research interests lie within using hydrogen and oxygen stable isotopes to see how different bodies of waters change in response to climatic signatures. As of right now, I am looking at how the isotopic composition of the waters of the Finger Lakes has changed during the last 30 or so years, and am attempting to parse out the signals that could be driving these observations. To do this, not only do I need to look at the lakes themselves, but I also need to consider the sourcing of the water that feeds them too. This breaks down into a couple different aspects: 

1) Precipitation
=====
* What are the dominant types of precipitation that fall into the lakes? Is it mostly rain, or does snow contribute more of a signal? 

* Where do the storms that fall into the lakes originate? Do they stem mostly from the Atlantic Ocean, Gulf of Mexico, or do the Great Lakes contribute a lot of moisture? 

2) Tributaries
=====
* How do the rivers and gorges that feed the lakes respond to incoming precipitation, and how sensitive to changes are they on weekly, seasonal, and yearly scales?

* Are there trends in isotopic enrichment/depletion that carry beyond multiple years? How do these trends culminate in what is observed with the lakes?


To tackle these challenges, I have been using hysplit to back calculate the trajectories of storms that land in Ithaca and then cross compare these tracks with their isotopic composition. I also have been collecting daily samples of a nearby stream to see how sensitive it is to seasonal changes. However, I also collect samples from the stream for cations, anions, and silica to better understand how the structure of the bedrock influences the stream in the long term.


{% include base_path %}


{% for post in site.project %}
  {% include archive-single.html %}
{% endfor %}