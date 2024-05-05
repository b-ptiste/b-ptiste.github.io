---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<a href="/files/Resume_callard_baptiste.pdf" target="_blank"><img src="/images/resume.png" alt="Resume" width="300" height="100" /></a>

Education
======
* Ph.D in Version Control Theory, GitHub University, 2018 (expected)
* **M.S. MVA** ENS Paris-Saclay in research in applied mathematics and AI, Paris-Saclay University, 2024
* M.S. in Applied Mathematics, INSA Rennes engineering school 2023

Work experience
======
* Apr. - Oct. 2024: ML Research intern at [Valeo.ai](https://valeoai.github.io/blog/)
Supervisor : [Spyros Gidaris](https://scholar.google.fr/citations?user=7atfg7EAAAAJ&hl=en), [Florent BARTOCCIONI](https://scholar.google.com/citations?user=SemxkMwAAAAJ&hl=fr)
Subject : *"Tokenization from multi-camera autonomous drivin data"*
Outcomes : 

* Feb. - Aug. 2023: ML Research intern at [Airbus DS](https://www.airbus.com/fr/space/space-made-in-france-by-airbus)
Supervisor: [Alexandre Mayerowitz](https://www.linkedin.com/in/alexandre-mayerowitz-393a45b7/?originalSubdomain=fr)
Subject : *"Building segmentation and polygonalization from very high resolution satellite imagery"*
Outcomes : Creation of a new architecture based on [HRNet](https://arxiv.org/abs/1908.07919) and [Attraction field Map representation](https://arxiv.org/abs/1812.021220) which enabled us to obtain better segmentation masks, respecting the coherence constraints: segment sharing for terraced houses, polygon complexity, accuracy: 1 pixel and robustness: must work on all types of landscape.

* July. - Sept. 2022: ML Research intern at [Qohash](https://qohash.com/about-us/)
Supervisor: [Julien Keutchayan](https://dblp.org/pid/202/2872.html)
Subject : *"Insider threat detection within companies using temporal graphs"*
Outcomes : Creation of a new architecture to detect malicious activity in a company. Malicious activity can be characterised as much by a one-off action as by a series of incoherent actions. It also depends on the person's role within the company. The solution was to create a [temporal graph of activity](https://github.com/graphaware/neo4j-timetree) for each employee and then, at a higher level, to introduce a company graph. Malicious activity is then detected in a self-supervised manner using an auto-encoder. 

* July. - Aug.: ML intern at [Wizdeo](https://www.wizdeo.com/en/about-us)
Supervisor : [Jordan Tremoureux](https://www.linkedin.com/in/jordantremoureux/?originalSubdomain=fr)
Subject : *"Predicting the cost of a YouTube influencer sponsorship based on key performance indicators"*
Outcomes : 
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
