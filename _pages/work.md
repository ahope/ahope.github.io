---
layout: page
permalink: /work/
title: my work
description: Places I've worked over the years
nav: false
---
<div class="projects">

<ul>
  {% assign sorted_work = site.work | sort: "compare_start_date" %}
	{% for item in sorted_work reversed%}
        <li>
             {{ item.compare_start_date }} <a href="{{ item.url }}">{{ item.title }}</a>
         </li>
      {% endfor %}



</ul>
</div>
