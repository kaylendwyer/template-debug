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

<div class="faculty-list" style="margin: 3rem 0 0 0;">

{% assign faculty_list = site.data.faculty | sort: "name" %}
{% for faculty in faculty_list %}
  {% unless faculty.role contains "staff" or faculty.role contains "panelist" %}

<div class="row" style="margin-bottom: 4rem; align-items: center;">

<div class="medium-4 columns" style="padding-right: 50px;">
	<img src="../images/people/{{ faculty.img }}" alt="{{ faculty.name }}" style="max-width: 200px; border-radius: 50%;"/>
</div>

<div class="medium-8 columns">
	<h1 style="font-weight: bold;">{{ faculty.name }}</h1>
	{{ faculty.bio | markdownify }}	
</div>



</div>

{% endunless %}
{% endfor %} 


{% for faculty in faculty_list %}
  {% if faculty.role contains "panelist" %}

<div class="row" style="margin-bottom: 4rem; align-items: center;">

<div class="medium-4 columns" style="padding-right: 50px;">
  <img src="../images/people/{{ faculty.img }}" alt="{{ faculty.name }}" style="max-width: 200px; border-radius: 50%;"/>
</div>

<div class="medium-8 columns">
  <h1 style="font-weight: bold;">{{ faculty.name }}</h1>
  {{ faculty.bio | markdownify }} 
</div>



</div>

{% endif %}
{% endfor %} 
<div>