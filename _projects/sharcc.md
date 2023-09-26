---
layout: page
title: SHARCC 
description: Colour Correction Of Augmented Reality Objects Using Spherical Harmonics Lighting  
img: assets/sharcc/spherical-harmonics-demo.gif
importance: 3
category: work 
giscus_comments: true
github: https://github.com/jaolejnik/DXPlayground
---

This project was made in cooperation with [LUGG](https://graphics.cs.lth.se/). They provided me with a HoloLens 2 and source code for Rikard Olajos’s ARCC, which was the base for this project. During my work I gained a better understanding of the importance of lighting in 3D simulations, and how big of a role Spherical Harmonics have played over the years in that field. Great source on that topic is [Robin’s Green Spherical Harmonics Lighting: The gritty detail](https://www.cse.chalmers.se/~uffe/xjobb/Readings/GlobalIllumination/Spherical%20Harmonic%20Lighting%20-%20the%20gritty%20details.pdf). This was also my first experience with creating an UWP application based on DirectX 11.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/sharcc/spherical-harmonics.png" title="SH projection of functions with increasing orders of approximation" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/sharcc/spherical-harmonics-demo.gif" title="Limited band reconstruction of different cube maps" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Using Spherical Harmonic to reconstruct limited band signal of cubemaps to simulate enviroment lighting.
</div>

### About the project 
While Virtual Reality headsets completely cut the user off the real world surrounding, Augmented Reality, as the name suggests, augments it by displaying virtual content on top of it, allowing user to still be fully aware of the real world environment. Being able to place and interact with digital objects on a physical desk is truly a mesmerizing experience for the first time users, that seems to bridge the gap between physical and virtual space. However, as the amazement wears off, one can notice that the digital objects are often easily distinguishable and appear to be out of place when compared with their real world equivalents. One of the main reasons for this phenomena is lighting of the virtual scene, which often does not fully match the lighting from the physical environment, hence rendered objects tend to stand out to the user. In this work I investigated colour correction of objects rendered in AR, in order to provide a way to seamlessly blend them with the environment, hence improving the realism and immersion for the user of HoloLens 2.
 
{% include figure.html path="assets/sharcc/desktop-diffuse.png" title="Desktop: Diffuse Shading" class="img-fluid rounded z-depth-1" %}
<div class="caption">
   Desktop Application: Diffuse Shading with single Point Light 
</div>

{% include figure.html path="assets/sharcc/desktop-sh.png" title="Desktop: Spherical Harmonics Lighting" class="img-fluid rounded z-depth-1" %}
<div class="caption">
   Desktop Application: Spherical Harmonics Lighting 
</div>

{% include figure.html path="assets/sharcc/ar-noshading.jpg" title="HoloLens: No shading" class="img-fluid rounded z-depth-1" %}
<div class="caption">
   HoloLens Application: No shading 
</div>

{% include figure.html path="assets/sharcc/ar-sh.jpg" title="HoloLens: Spherical Harmonics" class="img-fluid rounded z-depth-1" %}
<div class="caption">
   HoloLens Application: Spherical Harmonics Lighting 
</div>
