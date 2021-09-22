---
layout: page-fullwidth
#background: grey
permalink: /faculty/
header:
    title: Faculty
    slogan: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
    background-color: "#39393A"
---


<!-- 
{% for faculty in site.faculty %}
{{ faculty.content }}

{% endfor %} 
-->


<div class="faculty-list" style="margin: 3rem 0 0 0;">

{% for faculty in site.faculty %}
<div class="row" style="margin-bottom: 4rem; align-items: center;">

<div class="medium-4 columns" style="padding-right: 50px;">
	<img src="{{ faculty.img }}" style="max-width: 200px; border-radius: 50%;"/>
</div>

<div class="medium-8 columns">
	<h1 style="font-weight: bold;">{{ faculty.person_name }}</h1>
	{{ faculty.content }}	
</div>



</div>


{% endfor %} 
<div>