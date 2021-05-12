---
title: "Documents"
layout: gridlay
excerpt: "Documents"
sitemap: false
permalink: /presentations/
---

# Presentations

### 2021
{% for talk in site.data.talk21 %}

  - <b>{{ talk.title }}</b>, presented by {{ talk.presenter }} at <u>{{ talk.meeting }}</u>, {{ talk.date }}, {{ talk.location }}. [PDF](https://igacproject.org/east-asia-focus-working-group)
  
{% endfor %}


### 2020
{% for talk in site.data.talk20 %}

  - <b>{{ talk.title }}</b>, presented by {{ talk.presenter }} at <u>{{ talk.meeting }}</u>, {{ talk.date }}, {{ talk.location }}. [PDF](https://igacproject.org/east-asia-focus-working-group)
  
{% endfor %}

