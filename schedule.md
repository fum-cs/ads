---
layout: page
title: Schedule
nav_exclude: true
description: The weekly event schedule.
tags: [Computer Science Dept., Ferdowsi University of Mashhad, علوم کامپیوتر دانشگاه فردوسی مشهد]
---

# Weekly Schedule

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
