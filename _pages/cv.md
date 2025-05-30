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
* University of Florida, Gainesville, FL, USAPh.D. in Computer Science, GPA: 3.88/4.00 — May 2022 – PresentAdvisor: Bonnie J. Dorr

* Indiana University, Bloomington, IN, USAM.S. in Data Science, GPA: 3.88/4.00 — May 2021

* Sungkyunkwan University, Seoul, South KoreaB.A. in Data Science, Library and Information Science, GPA: 4.08/4.50 — Feb 2019

* University at Buffalo, Buffalo, NY, USAExchange Student, GPA: 3.93/4.00 — Jan 2016 – May 2016

Work Experience
======
* Graduate Teaching Assistant — Jan 2023 – PresentDepartment of CISE, University of Florida
  * Taught and developed course projects for Natural Language Processing (CAP 4641 / CIS6930)

* Graduate Research Assistant — Mar 2022 – PresentDepartment of CISE, University of Florida
  * Developed politeness/formality detection models
  * Designed SRL algorithms for mid-resource languages
  * Established NLP&C lab environment
*  Instructor — Spring 2024Department of CISE, University of Florida
  * Taught Natural Language Processing (CAI 6307)


Publications
======
{% assign sorted = site.publications | reverse %} {% for post in sorted %} {% include archive-single.html %} {% endfor %}
  
  
Teaching
======
{% for post in site.teaching reversed %}{% include archive-single.html %}{% endfor %}


