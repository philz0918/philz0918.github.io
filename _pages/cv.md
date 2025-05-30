---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---


{% include base_path %}

For the most updated version of my CV, see my [CV](https://github.com/philz0918/sangpilY_cv/blob/main/CV_Sangpil_Y.pdf).

Education
=====
* University of Florida, Gainesville, FL, USA, May 2022-Ongoing
  * Ph.D. in Computer Science, GPA: 3.88/4.00 
  * Present Advisor: Bonnie J. Dorr

* Indiana University, Bloomington, IN, USA, Aug 2019 - May 2021
  * M.S. in Data Science, GPA: 3.88/4.00

* Sungkyunkwan University, Seoul, South Korea, Mar, 2010 - Feb, 2019
  * Bachelor in Data Science, GPA: 3.92/4.50
  * Bachelor in Library and Information Science, GPA: 4.08/4.50 

* University at Buffalo, Buffalo, NY, USA, Jan 2016 – May 2016
  * Exchange Student, GPA: 3.93/4.00 

Work Experience
=====

* Graduate Teaching Assistant — Jan 2023 – Present
  * Department of CISE, University of Florida
  * Taught and developed course projects for Natural Language Processing (CAP 4641 / CIS6930)

* Graduate Research Assistant — Mar 2022 – Present
  * Department of CISE, University of Florida
  * Developed politeness/formality detection models
  * Designed SRL algorithms for mid-resource languages
  * Established NLP&C lab environment

* Instructor — Spring 2024
  * Department of CISE, University of Florida
  * Taught Natural Language Processing (CAI 6307)
 


Publications
=====
{% assign sorted = site.publications | reverse %} {% for post in sorted %} {% include archive-single.html %} {% endfor %}

Teaching
=====
{% for post in site.teaching reversed %}{% include archive-single.html %}{% endfor %}
  
  


