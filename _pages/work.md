---
layout: page
permalink: /work/
title: my work history
description: Places I've worked over the years
nav: false
---
<div class="work">

<ul>
  {% assign sorted_work = site.work | sort: "compare_start_date" %}
	{% for item in sorted_work reversed%}
    {% include work.html %}
        
      {% endfor %}



</ul>
</div>
