---
layout: page-fullwidth
title: People
#background: grey
permalink: /people/
header: no
---



<!-- 

## CODE FOR LIST OF FACULTY IN ONE PAGE ##
{% for portfolio in site.portfolio %}
<h2>{{ portfolio.title }}</h2>
{{ portfolio.content }}

{% endfor %} -->

{% for faculty in site.faculty %}
{{ faculty.content }}

{% endfor %}