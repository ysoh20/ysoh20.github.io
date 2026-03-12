---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
- (예) Ph.D. in ___, ___ University, YYYY–YYYY
- (예) M.S. in ___, ___ University, YYYY–YYYY
- (예) B.S. in ___, ___ University, YYYY–YYYY

Work experience
======
- (예) YYYY–YYYY: Role, Organization
  - Key impact 1
  - Key impact 2
  
Skills
======
- (예) Python, ML, Systems, Web

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
- (예) Community / Reviewing / Mentoring
