---
layout: archive
title: "RPM measurement module"
permalink: /measure-module/
author_profile: false
redirect_from:
  - /module/
  - /measuremodule/
---
<style>body {text-align: justify}</style>

A custom measurement module was made to get the rotational speed of the watermills. This module sends every single RPM value to a Google spreadsheet through a webapp, which in turn is displayed by this website to provide [real-time data](https://arenberg-watermill.github.io/real-time-data/). It contains the following hardware:

 - 3D printed case
 - D1 mini (ESP8266 microprocessor) 
 - OLED display
 - Optical switch

The module was first tested thoroughly in a breadboard setup. The rotational speed is calculated using the time difference between two optical switch triggers. Then it is sent to the spreadsheet to ultimately be displayed on the OLED screen.

<figure>

  <img src="/images/rpmmeasuremodule/setup.jpg">
  <figcaption>Setup</figcaption>

</figure>

Then a case was designed using Fusion 360 and 3D printed.

<figure class="row">
  <div class="column2">
    <img src="/images/rpmmeasuremodule/D1Mini_box_full.png" alt="3D model - Front view" style="width:100%">
  </div>
  <div class="column2">
    <img src="/images/rpmmeasuremodule/D1Mini_box_full_section.png" alt="3D model - Section" style="width:100%">
  </div>
  <figcaption>3D model in Fusion 360</figcaption>
</figure>

Finally, the components were placed in the case and the module was installed inside the mill house.

<figure>
  <img src="/images/rpmmeasuremodule/installation.jpg">
  <figcaption>Installation</figcaption>
</figure>

<figure>
  <img src="/images/rpmmeasuremodule/finished.jpg">
  <figcaption>Finished product</figcaption>
</figure>

<figure>
  <img src="/images/rpmmeasuremodule/finished2.jpg">
  <figcaption>Finished product - Close-up</figcaption>
</figure>

 A piece of plastic is glued to the axis of the water wheel and passes through the optical switch to trigger it.

 <figure>
  <img src="/images/rpmmeasuremodule/optical-trigger.jpg">
  <figcaption>Optical switch</figcaption>
</figure>