---
layout: page
title: Neural Network Line Follower 
description: A line follower that teaches itself 
img: assets/nn-linefollower/robot_bottom.jpeg
importance: 4
category: work 
giscus_comments: true
github: https://github.com/jaolejnik/nn-line-follower
---
### About the project
The topic of my bachelor thesis was: _Autonomous Mobile Robot Controlled by an Artificial
Neural Network_. The robot should be able to drive through a whole course from the start to
the end without losing track of the designated path and to stop in a case of possible
collision. 

It has been achieved by building a physical robot, creating a computer
simulation and implementing an artificial intelligence algorithm using reinforcement
learning methods i.e. Deep Q-learning. The ability of the trained network model to make
decisions on performing an optimal action for the current state provided by line sensors
was tested and described for both the simulation and a real life environment.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/nn-linefollower/robot_top.jpeg" title="The robot" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/nn-linefollower/robot_bottom.jpeg" title="Line detection sensors" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/nn-linefollower/simulation.png" title="PyGame simulation" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### Why I made this?
Autonomous robots are something that has fascinated me for my whole life even in their
simplest forms e.g. robo-vacuums. Later on, during the studies, I learned about neural
networks and instantly developed a great interest in them. Hence I wanted to create a
project for my thesis which would combine those two fields and would grant me a better
insight of them.
