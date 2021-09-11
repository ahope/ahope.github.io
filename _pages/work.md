---
layout: page
permalink: /work/
title: my work
description: Places I've worked over the years
nav: false
---

<div class="projects">

<ul>
	{% for item in site.work%}
        <li>
              <a href="{{ item.url }}">{{ item.title }}</a>
         </li>
      {% endfor %}



</ul>
</div>
