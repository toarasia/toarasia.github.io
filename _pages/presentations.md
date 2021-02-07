---
title: "Presentations"
layout: gridlay
excerpt: "Presentations"
sitemap: false
permalink: /presentations/
---

# Presentations

### 2021
{% for talk in site.data.talk21 %}

  - <b>{{ talk.title }}</b>, presented by {{ talk.presenter }} at <u>{{ talk.meeting }}</u>, {{ talk.date }}, {{ talk.location }}.
  
{% endfor %}


### 2020
{% for talk in site.data.talk20 %}

  - <b>{{ talk.title }}</b>, presented by {{ talk.presenter }} at <u>{{ talk.meeting }}</u>, {{ talk.date }}, {{ talk.location }}.
  
{% endfor %}

