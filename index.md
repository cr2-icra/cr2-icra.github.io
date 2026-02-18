---
layout: home
title: CR2 Workshop @ ICRA 2026
---
<head>
<link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>

## Debates on the Path Towards Generalizable Contact-Rich Robotics: Control and Representation
Workshop at ICRA 2026

<h2 id="abstract">Introduction</h2>
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

<h2 id="schedule">Tentative Schedule</h2>
<div class="table-responsive">
  <table class="table table-sm table-striped">
    <thead>
      <tr>
        <th style="width: 18%;">Time</th>
        <th style="width: 52%;">Session</th>
        <th style="width: 30%;">Speakers/Panelists</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>09:00 – 09:15</td>
        <td>Welcome + intro</td>
        <td>Organizers</td>
      </tr>
      <tr>
        <td>09:15 – 10:15</td>
        <td>Debate 1: Contact Model Representations</td>
        <td>Nima Fazeli, Marc Toussaint, Yuval Tassa</td>
      </tr>
      <tr>
        <td>10:15 – 11:00</td>
        <td>Coffee break + poster session</td>
        <td></td>
      </tr>
      <tr>
        <td>11:00 – 12:00</td>
        <td>Spotlight talks (4-5 slots)</td>
        <td></td>
      </tr>
      <tr>
        <td>12:00 – 01:30</td>
        <td>Lunch break</td>
        <td></td>
      </tr>
      <tr>
        <td>01:30 – 02:30</td>
        <td>Debate 2: Algorithms for Contact-Rich Control</td>
        <td>Justin Carpentier, Bibit Bianchini, Hae-Won Park, Emo Todorov</td>
      </tr>
      <tr>
        <td>02:30 – 03:30</td>
        <td>Spotlight talks (4-5 slots)</td>
        <td></td>
      </tr>
      <tr>
        <td>03:30 – 04:15</td>
        <td>Coffee break + poster session</td>
        <td></td>
      </tr>
      <tr>
        <td>04:15 – 05:15</td>
        <td>Debate 3: State and Future for Contact-Rich Control</td>
        <td>Matt Mason, Aaron Ames, Aaron Johnson, Dmitry Berenson</td>
      </tr>
      <tr>
        <td>05:15 – 05:30</td>
        <td>Conclusions</td>
        <td>Organizers</td>
      </tr>
    </tbody>
  </table>
</div>

<div class="callout">
  <h2 id="calls">Calls</h2>
  <p>
    This workshop is emphasizing in-progress work and how our convictions and perceptions in the field are under constant change. In this spirit, CR2 is not calling for *any* invited speakers or presentations of published papers, especially papers that will be on the floor at ICRA. Instead, our calls are below:
  </p>
  <h3>Call for workshop posters</h3>
  <p>
    We will have two poster sessions complementing the three debate topics. We strongly emphasize and encourage the submission of late-breaking, speculative, or otherwise unpublished material. [...]
  </p>

  <h3>Call for spotlight talks</h3>
  <p>
    We will have two spotlight talk sections, each with 4-5 open slots of 10-12 minutes. We are soliciting traditional research talks with an emphasis on new results and the work of younger researchers. In submissions for this category, please include a video of the speaker with a brief snippet of the proposed talk. [...]
  </p>
</div>

<h2 id="organizers">Organizers</h2>

<div class="panelists">
  <div class="container px-0">
    <div class="row">
      {% assign sorted_organizers = site.organizers | sort: "importance" %}
      {% for o in sorted_organizers %}
        <div class="col-12 col-md-6 col-lg-4 mb-3 d-flex">
          {% include project-card.html project=o %}
        </div>
      {% endfor %}
    </div>
  </div>
</div>

