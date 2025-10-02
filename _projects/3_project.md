---
layout: page
title: Continuous Time Filter Design
description: Mixed signal circuit design course project
img: assets/img/7.jpg
importance: 1
category: Semester Projects
---


## Overview

This project was a part of my honours course on mixed-signal circuit design where we were tasked with designing a 4-th order Continuous Time Butterworth filter in SCL-180nm pdk in Cadence virtuoso at the schematic level.

## Project Details

**Duration:** April 2025 – May 2025  <br>
**Role:** Undergraduate Researcher  <br>
**Advisor:** [Prof. Saravana Kumar M.](https://iitr.ac.in/Departments/Electronics%20and%20Communication%20Engineering%20Department/People/Faculty/100969.html), <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Assistant Professor, <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Electronics and Communication Engineering, IIT-Roorkee <br>


## Research Objectives

1. Design a single ended two-stage Miller compensated OTA with given specifications
2. Implement a Tow-Thomas Biquad filter using the previously designed OTA

## Technologies used
- Cadence virtuoso
- MATLAB

## Learning Outcomes

This was my first time ever designing an OTA, which I had done using the gm/Id method. I learnt a little bit of ocean scripting in Cadence for exporting transistor data for analysis and processed the gm/Id tables in MATLAB. Optimizing for the best set of parameters had me going back and forth between the gm/Id plots and the small-signal expressions. 

The OTA was designed for the assigned specifications and then used in the schematic for Tow-Thomas biquad filter. Two 2nd order filters were cascaded to get the final filter schematic. The exact filter coefficients were obtained from MATLAB.


<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/OTA_ckt.png" title="ota img" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/Tow_thomas.png" title="filter img" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The schematic of my OTA on the left and 2nd order Tow-Thomas Biquad filter on the right. The entire filter was implemented as a cascade of two such stages.
</div>
