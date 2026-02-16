---
layout: home
title: CR2 Workshop @ ICRA 2026
---
<head>
<link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>

## Debates on the Path Towards Generalizable Contact-Rich Robotics: Control and Representation
Workshop at ICRA 2026

<h2 id="abstract">Abstract</h2>
Contact-rich robotics, where robots skillfully interact with the world through physical contact, represents one of the most challenging frontiers in robotics today. Recently, we have seen significant advances in contact representation and control algorithms that also have led to widening gaps between communities. This workshop aims to close these gaps by bringing together leading researchers in the field to participate in a series of facilitated discussions to identify promising research directions, and work toward consensus on key open problems that must be solved to achieve truly generalizable contact-rich robotics systems in the open world.

<h2 id="panelists">Panelists</h2>
We are excited to welcome the following expert guest panelists from across both industry and academia with representation from different genders, geographic locations, and career stages.

<div class="panelists">
  <div class="container px-0">
    <div class="row">
      {% assign sorted_panelists = site.panelists | sort: "title" %}
      {% for p in sorted_panelists %}
        <div class="col-12 col-md-6 col-lg-4 mb-3 d-flex">
          {% include project-card.html project=p %}
        </div>
      {% endfor %}
    </div>
  </div>
</div>

<h2 id="schedule">Schedule</h2>


<h2 id="organizers">Organizers</h2>