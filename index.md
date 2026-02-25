---
layout: home
title: CR2@ICRA2026
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
  <li><strong>Submission Deadline:</strong> April 3rd, 2026</li>
  <li><strong>Notification of Acceptance:</strong> April 17th, 2026</li>
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
        <td>Panel 1: Contact Model Representations</td>
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
        <td>Panel 2: Algorithms for Contact-Rich Control</td>
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
        <td>Panel 3: State and Future for Contact-Rich Control</td>
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

{% capture calls_content %}
  <h2 id="calls">Calls for Participation</h2>
  <p>
    This workshop is emphasizing in-progress work and how our convictions and perceptions in the field are under constant change. In this spirit, we not calling for *any* invited speakers or presentations of published papers, especially papers that will be on the floor at ICRA. Instead, our calls for participation are below:
  </p>
  <h5>Call for abstracts</h5>
  <p>
    We strongly emphasize and encourage the submission of late-breaking, speculative, or otherwise unpublished material. In this submission category, please submit an abstract (no more than 4 pages) in <a href="https://www.ieee.org/conferences/publishing/templates.html">IEEE conference format</a>. This submission will undergo a double-blind review process. Accepted abstracts will be presented at one of the two poster sessions during the workshop.
  </p>
  <h5>Call for research talks</h5>
  <p>
    We have 8-10 slots for solicited talks (10-15 minutes) to be selected from submitted abstracts. The selection process will emphasize new and creative ideas or results that have not previously been published. Work centered around papers being presented at ICRA will not be considered. We particularly encourage submissions from more junior researchers, loosely defined. For your submission to be considered for a talk, please include a 2-3 minute video summary (with speaker audio) along with a brief abstract of the proposed talk. The video summary should serve as a preview of what you would present, though we understand that the details of the talk will evolve between the submission date and the workshop itself.
  </p>

  <h5>Submission Portal</h5>
  <p>
    All submissions should be made through <a href="https://openreview.net/group?id=IEEE.org/ICRA/2026/Workshop/CR2">OpenReview</a>.
  </p>

  <h2>Topics of Interest</h2>
  <p>We welcome submissions related to, but not limited to, the following topics:</p>

  <h5>Contact Model Representations</h5>
  <ul>
    <li>Learned vs. analytical contact models</li>
    <li>Structure-preserving learned models</li>
    <li>Rigid and compliant and differentiable contact models</li>
    <li>GPU-accelerated contact simulation</li>
    <li>Contact reasoning in visual world models</li>
    <li>Analytical and learned models for deformable objects, granular media</li>
    <li>Sim-to-real fidelity and accuracy requirements for control</li>
  </ul>

  <h5>Algorithms for Contact-Rich Control</h5>
  <ul>
    <li>Sampling, differentiable simulation, and non-convex optimization methods</li>
    <li>Key challenges for deployment: scale, friction, and hybrid dynamics</li>
    <li>Evaluation and comparison of approximate solvers</li>
    <li>Convergence properties and contact mode discovery in local solvers</li>
    <li>Zeroth-order and gradient-based optimization for contact</li>
    <li>Sim-to-real policy transfer and adaptation</li>
    <li>Tactile and force feedback in contact-rich control</li>
  </ul>

  <h5>The State and Future of Contact-Rich Control</h5>
  <ul>
    <li>Model-based and learning-based control</li>
    <li>Perception and high-dimensional sensing for contact-rich tasks</li>
    <li>Rigid body and deformable object manipulation</li>
    <li>Tools and infrastructure for contact-rich robotics</li>
    <li>Benchmarks and evaluation metrics for contact-rich control</li>
  </ul>
{% endcapture %}

{% include callout.html content=calls_content %}

<style>
.organizers-grid {
  display: grid;
  gap: 1rem;
  margin-top: 1.5rem;
  margin-bottom: 3rem;
}
@media (min-width: 900px) {
  .organizers-grid {
    grid-template-columns: repeat(5, 1fr);
  }
}
@media (min-width: 600px) and (max-width: 899px) {
  .organizers-grid {
    grid-template-columns: repeat(4, 1fr);
  }
}
@media (max-width: 599px) {
  .organizers-grid {
    grid-template-columns: repeat(3, 1fr);
  }
}
</style>

<h2 id="organizers">Organizers</h2>
<div class="organizers-grid">
{% assign sorted_organizers = site.organizers | sort: "order" %}
{% for person in sorted_organizers %}
  {% include organizer-card.html person=person %}
{% endfor %}
</div>

For questions or inquiries, please contact us at [cr2-icra2026@mit.edu](mailto:cr2-icra2026@mit.edu).

