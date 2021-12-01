---
layout: single
title: Lista
permalink: /lista
toc: true
---

{%- for post in site.categories["lista"] %}
* [{{post.title}}]({{post.url}})
{% endfor %}
