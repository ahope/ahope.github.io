---
layout: page
permalink: /teaching/
title: teaching
description: Classes I've taught over the years. 
nav: false
---

<div class="projects">

<ul>
	{% for item in site.teaching%}
        <li>
              <a href="{{ item.url }}">{{ item.title }}</a>
         </li>
      {% endfor %}



</ul>
</div>


(Reminder to myself)[https://alshedivat.github.io/al-folio/teaching/]