---
title: "Allan Lab - Team"
layout: gridlay
excerpt: "Allan Lab: Team members"
sitemap: false
permalink: /team/
---

{% assign pi = site.data.team_members[0] %}

<h1 class="section-title">Group Leader</h1>

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


<h1 class="section-title">Group Members</h1>

<p><strong>We are  looking for self-motivated PhD students and RAs to join the team</strong>
(<a href="{{ site.url }}{{ site.baseurl }}/vacancies">see openings</a>)!</p>

<div class="row">
  <div class="col-sm-6 clearfix">
    <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/xihao.jpg"
         alt="Xihao Piao (Paku)"
         style="float:left; margin-right:16px; width:175px; height:175px; border-radius:50%; object-fit:cover;" />
    <h4>Xihao Piao (Paku)</h4>
    <i>Ph.D. student, Osaka University (2024 - )</i>
    <ul style="overflow: hidden">
      <li>Time series, AI for bioinformatics, Knowledge Graph</li>
    </ul>
  </div>

  <div class="col-sm-6 clearfix">
    <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/rikuto.jpg"
         alt="Kotoge Rikuto"
         style="float:left; margin-right:16px; width:175px; height:175px; border-radius:50%; object-fit:cover;" />
    <h4>Kotoge Rikuto</h4>
    <i>Ph.D. student, Osaka University (2024 - )</i>
    <ul style="overflow: hidden">
      <li>EEG, brain dynamic modeling</li>
    </ul>
  </div>
</div>

<div class="row">
  <div class="col-sm-6 clearfix">
    <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/zihang.jpg"
         alt="Zihang Wang (Alex)"
         style="float:left; margin-right:16px; width:175px; height:175px; border-radius:50%; object-fit:cover;" />
    <h4>Zihang Wang (Alex)</h4>
    <i>Ph.D. student, Waseda University (2024 - )</i>
    <ul style="overflow: hidden">
      <li>Neuromorphic computing</li>
    </ul>
  </div>

  <div class="col-sm-6 clearfix">
    <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/koki.jpg"
         alt="Koki Yoshida"
         style="float:left; margin-right:16px; width:175px; height:175px; border-radius:50%; object-fit:cover;" />
    <h4>Koki Yoshida</h4>
    <i>M.Sc. student, Osaka University (2025 - )</i>
    <ul style="overflow: hidden">
      <li>EEG, biosignal foundation model</li>
    </ul>
  </div>
</div>

<div class="row">
  <div class="col-sm-6 clearfix">
    <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/yiming.jpg"
         alt="Yiming Wu"
         style="float:left; margin-right:16px; width:175px; height:175px; border-radius:50%; object-fit:cover;" />
    <h4>Yiming Wu</h4>
    <i>M.Sc. student, Osaka University (2025 - )</i>
    <ul style="overflow: hidden">
      <li>LLM / Agent for bioinformatics</li>
    </ul>
  </div>
</div>

<h1 class="section-title">Alumni</h1>

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
