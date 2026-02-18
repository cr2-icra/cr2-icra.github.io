---
layout: home
title: CR2 @ ICRA 2026
---
<head>
<link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>

## Workshop on the Path Towards Generalizable Contact-Rich Robotics: Control and Representation

June 1st, 2026. Vienna, Austria. Room TBA

<h2 id="abstract">Overview</h2>
Contact-rich robotics, where robots skillfully interact with the world through physical contact, represents one of the most challenging frontiers in robotics today. Recently, we have seen significant advances in contact representation and control algorithms that also have led to widening gaps between communities. This workshop aims to close these gaps by bringing together leading researchers in the field to participate in a series of facilitated discussions to identify promising research directions, and work toward consensus on key open problems that must be solved to achieve truly generalizable contact-rich robotics systems in the open world.

<h2 id="important-dates">Important Dates</h2>
<ul>
  <li><strong>Submission Deadline:</strong> TBD</li>
  <li><strong>Notification of Acceptance:</strong> TBD</li>
  <li><strong>Workshop Date:</strong> June 1st, 2026</li>
</ul>

<h2 id="panelists">Panelists</h2>
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
        <td>Nima Fazeli, Marc Toussaint, Yuval Tassa, Yilun Du</td>
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
  <h2 id="calls">Calls for Participation</h2>
  <p>
    This workshop is emphasizing in-progress work and how our convictions and perceptions in the field are under constant change. In this spirit, we not calling for *any* invited speakers or presentations of published papers, especially papers that will be on the floor at ICRA. Instead, our calls for participation are below:
  </p>
  <h5>Call for abstracts</h5>
  <p>
    We strongly emphasize and encourage the submission of late-breaking, speculative, or otherwise unpublished material. In this submission category, please submit an abstract (no more than 4 pages) in <a href="https://www.ieee.org/conferences/publishing/templates.html">IEEE conference format</a>. This submission will undergo a double-bline review process. Accepted abstracts will be presented at one of the two poster sessions during the workshop. [...]
  </p>
  <h5>Call for spotlight talks</h5>
  <p>
    We are soliciting traditional research talks with an emphasis on new results and the works of younger researchers. In submissions for this category, please include a 1 minute video summary (with speaker audio) along with a brief abstract of the proposed talk. [...]
  </p>

  <h5>Submission Portal</h5>
  <p>
    All submissions should be made through <a href="https://openreview.net">OpenReview</a> (TBA).
  </p>

  <h2>Topics of Interest</h2>
  <p>We welcome submissions related to, but not limited to, the following topics:</p>

  <h5>Contact Model Representations</h5>
  <ul>
    <li>How do learned models compare against analytical models?</li>
    <li>Should we impose structure when learning contact models?</li>
    <li>How should we compare rigid and compliant (or differentiable) models?</li>
    <li>What are the challenges for simulating contact on GPUs?</li>
    <li>Do (visual) world models understand contact interactions?</li>
    <li>Do simple analytic models (e.g. rigid bodies, complementarity, etc.) work with real sensors (e.g. vision)? What about deformable objects or granular media? What's the utility of algorithms based on these simple models?</li>
    <li>How well do current models/simulations of contact match empirical data? What level of accuracy is needed for control?</li>
  </ul>

  <h5>Algorithms for Contact-Rich Control</h5>
  <ul>
    <li>What are the relative strengths and weaknesses of the various approaches (e.g. sampling, based in differentiable simulation, or non-convex optimization)?</li>
    <li>What are the truly difficult aspects of contact-rich control? Scale? Friction? The hybrid elements? Of these, what matters for actual robot deployment?</li>
    <li>For algorithms which find approximately-optimal or approximately-feasible solutions, how should the results be compared?</li>
    <li>For algorithms which find local solutions, how should we discuss convergence properties? For example, algorithms might be better or worse at "discovering" contact modes, or optimizing within some mode sequence.</li>
    <li>Are zeroth-order optimizers superior to gradient-based optimizers for contact-rich control?</li>
    <li>Should we bridge the sim-real gap by adapting the policy or the model?</li>
    <li>What role should tactile/force feedback play?</li>
  </ul>

  <h5>The State and Future of Contact-Rich Control</h5>
  <ul>
    <li>Should model-based control beat out learning? Should it be competitive? How do we convince the community that it's real?</li>
    <li>Is perception optional? Do lessons learned using full-state feedback translate to systems with noisy/high-dimensional sensing?</li>
    <li>What importance should we place on rigid bodies vs. deformable?</li>
    <li>Do we need to develop better tools?</li>
    <li>Do we need benchmark tasks? If so, what would they be?</li>
    <li>How should we judge controllers for contact-rich tasks?</li>
  </ul>

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

