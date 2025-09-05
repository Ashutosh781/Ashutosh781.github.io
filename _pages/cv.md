---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

You can view my complete CV [here](https://drive.google.com/file/d/1AqzNfTDYa_7IPigrYaiSDW5cHXKaIIks/view?usp=sharing).

<h1>Education</h1>

* M.S. in Robotics (AI minor), Oregon State University, USA
* B.E in Electronics and Communication, BITS Pilani Goa, India

<h1>Work experience</h1>

* Jun 2024 - Present: Graduate Research Assistant
  * Dynamic Robotics and Artificial Intelligence Lab, Oregon State University
  * Supervisor: Prof Alan Fern

* Jun 2022 - May 2023: Research Intern
  * Biorobotics Lab, Carneigie Mellon University
  * Supervisor: Prof Howie Choset

* Jun 2021 - May 2022: Remote Research Collaborator
  * Sheffield Robotics, The University of Sheffield
  * Supervisor: Dr Robert Worley

* Jun 2021 - Jul 2021: Robotics Intern
  * Peppermint Robotics, India
  * Supervisor: Harshal Deshpande

* May 2021 - Jul 2021: Remote Research Intern
  * CSIR - National Institute of Oceanography, India
  * Supervisor: Sh Gajanan Navelkar

<h1>Publications</h1>

<h2>Conference Papers</h2>
  <ul>
  {% for post in site.publications_conference reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
  </ul>

<h2>Workshop Papers</h2>
  <ul>
  {% for post in site.publications_workshop reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
  </ul>
