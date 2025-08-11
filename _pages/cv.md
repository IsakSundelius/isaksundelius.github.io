---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

PhD student at Uppsala University.

Contact
======

E-mail: isak [dot] sundelius [at] math [dot] uu [dot] se

Education
======

* M.S. Mathematics, June 2024
  * Thesis title: Derived Autoequivalences of the Product of an Elliptic Curve and a Variety with Discrete Picard and Automorphism Group
  * Exchange, EPFL, September 2023 - January 2024
* B.S. Engineering mathematics, June 2023
  * Thesis title: Murphy's Law for Schemes

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Conferences attended
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

