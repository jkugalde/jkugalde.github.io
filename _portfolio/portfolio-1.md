---
layout: archive
title: "Other projects"
excerpt: "Small or hardware projects"
permalink: /projects/
collection: portfolio
author_profile: true
---

{% include base_path %}
{% for post in site.projects %}
  {% include archive-single.html %}
{% endfor %}

