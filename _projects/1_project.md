---
layout: page
title: EPOG literature
description: Key literature for EPOG meeting Barcelona 2025
img: assets/img/12.jpg
importance: 1
category: work
related_publications: true
---

Andersen, Allan Dahl, Koen Frenken, Victor Galaz, et al. 2021. “On Digitalization and Sustainability Transitions.” Environmental Innovation and Societal Transitions 41 (December): 96–98. https://doi.org/10.1016/j.eist.2021.09.013.
Ditzler, Lenora, and Clemens Driessen. 2022. “Automating Agroecology: How to Design a Farming Robot Without a Monocultural Mindset?” Journal of Agricultural and Environmental Ethics 35 (1): 2. https://doi.org/10.1007/s10806-021-09876-x.
Fairbairn, Madeleine, and Emily Reisman. 2024. “The Incumbent Advantage: Corporate Power in Agri-Food Tech.” The Journal of Peasant Studies 51 (6): 1331–54. https://doi.org/10.1080/03066150.2024.2310146.
Kanger, Laur, Johan Schot, Benjamin K. Sovacool, et al. 2021. “Research Frontiers for Multi-System Dynamics and Deep Transitions.” Environmental Innovation and Societal Transitions, Celebrating a decade of EIST: What’s next for transition studies?, vol. 41 (December): 52–56. https://doi.org/10.1016/j.eist.2021.10.025.
Klerkx, Laurens, Emma Jakku, and Pierre Labarthe. 2019. “A Review of Social Science on Digital Agriculture, Smart Farming and Agriculture 4.0: New Contributions and a Future Research Agenda.” NJAS - Wageningen Journal of Life Sciences 90–91 (December): 100315. https://doi.org/10.1016/j.njas.2019.100315.
Rikap, Cecilia. 2023. “The Expansionary Strategies of Intellectual Monopolies: Google and the Digitalization of Healthcare.” Economy and Society 52 (1): 1. https://doi.org/10.1080/03085147.2022.2131271.

<img width="468" height="390" alt="image" src="https://github.com/user-attachments/assets/b0e480ed-c498-4c39-8191-ed3666f4eb00" />





Attempting to update text.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

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
