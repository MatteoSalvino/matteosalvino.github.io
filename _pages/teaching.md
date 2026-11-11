---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---


<h2 id="ay-26-27">Academic Year 2026-2027</h2>
{% assign courses = site.teaching %}
<ul>
  {% for course in courses %}
  <li>
    {{ course.role }}, {{ course.name }} - {{ course.degree }}, {{ course.institution }}
  </li>
  {% endfor %}
</ul>