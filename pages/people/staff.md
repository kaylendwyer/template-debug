---
layout: page-fullwidth
#background: grey
permalink: /staff/
header:
    title: Staff
    slogan: Developed and organized by the Institute for Digital Research in the Humanities with Coneflower Consulting
    background-color: "#fff"
    underline-color: "#e9d758"
---

<div class="faculty-list" style="margin: 3rem 0 0 0;">

{% assign staff_list = site.data.faculty | sort: "name" %}
{% for staff in staff_list %}
  {% if staff.role contains "staff" %}
 

 <div class="row" style="margin-bottom: 4rem; align-items: center;">

   <div class="medium-4 columns" style="padding-right: 50px;">   
	<img src="../images/people/{{ staff.img }}" style="max-width: 200px; border-radius: 50%;"/>
   </div>

   <div class="medium-8 columns">
	<h1 style="font-weight: bold;">{{ staff.name }}</h1>
	{{ staff.bio }}	
   </div>
 </div>

{% endif %}
{% endfor %} 
<div>