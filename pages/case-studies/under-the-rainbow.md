---
permalink: /case-studies/under-the-rainbow/
breadcrumb: true
layout: page
header: 
    title: "Under the Rainbow: Oral Histories of Gay, Lesbian, Bisexual, Transgender, and Queer People in  Kansas"
    slogan: Tami Albin, Associate Librarian, KU Libraries
    background-color: "#fff"
    underline-color: "#e9d758"
---

*Under the Rainbow: Oral Histories of Gay, Lesbian, Bisexual, Transgender, Intersex and Queer People in Kansas* is a series of interviews that documents the life stories and experiences of GLBTQ Kansans. 

<img src="../../images/case-studies/Rainbow-logo.gif" alt="Under the Rainbow"/>

It is the first online open access oral history collection of GLBTQ Kansans in the U.S.  


<span style="font-size: 1.25rem;">[View Project »](http://hdl.handle.net/1808/5330)</span>  

---

{% for person in site.data.faculty %}
{% if person.sessions contains "Rainbow" %}

<div class="row" style="margin-top: 4rem; margin-bottom: 4rem; align-items: center;">

<div class="medium-4 columns" style="padding-right: 50px;">
    <img src="../../images/people/{{ person.img }}" alt="{{ person.name }}" style="max-width: 200px; border-radius: 50%;"/>
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