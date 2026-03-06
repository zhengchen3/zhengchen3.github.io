---
title: "Zheng Research Group - People"
layout: gridlay
excerpt: "Zheng Research Group: team members"
sitemap: false
permalink: /team/
---

{% assign pi = site.data.team_members[0] %}

<h1 class="section-title">Group Leader</h1>

<div class="row">
<div class="col-sm-4 text-center">
<img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ pi.photo }}" alt="{{ pi.name }}" style="margin-bottom:12px; width:175px; height:175px; border-radius:50%; object-fit:cover;" />
</div>
<div class="col-sm-8 clearfix">
<h4>{{ pi.name }}</h4>
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

<p>
Dr. Zheng Chen is a Specially Appointed Associate Professor at SANKEN, The University of Osaka, within [Sakurai & Matsubara Lab](https://www.dm.sanken.osaka-u.ac.jp).
Before joining SANKEN, he received his Ph.D. degree from Computational Systems Biology Laboratory at Nara Institute of Science and Technology (NAIST). His research lies at the intersection of machine learning, biomedical engineering, and biomedical data science, focusing on EEG, disease prediction, clinical decision making, omics data analysis, and drug discovery. His work has been published in leading AI conferences and biomedicine journals, including ICLR, NeurIPS, KDD, and Nature Biomedical Engineering.
<!-- He serves as an Area Chair and Program Committee member for major conferences such as KDD. -->
Dr. Chen collaborates closely with computer scientists, oncologists, bioinformaticians, and neuroscientists from institutions worldwide, including the University of Illinois Urbana–Champaign (UIUC), the University of Tokyo, Harvard Medical School, and RIKEN.
His research has also been recognized by industry partners including Keiji AI and Guardant Health on AI-driven biomedical data analysis.
</p>

<!-- <p>
Before joining SANKEN, he received his Ph.D. from NAIST and has worked closely with
clinicians and collaborators in neuroscience and oncology. His work has been
published in venues such as NeurIPS, ICLR, and Nature Biomedical Engineering.
The group aims to develop methods that are not only accurate on benchmarks, but
also interpretable and deployable in real-world biomedical settings.
</p> -->

<div class="member-links" style="display:flex; flex-direction:row; gap:12px; align-items:center;">
 {% if pi.scholar %}
 <a href="{{ pi.scholar }}" title="Google Scholar" target="_blank" class="member-icon">
   <i class="fa-solid fa-graduation-cap"></i>
 </a>
 {% endif %}
 {% if pi.github %}
 <a href="{{ pi.github }}" title="GitHub" target="_blank" class="member-icon">
   <i class="fa-brands fa-github"></i>
 </a>
 {% endif %}
 {% if pi.linkedin %}
 <a href="{{ pi.linkedin }}" title="LinkedIn" target="_blank" class="member-icon">
   <i class="fa-brands fa-linkedin"></i>
 </a>
 {% endif %}
 {% if pi.email %}
 <a href="mailto:{{ pi.email }}" title="Email" class="member-icon">
   <i class="fa-solid fa-envelope"></i>
 </a>
 {% endif %}
</div>
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
<i>PhD Student, Osaka University (2024 - )</i>
<ul style="overflow: hidden">
<li>Time series, Bio AI Agent, Knowledge Graph</li>
</ul>
</div>

<div class="col-sm-6 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/teampic/rikuto.jpg"
alt="Kotoge Rikuto"
style="float:left; margin-right:16px; width:175px; height:175px; border-radius:50%; object-fit:cover;" />
<h4>Kotoge Rikuto</h4>
<i>PhD Student, Osaka University (2024 - )</i>
<ul style="overflow: hidden">
<li>EEG, Brain dynamic modeling</li>
</ul>
</div>
</div>

<div class="row">
<div class="col-sm-6 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/teampic/zihang.jpg"
alt="Zihang Wang (Alex)"
style="float:left; margin-right:16px; width:175px; height:175px; border-radius:50%; object-fit:cover;" />
<h4>Zihang Wang (Alex)</h4>
<i>PhD Student, Waseda University (2024 - )</i>
<ul style="overflow: hidden">
<li>Neuromorphic computing</li>
</ul>
</div>

<div class="col-sm-6 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/teampic/koki.jpg"
alt="Koki Yoshida"
style="float:left; margin-right:16px; width:175px; height:175px; border-radius:50%; object-fit:cover;" />
<h4>Koki Yoshida</h4>
<i>M.Sc. Student, Osaka University (2025 - )</i>
<ul style="overflow: hidden">
<li>EEG, Foundation model</li>
</ul>
</div>
</div>

<div class="row">
<div class="col-sm-6 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/teampic/yiming.jpg"
alt="Yiming Wu"
style="float:left; margin-right:16px; width:175px; height:175px; border-radius:50%; object-fit:cover;" />
<h4>Yiming Wu</h4>
<i>M.Sc. Student, Osaka University (2025 - )</i>
<ul style="overflow: hidden">
<li>Bio AI Agent, Metabolic Modeling</li>
</ul>
</div>

<div class="col-sm-6 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/teampic/koki.jpg"
alt="Yiming Wu"
style="float:left; margin-right:16px; width:175px; height:175px; border-radius:50%; object-fit:cover;" />
<h4>Yiming Wu</h4>
<i>Undergraduate Student, University of Southern California (2026 - )</i>
<ul style="overflow: hidden">
<li>Knowledge graph, EEG</li>
</ul>
</div>
</div>


<h1 class="section-title">Alumni</h1>

<div class="row">
<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/ziwei.jpg" alt="Ziwei Yang" style="float:left; margin-right:16px; width:175px; height:175px; border-radius:50%; object-fit:cover;" />
  <h4>Ziwei Yang</h4>
  <i>PhD Student, Kyoto University (2023.4 - 2026.3)</i>
  <ul style="overflow: hidden">
    <li>Multi-omics data, Bio-network</li>
  </ul>
</div>
</div>
