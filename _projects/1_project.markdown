---
layout: page
title: The IoT Spotify Clock
description: A Fun RGB LED Matrix project
img: /assets/img/12.jpg
importance: 1
category: fun
---

My goal with this project was to become better acquainted with an RGB LED Matrix from AdaFruit. I wanted to be able to show two different things:

* The time
* What I'm currently listening to on Spotify

I originally wanted to be able to swap between many different displays (e.g., weather), but simplified to better understand the capabilities and constraints before taking that step.

The (current) final output is a voice-activated display. It starts by showing the time while waiting to update from Spotify. When a song is played, it displays the title and artist. At any point, I can swap between the clock display and the Spotify display. I can also ask to change the color of the primary display.

## Current Github Status 

* Host Name : {{ site.github.hostname }}
* URL : {{ site.github.url }}
* BaseURL : {{ site.github.baseurl }}
* Archived : {{ site.github.archived}}
* Contributors : 
{% for contributor in site.github.contributors %}
  * {{ contributor.login }}
{% endfor %}