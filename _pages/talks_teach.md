---
layout: archive
title: "Talks and Teaching"
permalink: /talks_teach/
author_profile: true
---

I've presented my work at a variety of venues, both as poster presentations and paper talks. In addition, 
I worked as a teaching assistant for two natural language processing courses while at the University of 
Illinois at Urbana-Champaign.

{% for post in site.talks_teach reversed %}
  {% include archive-single_talks-teach.html %}
{% endfor %}
