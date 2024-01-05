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

* M.S. in Robotics, Oregon State University, USA, 2025 (expected)
* B.E in Electronics and Communication, BITS Pilani Goa, India, 2023

<h1>Work experience</h1>

* Jun 2022 - May 2023: Research Intern
  * Biorobotics Lab, Carneigie Mellon University
  * Advisor: Professor Howie Choset

* Jun 2021 - May 2022: Remote Research Collaborator
  * Sheffield Robotics, The University of Sheffield
  * Advisor: Dr Robert Worley

* Jun 2021 - Jul 2021: Robotics Intern
  * Peppermint Robotics, India

* May 2021 - Jul 2021: Remote Research Intern
  * CSIR - National Institute of Oceanography, India
  * Advisor: Gajanan Navelkar

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
