---
title: "About"
layout: gridlay
sitemap: false
permalink: /about/
---

## About
<!-- ===================== PI CARD ===================== -->
<div class="section-card">
<div class="pi-card">

<img src="{{ site.url }}{{ site.baseurl }}/images/{{ site.photo }}"
     class="pi-photo"
     alt="{{ site.name }}"
     loading="lazy">

<div>

<h2 class="pi-name">{{ site.name }}</h2>

<p style="font-style: italic; color: var(--text-secondary);">
  {{ site.title }}, {{ site.institution }}
</p>

Jiaen Wu is a Postdoctoral Fellow in Mechanical Engineering at Stanford University, advised by Steve Collins. She received her Ph.D. degree from ETH Zürich in 2022, where she conducted research in the Multi-Scale Robotics Lab with Bradley Nelson on small-scale robotics and wearable systems. She earned her bachelor’s degree in Control Engineering from Zhejiang University in 2017. 

Her research pioneers intelligent systems that restore and enhance human mobility through wearable robotics, biomechanics, and human-centered AI. She develops next-generation assistive technologies, ranging from gait rehabilitation systems to balance-augmenting exoskeletons that perceive user intent, respond to dynamic environments, and actively improve human mobility. 

Her contribution has been translated into a certified medical device and recognized with multiple awards, including the Swiss AI Awards (2nd place, 2022) and the finalist for the Swiss Excellence Product Award (2022). Her work was featured among the “Top 10 Parkinson’s stories of 2024” by Parkinson’s News Today. She is also an MIT Rising Star in Mechanical Engineering (2025) and a Wu Tsai Human Performance Alliance Distinguished Postdoctoral Fellow at Stanford University.


<!-- I am a researcher in wearable robotics and biomechanics, working at the intersection of robotics, human movement science, and rehabilitation engineering.

My research seeks to understand how humans maintain stable and efficient locomotion, and how robotic systems can augment or restore mobility. I develop experimental platforms and real-time robotic controllers to investigate human balance, gait adaptation, and physical human-robot interaction.

My long-term goal is to advance intelligent assistive technologies that improve mobility, reduce fall risk, and enhance quality of life across aging and clinical populations. -->


<!-- LINKS -->
<div class="pi-links">
{% if site.email %}
  <a href="mailto:{{ site.email }}" class="icon-link" title="Email"><i class="fa-solid fa-envelope"></i></a>
{% endif %}

{% if site.links.cv and site.links.cv != "" %}
  <a href="{{ site.url }}{{ site.baseurl }}/{{ site.links.cv }}" class="icon-link" title="CV"><i class="ai ai-cv"></i></a>
{% endif %}

{% if site.links.google_scholar and site.links.google_scholar != "" %}
  <a href="{{ site.links.google_scholar }}" class="icon-link" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>
{% endif %}

{% if site.links.github and site.links.github != "" %}
  <a href="{{ site.links.github }}" class="icon-link" title="GitHub"><i class="fa-brands fa-github"></i></a>
{% endif %}

{% if site.links.researchgate and site.links.researchgate != "" %}
<a href="{{ site.links.researchgate }}" class="icon-link" title="ResearchGate"><i class="ai ai-researchgate"></i></a>
{% endif %}
</div>

<!-- EDUCATION -->
<!-- {% if site.data.pi[0].education %}
<ul style="margin-top: var(--space-4);">
{% for education in site.data.pi[0].education %}
<li>{{ education | replace: "-","&#8211;" }}</li>
{% endfor %}
</ul>
{% endif %} -->


</div>
</div>
</div>

<!-- ===================== GRANTS ===================== -->
{% if site.data.grants %}
<div class="section-card">
<h3>Grants</h3>
<ul>
{% for grant in site.data.grants %}
<li>{{ grant.name }}</li>
{% endfor %}
</ul>
</div>
{% endif %}

<!-- ===================== AWARDS ===================== -->
{% if site.data.awards %}
<div class="section-card">
<h3>Awards</h3>
<ul>
{% for award in site.data.awards %}
<li>{{ award.name | replace: "-","&#8211;" }}</li>
{% endfor %}
</ul>
</div>
{% endif %}

<!-- ===================== STUDENTS ===================== -->
{% if site.data.people %}
<div class="section-card">
  <h3>Students and Mentoring</h3>

  <ul class="people-list">
    {% for student in site.data.people %}
      <li>
        {{ student.name }},
        {{ student.location }}
        <span class="people-meta">
          ({{ student.degree }}, {{ student.year }})
        </span>
      </li>
    {% endfor %}
  </ul>
</div>
{% endif %}


<!-- ===================== SPONSORS ===================== -->
{% if site.data.funders %}
<div class="section-card">
<h4>Collaborator</h4>

<div class="sponsor-logos" style="display: flex; flex-wrap: wrap; align-items: center; justify-content: center; gap: var(--space-6);">
{% for funder in site.data.funders %}
<a href="{{ funder.url }}" target="_blank">
<img src="{{ site.url }}{{ site.baseurl }}/images/{{ funder.image }}" 
  alt="Funder logo" 
  style="max-height: 80px; max-width: 200px; border-radius: 0;" loading="lazy">
</a>
{% endfor %}
</div>
</div>
{% endif %}
