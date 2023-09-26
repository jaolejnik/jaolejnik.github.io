---
layout: page
title: Untitled Flyswatter Game 
description: An asymmetric multiplayer VR game 
img: assets/ufg/cover.png
importance: 0
category: work 
giscus_comments: true
github: 
---
This is the final project for Virtual Reality in Theory and Practice course at Lund University, on which I worked with [Anurag Gargeya](https://www.linkedin.com/in/anuraggargeya/). We developed an asymetric multiplayer VR game for Meta Quest 2 using [Unity](https://unity.com/), [Photon](https://www.photonengine.com/) and [VRIF](https://wiki.beardedninjagames.com/). We showed off the project at the annual VR fair that concludes the course.

<div class="row">
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.html path="assets/ufg/cover.png" title="UFG Poster" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-5 mt-md-0">
        {% include figure.html path="assets/ufg/preview.gif" title="Gameplay Preview" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### About the project
In this game one of the players takes the role of a _Human_, who needs to defend their kitchen full of tasty treats against swarms of ants and flies. They need to kill the bugs using the flyswatter before they steal all the goods, and must try to not destroy the kitchen in the process. The second player becomes a _Bug Queen_, which can throw eggs to spawn her little bug minions and web swing across the counters to wreck havoc. The game lasts around 2 minutes, if during this time the Human succesfully repels the attack of the bugs, they win. However, if majority of the treats are stolen, or the kitchen appliances are destroyed, the Bug Queen is victorious.

### My contribution
I came up with the premise and most of the game mechanics. During the development I was mostly in charge of the bug enemies. I modelled, rigged and animated all of the bug models in Blender. I also implemented their behaviour using Unity’s NavMesh agents, how they collect food, and the Bug Queen’s egg throwing mechanic. I also implemented how the flyswatter interacts with the enemies, kitchen appliances and food.

{% include figure.html path="assets/ufg/models.png" title="Bug models" class="img-fluid rounded z-depth-1" %}
