---
layout: projects
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

A selection of my recent projects can be found below. Note that both the summaries 
and the listed technologies are inexhaustive, and are mainly included to provide general 
information on the projects.

{% for post in site.projects reversed %}
  {% include archive-single_projects.html %}
{% endfor %}

