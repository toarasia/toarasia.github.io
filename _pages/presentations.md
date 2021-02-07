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
  - 1<b>{{ talk.title }}<b>, presented by {{ talk.presenter }} at <u>{{ talk.meeting }}<u>, {{ talk.date }}, {{ talk.location }}. <b>(Invited)</b>
  {% endif %} 

  {% if talk.invited_talk == 0 %}
  - 1<b>{{ talk.title }}<b>, presented by {{ talk.presenter }} at <u>{{ talk.meeting }}<u>, {{ talk.date }}, {{ talk.location }}.
  {% endif %} 
  
{% endfor %}



