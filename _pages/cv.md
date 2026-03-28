---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---


{% include base_path %}

For the most up-to-date and complete version of my CV, see my [CV](https://github.com/philz0918/sangpilY_cv/blob/main/CV_Sangpil_Y.pdf).

Education
=====
* **University of Florida**, Gainesville, FL, USA, May 2022 - August 2026 (Expected)
  * Ph.D. in Computer Science 
  * Advisor: Bonnie J. Dorr

* **Indiana University**, Bloomington, IN, USA, Aug 2019 - May 2021
  * M.S. in Data Science

* **Sungkyunkwan University**, Seoul, South Korea, Mar, 2010 - Feb, 2019
  * Bachelor in Data Science
  * Bachelor in Library and Information Science


Work Experience
=====

* Graduate Research Assistant — Mar 2022 – Present
  * Department of CISE, University of Florida
  * Developed politeness/formality detection models
  * Designed SRL algorithms for mid-resource languages
  * Established NLP&C lab environment

* Graduate Teaching Assistant — Jan 2023 – Present
  * Department of CISE, University of Florida
  * Taught and developed course projects for Natural Language Processing (CAP 4641 / CIS6930)
 
* Instructor — Spring 2024
  * Department of CISE, University of Florida
  * Taught Natural Language Processing (CAI 6307)

* Graduate Researcher (Wissee) -  Oct 2020 – May 2021
  * Developed an LSTM-CRF model for Named Entity Recognition (NER) on real-world data, achieving 69.3% F1 score under
    noisy and domain-specific conditions

    



Publications
=====
{% assign sorted = site.publications | reverse %} {% for post in sorted %} {% include archive-single.html %} {% endfor %}

Teaching
=====
{% for post in site.teaching reversed %}{% include archive-single.html %}{% endfor %}
  
  


