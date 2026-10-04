---
layout: about
title: about
permalink: /
subtitle: University of Maryland, College Park

profile:
  align: right
  image: prof_pic.jpg
  image_circular: true # crops the image to make it circular
  more_info: >
    <div style="text-align: center;">College Park, MD</div>
    <div style="text-align: center;">rmatheu [at] umd [dot] edu</div>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am an Electrical & Computer Engineering Ph.D. student and Clark Doctoral Fellow at the <a href="https://umd.edu/">University of Maryland, College Park</a>, working under the mentorship of Professor <a href="https://johnbaras.com/">John S. Baras</a>, Distinguished University Professor and Endowed Lockheed Martin Chair in Systems Engineering, and Professor <a href="https://calinbelta.com/">Calin Belta</a>, Brendan Iribe Endowed Professor of Electrical & Computer Engineering and Computer Science.

My research focuses on formal methods for the specification, verification, and control of autonomous systems. Much of my work centers on ternary temporal logic. Temporal logics such as Signal Temporal Logic (STL) provide the formal semantics needed for verification and correct-by-construction control synthesis, but their interpretation is binary. Kleene's ternary logic $K_3$ introduces a third truth value _Unknown_ to represent the case where there is not enough information to determine whether a specification is _True_ or _False_. I apply ternary temporal logic to online monitoring and control synthesis over partial trajectories, and to the training of differentiable ternary logic gate networks. I also contribute to integrated data-driven and model-based systems engineering tools for trusted autonomous cyber-physical systems.

<h2 class="section-heading">Research</h2>

{% include research.liquid %}

<h2 class="section-heading">Outside the lab</h2>

A hiking trip through Saguaro National Park, and a striped bass caught on the Chesapeake Bay.

<div class="fun-photos">
  {% include figure.liquid path="assets/img/fun_saguaro.jpg" class="img-fluid rounded" alt="Ryan standing on a rocky outcrop in Saguaro National Park" caption="Saguaro National Park" sizes="200px" %}
  {% include figure.liquid path="assets/img/fun_chesapeake.jpg" class="img-fluid rounded" alt="Ryan holding a striped bass on a boat on the Chesapeake Bay" caption="Chesapeake Bay" sizes="200px" %}
</div>
