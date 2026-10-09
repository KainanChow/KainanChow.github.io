---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

## Education

- **2027** — Ph.D., Tianjin Medical University (in progress)
- **2022** — Master's degree, Nantong University
- **2018** — Bachelor's degree, Nanjing Medical University

## Research Experience

- **2023** — Research Assistant, Fudan University

## Publications

<ul>
{% for post in site.publications reversed %}
  <li><a href="{{ post.url | relative_url }}">{{ post.title | escape }}</a>. <em>{{ post.venue | escape }}</em>, {{ post.date | date: "%Y" }}.</li>
{% endfor %}
</ul>
