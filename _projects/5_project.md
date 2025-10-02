---
layout: page
title: IUSSTF-Viterbi'25
description: My summer research intern at USC-Viterbi
img: assets/img/USC_photo.jpg
importance: 1
category: Research Internship
---

## Overview

I spent my summer of 2025 at the University of Southern California, Los Angeles as a part of the [IUSST-Viterbi program](https://iusstf.org/iusstf-viterbi-program) where I undertook research activities at the [ACME lab](https://acme.usc.edu/) led by Prof. Constantine Sideris. My projects focused on biomedical circuits - one was related to testing and characterizing a fabricated IC and the other was IC design for bio-assay.

## Project Details

**Duration:** May 2025 – July 2025  <br>
**Role:** Summer Research Intern    <br>
**Advisor:** [Prof. Constantine Sideris](https://minghsiehece.usc.edu/directory/faculty/profile/?lname=Sideris&fname=Constantine), <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Associate Professor, <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Electronics and Computer Engineering, USC <br>

## Research Objectives

1. Designing PCBs for testing a custom neurostimulator chip
2. Working on the IC measurements and characterization
3. Contributing to the design of a new PLL-based IC for bio-assay in TSMC65nm technology node

## Technologies used
- Cadence virtuoso
- MATLAB
- KiCAD

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/Viterbi_presentation.jpg"    title="Viterbi_presentation" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/PCB.jpg" title="PCB" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The final presentation day, with Thanh Dat Nguyen, Ray Sun and Dean Prof Cauligi Raghavendra in the left image and the PCB I designed in the right.
</div>

## Learning Outcomes
I was tasked with designing the testbench for characterizing the custom neurostimulator chip, which was back from tapeout. I got to design the PCB for testing the IC, which included power management section, current references, voltage regulators and also a raspberry-pi module which was used for configuring the DSP unit of the chip [I made a mistake in the dimensions of the microcontroller footprint while designing, luckily we worked around it while soldering the components. You can see that in the image above]. 

After the board was ready, I worked on the chip measurements. This was my first time characterizing an actual fabricated chip, so it was a great learning experience honestly. For the measurements, I programmed the microcontroller for configuring the DSP unit and recorded the stimulator waveforms in an oscilloscope.

In the IC design project, it was again my first time designing at GHz frequencies. The circuitry there was primarily a PLL made up of an LC-tank VCO which would be interfaced with magnetic nanoparticles for frequency shift-based bio-assay. I modeled the behaviour of the nanoparticles in Cadence by exporting custom s-parameter files to check the frequency dependent inductance. This was then embedded in the PLL to check the behaviour. I proposed certain detection schemes with this architecture, some were more prone to non-idealitites than others. It was a very enriching experience overall - I had guidance from great mentors and a cohort of 15 IUSSTF scholars to keep me company.