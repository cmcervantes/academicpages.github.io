---
layout: archive
title: "Patents / Publications"
permalink: /patents_pubs/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.patents_pubs reversed %}
  {% include archive-single.html %}
{% endfor %}
