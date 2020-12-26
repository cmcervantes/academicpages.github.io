---
layout: archive
title: "Service and Leadership"
permalink: /service_leadership/
author_profile: true
---

During my time at the University of Illinois at Urbana-Champaign, I served on several 
committees and formally as a mentor for undergraduate researchers. 

{% include base_path %}

{% for post in site.service_leadership reversed %}
  {% include archive-single_service-leadership.html %}
{% endfor %}
