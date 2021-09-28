---
permalink: /case-studies/american-indian-digital-history-project/
breadcrumb: true
layout: page
header: 
    title: The American Indian Digital History Project
    slogan: Kent Blansett, Langston Hughes Associate Professor of Indigenous Studies and History, University of Kansas
    background-color: "#fff"
    underline-color: "#ff8552"

---

The American Indian Digital History Project works in partnership with Native peoples and communities to promote the recovery, sharing, preservation, and protection of rare Tribal archival and primary source materials. The project seeks to increase access to historical Tribal documents in order to encourage accurate and responsible American Indian research. 

<img src="../../images/case-studies/AIDHP-screenshot3.png" style="float:left; border: 2px solid lightgrey; margin-bottom: 10px;"/>

This innovative digital project is a cooperative partnership between the University of Kansas, the University of Nebraska at Omaha (UNO), Tribal communities, Tribal Colleges, Native organizations, Libraries, Universities/Colleges, and the larger public. 

<span style="font-size: 1.25rem;">[View Project »](http://aidhp.com/)</span>

---

{% for person in site.data.faculty %}
{% if person.sessions contains "AIDHP" %}

<div class="row" style="margin-top: 4rem; margin-bottom: 4rem; align-items: center;">

<div class="medium-4 columns" style="padding-right: 50px;">
    <img src="../../images/people/{{ person.img }}" style="max-width: 125px; border-radius: 50%;"/>
</div>

<div class="medium-8 columns">
    <h4 style="font-weight: bold;">{{ person.name }}</h4>
    {{ person.person_title }}   
</div>



</div>



{% endif %}
{% endfor %}