---
layout: archive
permalink: /vortex-method/
title: "Vortex Method"
---

{% include base_path %}
{% include group-by-array collection=site.posts field="tags" %}

{% assign posts = group_items[forloop.index0] %}
{% for post in posts %}
  {% include archive-single.html %}
{% endfor %}

Something more he duh sd
