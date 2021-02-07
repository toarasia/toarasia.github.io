---
title: "Presentations"
layout: gridlay
excerpt: "Presentations"
sitemap: false
permalink: /presentations/
---

# Presentations

{% for talk in site.data.talklist %}

  {% if talk.invited_talk == 1 %}
  - {{ talk.title }}, presented by {{ talk.presenter }} at <b>{{ talk.meeting }}</b>, <u>{{ talk.date }}</u>, {{ talk.location }}. <b>(Invited)</b>
  {% endif %} 

  {% if talk.invited_talk == 0 %}
  - {{ talk.title }}, presented by {{ talk.presenter }} at <b>{{ talk.meeting }}</b>, <u>{{ talk.date }}</u>, {{ talk.location }}.
  {% endif %} 
  
{% endfor %}



