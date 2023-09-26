---
layout: page
title: Gradientlisa 
description: Exploration of Alternative Image Representation Using Signed Distance Functions 
img: assets/gradientlisa/monalisa-rec.png
importance: 0
category: work 
giscus_comments: true
github: 
---
This is the project for my Master’s Thesis, which I completed under the guidance of [EA SEED](https://www.ea.com/seed)’s Future Graphics team. I got to work alongside many industry veterans: Martin Mittring, Alan Wolfe, Jon Greenberg, Chris Lewin, and Colin Barré-Brisebois, just to name a few. Their vast knowledge and experience were of an incredible help.
<div class="row">
    <div class="col-sm mt-5 mt-md-0">
        {% include figure.html path="assets/gradientlisa/monalisa-org.jpg" title="Reference" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-5 mt-md-0">
        {% include figure.html path="assets/gradientlisa/monalisa-rec.png" title="Reconstruction" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
 
### About the project 
This project leverages the core concepts of differentiable rendering to find alternative representation of images using geometric primitives rendered with Signed Distance Functions. By utilising gradient-descent-based methods it is possible to find optimal parameters of rendered primitives to create high-quality reconstruction. Moreover, this research serves as a foundation for extending the principles and methodologies explored to 2D space. While the project primarily focuses on 2D image representation, the insights gained can be applied to similar tasks in the field of 3D rendering. The project was build using C++, SDL and libtorch (PyTorch C++ API). If you would like to learn more, I strongly encourage you to read my published thesis [here](https://lup.lub.lu.se/student-papers/search/publication/9129143).

### Results
Here are some more reconstructions using various geometric primitives types and increasing number of primitives: 128, 256, 512, 1024 respectively.

<div class="row">
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.html path="assets/gradientlisa/womandarkhair-128.png" title="Reconstructed using 128 displaced circles" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.html path="assets/gradientlisa/womandarkhair-256.png" title="Reconstructed using 256 displaced circles" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.html path="assets/gradientlisa/womandarkhair-512.png" title="Reconstructed using 512 displaced circles" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.html path="assets/gradientlisa/womandarkhair-1024.png" title="Reconstructed using 1024 displaced circles" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.html path="assets/gradientlisa/peppers-128.png" title="Reconstructed using 128 displaced circles" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.html path="assets/gradientlisa/peppers-256.png" title="Reconstructed using 256 displaced circles" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.html path="assets/gradientlisa/peppers-512.png" title="Reconstructed using 512 displaced circles" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.html path="assets/gradientlisa/peppers-1024.png" title="Reconstructed using 1024 displaced circles" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.html path="assets/gradientlisa/cameraman-128.png" title="Reconstructed using 128 displaced circles" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.html path="assets/gradientlisa/cameraman-256.png" title="Reconstructed using 256 displaced circles" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.html path="assets/gradientlisa/cameraman-512.png" title="Reconstructed using 512 displaced circles" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.html path="assets/gradientlisa/cameraman-1024.png" title="Reconstructed using 1024 displaced circles" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.html path="assets/gradientlisa/mandril-128.png" title="Reconstructed using 128 displaced circles" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.html path="assets/gradientlisa/mandril-256.png" title="Reconstructed using 256 displaced circles" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.html path="assets/gradientlisa/mandril-512.png" title="Reconstructed using 512 displaced circles" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.html path="assets/gradientlisa/mandril-1024.png" title="Reconstructed using 1024 displaced circles" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
