---
layout: archive
title: "People"
permalink: /people/
author_profile: true
---

{% include base_path %}

Hello world

{% for post in site.people %}
  {% include archive-single.html %}
{% endfor %}

