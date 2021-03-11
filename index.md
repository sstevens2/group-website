---
lesson-example: "https://carpentries.github.io/lesson-example/"
layout: default
title: "Learning how to build websites with Jekyll"
---

## Description
{{ site.description }}

{% assign lead = site.team_members | where:"role", "project lead" | first %}
The project is led by {{ lead.name }}. [See our full team](/about).

More details about the project are available from the [About Page](about)

See some [examples of our work]({{ page.lesson-example }})
