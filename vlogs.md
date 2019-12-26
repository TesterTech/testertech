---
layout: page
title: "A list of vlogs"
permalink: "/vlogs/"
---

<ul>
  {% for vlog in site.vlogs %}
    <li>
      <a href="{{ vlog.url }}">{{ vlog.title }}</a>
      - {{ vlog.headline }}
    </li>
  {% endfor %}
</ul>