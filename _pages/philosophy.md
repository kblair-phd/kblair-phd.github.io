---
layout: archive
title: "Philosophy Scholarship"
permalink: /philosophy/
author_profile: true
---

{% include base_path %}

{% for post in site.philosophy reversed %}
  {% include archive-single.html %}
{% endfor %}
