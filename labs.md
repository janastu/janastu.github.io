---
layout: default
title: Labs
permalink: /labs/
---

{% for lab in site.labs %}
 <h2> <a href="{{ lab.url }}"> {{ lab.title }} </a></h2>
 <p> {{ lab.excerpt }} </p>
{% endfor %}