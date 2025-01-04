---
layout: page
title: Agtech Autonomous Vehicles
description: Interned at John Deere for 1.5 years working on autonomous golf mowers and construction vehicles
img: assets/img/projects/deere_skid_steer.jpg
importance: 2
category: industry
---

I first worked on an autonomous golf mower on two aspects: remote supervision and obstacle detection. I created a real-time web dashboard in Python to remotely supervise up to 6 autonomous golf mowers. I even simulated fake golf mowers in spearate docker containers using log data to better test my application. Next, I assisted in dataset and training aspects of segmentation of golf course specific obstacles and some camera calibration as well. 

My second project was deploying a path tracking controller developed in Matlab to a skid steer construction vehicle.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/deere_golf.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/deere_skid_steer_and_me.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left, testing the autonomous golf mower with some dummy obstacles. On the right, the target skid steer vehicle for path tracking.
</div>
