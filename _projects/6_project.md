---
layout: page
title: Resistance Modeling in Nanosheet FETs
description: Undergraduate Research at IIT-Roorkee
img: assets/img/5sheet_structure.png
importance: 4
category: Research Projects
---


## Overview

In my 2nd year of undergrad I volunteered at the [Dirac Lab](https://www.iitr.ac.in/diraclab/) at IIT-Roorkee, where I worked on modeling variation of extrinsic resistance in nanosheet FETs

## Project Details

**Duration:** Sept 2023 – May 2024  <br>
**Advisor:** [Prof. Avirup Dasgupta](https://faculty.iitr.ac.in/ece/avirup/), <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Associate Professor, <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Electronics and Communication Engineering, IIT-Roorkee <br>


## Research Objectives

1. Running device level simulations in Sentaurus TCAD
2. Extracting and modeling the resistance variation numerically in MATLAB

## Technologies used
- Sentaurus TCAD
- MATLAB

## Learning Outcomes

This was my first real exposure to electronics research in general, and I dived in headfirst into compact modeling without any prior theoretical foundation. However, fortunately this was also the time when I was doing my introductory semiconductor physics course in parallel. 

I would often spend hours in my 2nd year running device simulations in TCAD, exporting that data and trying to fit models onto the Id-Vd and Id-Vg curves. Unlike my other projects and research work in circuits, my work in compact modeling never really came to complete fruition, as in I could not achieve the initial ambitious goal of proposing a new physics based model for resistance variation in nanosheet FETs. At best I was able to get semi-empirical models to fit the device data.

However, it did teach me a lot about device physics honestly. I was lucky to have access to Sentaurus TCAD while learning introductory semiconductor physics, so I could actually visualize the variation of potential along different directions in different devices and correlate the same to my theory classes.

I also got to know firsthand that not all of our research endevours lead to success and that this is infact a very time consuming route - but I chose to pursure research further nevertheless.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/single_sheet.jpg" title="single sheet" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5sheet_structure.png" title="5sheet str" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/tcad_curve_fits.png" title="curve fits" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Some images from my project. The leftmost is the simulation of a single isolated nanosheet done for extracting potential varation in absence of the pillar like structures. The middle image is that of a 5 sheet NSFET and the last image is one of the Id-Vg curve fits.
</div>