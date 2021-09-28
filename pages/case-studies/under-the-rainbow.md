---
permalink: /case-studies/under-the-rainbow/
breadcrumb: true
layout: page
header: 
    title: "Under the Rainbow: Oral Histories of Gay, Lesbian, Bisexual, Transgender, and Queer People in  Kansas"
    slogan: Tami Albin, Associate Librarian, KU Libraries
    background-color: "#39393A"
---

<img src="../../images/case-studies/Rainbow-logo.gif"/>

*Under the Rainbow: Oral Histories of Gay, Lesbian, Bisexual, Transgender, Intersex and Queer People in Kansas* is a series of interviews that documents the life stories and experiences of GLBTQ Kansans. It is the first online open access oral history collection of GLBTQ Kansans in the U.S.  


#### [View Project »](http://hdl.handle.net/1808/5330)  

{% for person in site.data.faculty %}
{% if person.sessions contains "Rainbow" %}

<div class="row" style="margin-top: 4rem; margin-bottom: 4rem; align-items: center;">

<div class="medium-4 columns" style="padding-right: 50px;">
    <img src="../../images/people/{{ person.img }}" style="max-width: 200px; border-radius: 50%;"/>
</div>

<div class="medium-8 columns">
    <h4 style="font-weight: bold;">{{ person.name }}</h4>
    {{ person.person_title }}   
</div>



</div>


{% endif %}
{% endfor %}