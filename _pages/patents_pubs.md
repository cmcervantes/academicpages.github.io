---
layout: archive
title: "Patents and Publications"
permalink: /patents_pubs/
author_profile: true
---

Patents and publications can be found below. Note that papers have full text links but, 
due to the nature of patent applications, only overviews are provided for patents 
(excepting in cases where there's an associated paper draft).

{% include base_path %}

{% for post in site.patents_pubs reversed %}
  {% include archive-single_patents-pubs.html %}
{% endfor %}
