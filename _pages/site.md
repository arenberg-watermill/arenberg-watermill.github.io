---
permalink: /site/
title: "The site"
author_profile: false
redirect_from:
  - /water-level-station/
  - /waterlevelstation/
  - /vmm/
---
<style>body {text-align: justify}</style>

{% include base_path %}
{% include toc %}

To understand how the power production is influenced by the environment, a site description is needed. This page gives a short intro to the mill site, the possible improvements that are allowed to be made and the upstream VMM station.

# Mill site

The mill site consists of two water wheels: mill 1 and mill 2. They both consist of blades inclined away from the upstream water.

<figure>
  <div class="zoom-without-container">
        <img src="/images/MillAssignment.png">
  </div>
  <figcaption>Front view (photo by Rob Stevens)</figcaption>
</figure>

## Possible improvements
Instead of pointing away from the water surface, they should be inclined towards it. This can increase the efficiency from 10% up to 84%! Additionally, an inflow weir should be placed upstream so the blades always enter the water under the right angle. 

# VMM station

The data shown below is provided by the VMM (Vlaamse Milieu Maatschappij) and depicts the water level at station "Uitlaatkunstwerk Egenhoven". The data is used to build the model to predict the rotational speed of the watermills based on the water level of the river, see more [here](https://arenberg-watermill.github.io/rpm-model/).

<iframe width="800" height="550"  src='https://www.waterinfo.be/filestore/apps/kisters/js/share/tsclient.html?ZGF0YVNvdXJjZT1tZXJnZWRQb3J0YWwmcGVyaW9kPVAyRCZzdGF0aW9uX25vPTAxSzA4XzAxMiZnbGlzdD1beyJmaWx0ZXIiOnsidHNfbmFtZSI6IlAuMTV8UHYuMTUiLCJ0c19uYW1lX2xvd3JlcyI6IkRhZ0dlbSIsInN0YXRpb25wYXJhbWV0ZXJfbmFtZSI6IkhhZncgUk8iLCJzdGF0aW9uX25vIjoiMDFLMDhfMDEyIn0sInRlbXBsYXRlIjoidm1tX3N0dXdlbiJ9XQ=='  frameborder="0">Sorry, your browser does not seem to support this iframe</iframe>


The water level is being measured and monitored by the VMM.

<figure>
  <div class="zoom-without-container">
        <img src="/images/vmmstation/water-level-measurement.jpg">
  </div>
  <figcaption>Distance sensor that measures the water level</figcaption>
</figure>

The VMM itself uses the data to prevent the city of Leuven from being flooded. When a water level of 22.5 mTAW (distance in meters above sea level) is reached, a pneumatic valve is activated which gradually raises an underwater gate along with the water level. That way, a flood area (instead of the city downstream) gradually fills up with water.

<figure>
  <img src="/images/vmmstation/pneumatic-valve.jpg">
  <figcaption>Pneumatic valves</figcaption>
</figure>

<figure>
  <div class="column2">
    <div class="zoom-without-container">
      <img src="/images/vmmstation/underwater-gate.jpg" style="width:100%">
    </div>
  </div>
  <div class="column2">
    <div class="zoom-without-container">
      <img src="/images/vmmstation/emergency-gate.jpg" style="width:100%">
    </div>
  </div>
  <figcaption>Underwater- and emergency gate</figcaption>
</figure>

The monitoring system can be accessed locally, but also through an online app. The valves can be controlled locally too with the dials underneath the screen.

<figure>
  <div class="column2">
    <div class="zoom-without-container">
      <img src="/images/vmmstation/monitor-system.jpg" style="width:100%">
    </div>
  </div>
  <div class="column2">
    <div class="zoom-without-container">
      <img src="/images/vmmstation/monitor-screen.jpg" style="width:100%">
    </div>
  </div>
  <figcaption>Local monitoring system</figcaption>
</figure>