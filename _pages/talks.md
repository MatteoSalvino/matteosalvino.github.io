---
layout: archive
title: "Talks"
permalink: /talks/
author_profile: true
---

{% for talk in site.talks %}
* **{{ talk.role }} @ {{ talk.venue }}**, {{ talk.location }}. {{ talk.date | date: "%B %Y" }}.  
  *Title*: {{ talk.title }}
{% endfor %}
