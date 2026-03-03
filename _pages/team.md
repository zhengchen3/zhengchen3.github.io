---
title: "Allan Lab - Team"
layout: gridlay
excerpt: "Allan Lab: Team members"
sitemap: false
permalink: /team/
---

{% assign pi = site.data.team_members[0] %}

# {{ pi.name }}

<div class="row">
<div class="col-sm-12 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ pi.photo }}" alt="{{ pi.name }}" style="float:left; margin-right:16px; width:175px; height:175px; border-radius:50%; object-fit:cover;" />
  <h3>{{ pi.name }}</h3>
  <i>{{ pi.info }}</i>
  <ul style="overflow: hidden">

  {% if pi.number_educ == 1 %}
  <li> {{ pi.education1 }} </li>
  {% endif %}

  {% if pi.number_educ == 2 %}
  <li> {{ pi.education1 | markdownify}} </li>
  <li> {{ pi.education2 | markdownify}} </li>
  {% endif %}

  {% if pi.number_educ == 3 %}
  <li> {{ pi.education1 | markdownify}} </li>
  <li> {{ pi.education2 | markdownify}} </li>
  <li> {{ pi.education3 | markdownify}} </li>
  {% endif %}

  {% if pi.number_educ == 4 %}
  <li> {{ pi.education1 | markdownify}} </li>
  <li> {{ pi.education2 | markdownify}} </li>
  <li> {{ pi.education3 | markdownify}} </li>
  <li> {{ pi.education4 | markdownify}} </li>
  {% endif %}

  {% if pi.number_educ == 5 %}
  <li> {{ pi.education1 | markdownify}} </li>
  <li> {{ pi.education2 | markdownify}} </li>
  <li> {{ pi.education3 | markdownify}} </li>
  <li> {{ pi.education4 | markdownify}} </li>
  <li> {{ pi.education5 | markdownify}} </li>
  {% endif %}

  </ul>
  <p></p>
</div>
</div>


# Group Members

 **We are  looking for self-motivated PhD students and RAs to join the team** [(see openings)]({{ site.url }}{{ site.baseurl }}/vacancies) **!**


{% assign number_printed = 0 %}
{% for member in site.data.team_members offset:1 %}

{% if member.name != "Ziwei Yang" %}
  {% assign even_odd = number_printed | modulo: 2 %}

  {% if even_odd == 0 %}
  <div class="row">
  {% endif %}

  <div class="col-sm-6 clearfix">
    <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" alt="{{ member.name }}" style="float:left; margin-right:16px; width:175px; height:175px; border-radius:50%; object-fit:cover;" />
    <h4>{{ member.name }}</h4>
    <i>{{ member.info }} <!--<br>email: <{{ member.email }}></i> -->
    <ul style="overflow: hidden">

    {% if member.number_educ == 1 %}
    <li> {{ member.education1 }} </li>
    {% endif %}

    {% if member.number_educ == 2 %}
    <li> {{ member.education1 | markdownify}} </li>
    <li> {{ member.education2 | markdownify}} </li>
    {% endif %}

    {% if member.number_educ == 3 %}
    <li> {{ member.education1 | markdownify}} </li>
    <li> {{ member.education2 | markdownify}} </li>
    <li> {{ member.education3 | markdownify}} </li>
    {% endif %}

    {% if member.number_educ == 4 %}
    <li> {{ member.education1 | markdownify}} </li>
    <li> {{ member.education2 | markdownify}} </li>
    <li> {{ member.education3 | markdownify}} </li>
    <li> {{ member.education4 | markdownify}} </li>
    {% endif %}

    {% if member.number_educ == 5 %}
    <li> {{ member.education1 | markdownify}} </li>
    <li> {{ member.education2 | markdownify}} </li>
    <li> {{ member.education3 | markdownify}} </li>
    <li> {{ member.education4 | markdownify}} </li>
    <li> {{ member.education5 | markdownify}} </li>
    {% endif %}

    </ul>
  </div>

  {% assign number_printed = number_printed | plus: 1 %}

  {% if even_odd == 1 %}
  </div>
  {% endif %}
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

# Alumni

<div class="row">
<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/ziwei.jpg" alt="Ziwei Yang" style="float:left; margin-right:16px; width:175px; height:175px; border-radius:50%; object-fit:cover;" />
  <h4>Ziwei Yang</h4>
  <i>Research Associate, Kyoto University (2023 - )</i>
  <ul style="overflow: hidden">
    <li>Multi-omics data, bio-network</li>
  </ul>
</div>
</div>
