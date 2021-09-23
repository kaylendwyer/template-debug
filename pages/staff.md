---
layout: page-fullwidth
#background: grey
permalink: /staff/
header:
    title: staff
    slogan: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
    background-color: "#39393A"
---


<!-- 
{% for faculty in site.faculty %}
{{ faculty.content }}

{% endfor %} 
-->


<div class="faculty-list" style="margin: 3rem 0 0 0;">

{% for staff in site.staff %}
<div class="row" style="margin-bottom: 4rem; align-items: center;">

<div class="medium-4 columns" style="padding-right: 50px;">
	<img src="{{ staff.img }}" style="max-width: 200px; border-radius: 50%;"/>
</div>

<div class="medium-8 columns">
	<h1 style="font-weight: bold;">{{ staff.person_name }}</h1>
	{{ staff.content }}	
</div>



</div>


{% endfor %} 
<div>