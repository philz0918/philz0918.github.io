---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---


{% include base_path %}


## Publications

{% assign sorted = site.publications | reverse %} {% for post in sorted %} {% include archive-single.html %} {% endfor %}
  
  


