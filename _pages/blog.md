---
layout: single
permalink: /blog/
---

{% assign posts = site.posts %}
{% for post in posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}
