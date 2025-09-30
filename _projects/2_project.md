---
layout: page
title: Design of a CMOS Potentiostat for Glucose Biosensing
description: Undergraduate Research at IIT-R
img: assets/img/3.jpg
importance: 1
category: Research Projects
giscus_comments: true
---


## Overview

This project constituted the design of a glucose potentiostat at the schematic level. Under the guidance of my advisor, I implemented [this paper](https://ieeexplore.ieee.org/abstract/document/10454401) from ISSCC 2024 in SCL-180nm pdk in Cadence virtuoso

## Project Details

**Duration:** April 2024 – Jan 2025  <br>
**Role:** Undergraduate Researcher  <br>
**Advisor:** [Prof. Saravana Kumar M.](https://iitr.ac.in/Departments/Electronics%20and%20Communication%20Engineering%20Department/People/Faculty/100969.html), Assistant Professor, Electronics and Communication Engineering, IIT-Roorkee <br>

## Research Objectives

1. 

## Technologies used
    - Cadence virtuoso
    - Ltspice

## Learning Outcomes

Prior to this project, my exposure to analog circuits was purely coursework based - so in a way this project was my first introduction to circuits research as well as biomedical circuits.

Over the course of designing this system, I got to design blocks such as regenerative feedback comparators, current-steering DACs and certain digital circuitry. I also played around with noise shaping aspects towards the end of this project, which served as a somewhat introduction to mixed-signal circuit design for me.

I also had the opportunity to present my work on this project at the Student research forum at ISICAS-2024. That was a great experience for me where I got to meet many senior researchers and present my work before them.  



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
