---
layout: page-fullwidth
#background: grey
permalink: /faculty/
header:
    title: Faculty
    slogan: The Institute sessions will be led by more than 20 experienced academics and community partners, offering a breadth of complementary skill sets and areas of expertise that will provide participants rich opportunities for engagement
    background-color: "#fff"
    underline-color: "#e9d758"
---


<!-- 
{% for faculty in site.faculty %}
{{ faculty.content }}

{% endfor %} 
-->


<div class="faculty-list" style="margin: 3rem 0 0 0;">

{% assign faculty_list = site.data.faculty | sort: "name" %}
{% for faculty in faculty_list %}
  {% unless faculty.role contains "staff" %}

<div class="row" style="margin-bottom: 4rem; align-items: center;">

<div class="medium-4 columns" style="padding-right: 50px;">
	<img src="../images/people/{{ faculty.img }}" style="max-width: 200px; border-radius: 50%;"/>
</div>

<div class="medium-8 columns">
	<h1 style="font-weight: bold;">{{ faculty.name }}</h1>
	{{ faculty.bio }}	
</div>



</div>

{% endunless %}
{% endfor %} 
<div>