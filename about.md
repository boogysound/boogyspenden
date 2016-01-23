---
layout: page
title: About
permalink: /about/
---

{{site.data.termine.var1}}

{% for termin in site.data.termine.termine %}
  {{termin.zeit}}
{% endfor %}

This is the base Jekyll theme. You can find out more info about customizing your Jekyll theme, as well as basic Jekyll usage documentation at [jekyllrb.com](http://jekyllrb.com/)
