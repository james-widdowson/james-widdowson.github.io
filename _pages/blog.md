---
layout: archive
permalink: /blog/
author_profile: true
---

{% assign posts = site.posts | where: "categories", "blog" %}
{% for post in posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}
