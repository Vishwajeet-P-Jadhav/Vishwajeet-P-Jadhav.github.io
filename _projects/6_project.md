---
layout: page
title: Resistance Modeling in Nanosheet FETs
description: Undergraduate Research at IIT-Roorkee
img:
importance: 4
category: Research Projects
---


## Overview

This project was a part of my honours course on mixed-signal circuit design where we were tasked with designing a 4-th order Continuous Time Butterworth filter in SCL-180nm pdk in Cadence virtuoso at the schematic level.

## Project Details

**Duration:** Sept 2023 – May 2024  <br>
**Advisor:** [Prof. Avirup Dasgupta](https://faculty.iitr.ac.in/ece/avirup/), <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Associate Professor, <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Electronics and Communication Engineering, IIT-Roorkee <br>


## Research Objectives

1. Design a single ended two-stage Miller compensated OTA with given specifications
2. Implement a Tow-Thomas Biquad filter using the previously designed OTA

## Technologies used
- Sentaurus TCAD
- MATLAB

## Learning Outcomes

This was my first time ever designing an OTA, which I had done using the gm/Id method. I learnt a little bit of ocean scripting in Cadence for exporting transistor data for analysis and processed the gm/Id tables in MATLAB. Optimizing for the best set of parameters had me going back and forth between the gm/Id plots and the small-signal expressions. 

The OTA was designed for the assigned specifications and then used in the schematic for Tow-Thomas biquad filter. Two 2nd order filters were cascaded to get the final filter schematic. The exact filter coefficients were obtained from MATLAB.
