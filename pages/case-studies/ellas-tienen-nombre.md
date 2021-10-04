---
permalink: /case-studies/ellas-tienen-nombre/
breadcrumb: true
layout: page
presenter: Ivonne Ramírez
header: 
    title: Ellas Tienen Nombre (“They Have Names”)
    slogan: Ivonne Ramírez, independent scholar and writer
    background-color: "#fff"
    underline-color: "#ff8552"
---

Ellas Tienen Nombre (“They Have Names”) is an independent-scholar led project to gather public data and document murdered women and girls in Ciudad Juárez, Mexcio, through mapping and visualization. 

<img src="../../images/case-studies/Ellas-screenshot1.png" style="float:left; border: 2px solid lightgrey; margin-bottom: 10px;" alt="Screenshot of project data visualization"/>

The objective of this feminist mapping project is to focus on the victims of femi(ni)cide, monitoring and georeferencing the places where the bodies of murdered girls and women have been found, as well as breaking down the specificities and data of each of the cases. The project arises from the idea that this information should be available to all types of audiences interested in the subject and with internet access. Due to a political-ideological stance related to the historical context of Ciudad Juárez regarding feminicides, so far, this project has not searched for or received funds or financial support.  

<span style="font-size: 1.25rem;">[View Project »](https://www.ellastienennombre.org/)</span>

---

{% for person in site.data.faculty %}
{% if person.sessions contains "Ellas" %}
<div class="row" style="margin-top: 4rem; margin-bottom: 4rem; align-items: center;">

<div class="medium-4 columns" style="padding-right: 50px;">
    <img src="../../images/people/{{ person.img }}" alt="{{ person.name }}" style="max-width: 125px; border-radius: 50%;"/>
</div>

<div class="medium-8 columns">
    <h4 style="font-weight: bold;">{{ person.name }}</h4>
    {{ person.person_title }}
    <br>
    <br> 
    {{ person.bio }}   
</div>

</div>
{% endif %}
{% endfor %}
