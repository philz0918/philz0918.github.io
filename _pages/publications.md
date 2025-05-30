---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


For the most updated version of my publications page, see my [Google Scholar](https://scholar.google.com/citations?user=klSyUtMAAAAJ&hl=en) profile.

{% include base_path %}

{% assign sorted = site.publications | reverse %} {% for post in sorted %} {% include archive-single.html %} {% endfor %}
