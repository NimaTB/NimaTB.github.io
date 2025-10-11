---
layout: page
<<<<<<< HEAD
title: event identification
description: A Machine Learning Framework for Event Identification via Modal Analysis of PMU Data
img: 
=======
title: project 1
description: with background image
img: assets/img/12.jpg
>>>>>>> upstream/master
importance: 1
category: work
related_publications: true
---

Power systems are prone to a variety of events (e.g. line trips and generation loss) and real-time identification of such events is crucial in terms of situational awareness, reliability, and security. Using measurements from multiple synchrophasors, i.e., phasor measurement units (PMUs), we propose to identify events by extracting features based on modal dynamics. 
We combine such traditional physics-based feature extraction methods with machine learning to distinguish different event types. Including all measurement channels at each PMU allows exploiting diverse features but also 
requires learning classification models over a high-dimensional space. 
To address this issue, various feature selection methods are implemented to choose the best subset of features.
Using the obtained subset of features, we investigate the performance of two well-known classification models, namely, logistic regression (LR) and support vector machines (SVM) to identify generation loss and line trip events in two datasets. The first dataset is obtained from simulated generation loss and line trip events in the Texas 2000-bus synthetic grid.
The second is a proprietary dataset with labeled events obtained from a large utility in the USA involving measurements from nearly 500 PMUs. 
Our results indicate that the proposed framework is promising for identifying the two types of events.

**Acknowledgments:**
This material is based upon work supported by the National Science Foundation  under  Grants  OAC-1934766, CCF-2048223, and CCF-2029044, and the Power System Engineering Research Center (PSERC) under projects S-87.

<<<<<<< HEAD
<a href="https://ieeexplore.ieee.org/document/9911774">Link to the paper</a>
=======
    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

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

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
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
>>>>>>> upstream/master
