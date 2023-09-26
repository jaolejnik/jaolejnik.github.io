---
layout: page
title: NPR-Renderer 
description: Implementation of a non-photorealistic renderer using OpenGL 
img: assets/npr-renderer/lego-comic.png
importance: 2
category: work 
giscus_comments: true
github: https://github.com/jaolejnik/npr-renderer 
---

This is the final project for Advanced Computer Graphics course at Lund University, on
which I worked with [Trevina Litchmore](https://www.linkedin.com/in/trevinalitchmore/). At
the course-wide competition it was voted as the best project by the jury consisting of
representatives from **AMD**, **NVIDIA** and **Ubisoft Massive Entertainment**.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/npr-renderer/sofa-sketch.png" title="" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/npr-renderer/sofa-comic.png" title="" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### About the project
Realistic computer graphics were always associated with the most advanced technology and memorable experiences. Nowadays this is definitely still true, although the advancement in the field of 3D graphics is not as noticeable (especially by people outside the industry) as in early 2000s. This led to creators using unconventional ways to stylize their work, to make it more distinguishable from others. In the past, this stylization was often the consequence of hardware limitation, but today it is a conscious choice on part of the 3D graphics artist. Thus we wanted to explore this subject ourselves and came up with the idea to implement a non-physically based renderer that produces images that mimicked sketches. Additionally, we combined some aspects of the sketch renderer with diffuse shading and dithering to create a renderer that would output images in the style of the famous Pop Art artist, Roy Lichtenstein.

If you are interested in more in-depth explanation of the implementation I strongly encourage you to read our short report [here](https://raw.githubusercontent.com/jaolejnik/npr-renderer/main/TLitchmore_JOlejnik_NPR_Report.pdf).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/npr-renderer/lego-sketch.png" title="" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/npr-renderer/lego-comic.png" title="" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

{% include figure.html path="assets/npr-renderer/sponza-pipeline-sketch.png" title="" class="img-fluid rounded z-depth-1" %}

{% include figure.html path="assets/npr-renderer/sponza-pipeline-comic.png" title="" class="img-fluid rounded z-depth-1" %}
