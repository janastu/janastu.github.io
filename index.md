---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---

{% for lab in site.labs %}
 <h2> <a href="{{ lab.url }}"> {{ lab.title }} </a></h2>
 <p> {{ lab.excerpt }} </p>
{% endfor %}
