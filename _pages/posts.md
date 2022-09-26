---
layout: archive
title: "Posts"
permalink: /posts/
author_profile: false
---

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
