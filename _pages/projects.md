---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /publications/
---

# Publications

<!-- <div class="projects-intro">

My research develops intelligent robotic systems that enhance
human mobility, balance, and healthcare through biomechanics,
wearable robotics, embedded sensing, and real-time human–robot interaction.

<!-- We combine robotics, sensing, AI, and human experiments to study
human locomotion, neurological rehabilitation, balance control,
and targeted therapeutic systems. -->


<!-- </div> --> 

---

## Human-Robot Interaction 

<div class="project-card">

<div class="project-top">

<div class="project-media">

<video
class="project-video-exo"
autoplay
muted
loop
playsinline>

<source
src="{{ site.url }}{{ site.baseurl }}/videos/projects/exo_walking.mp4"
type="video/mp4">

</video>

</div>

<div class="project-content">


<ul class="project-details">
<li>Adaptive exoskeleton torque control for varying assistance</li>

<li>Perturbation experiments using wearable assistive robots</li>

<li>Human–robot interaction identification during locomotion and balance recovery</li>

<li>Fusion of musculoskeletal modeling and neural networks</li>

<!-- <li>Human-in-the-loop optimization for wearable robotics</li>

<li>Reinforcement learning for rapid exoskeleton personalization</li>

<li>Real-time estimation of human biomechanical states</li>

<li>Sensor fusion and embedded control for wearable systems</li>

<li>Neuromechanical modeling of human locomotion</li>

<li>Ultrasound-based evaluation of muscle–robot interaction</li> -->

</ul>



</div>

</div>

</div>

---

## Human Balance Assessment

<div class="project-card">

<div class="project-top">

<div class="project-media">

<video
class="project-video-human"
autoplay
muted
loop
playsinline>

<source
src="{{ site.url }}{{ site.baseurl }}/videos/projects/MovieS3.mp4"
type="video/mp4">

</video>

</div>

<div class="project-content">


<ul class="project-details">

<li>Quantitative assessment of human balance capability</li>

<li>Perturbation Recovery Time metric for detecting subtle balance impairments</li>

<li>Biomechanics dataset under staedy-state and perturbed walking conditions</li>

<li>Biomechanical feature discovery for balance characterization</li>


</ul>

</div>

</div>

<div class="project-publications">

<h4 class="pub-section-title">
Selected Publications
</h4>

<div class="publication-list">

{% bibliography --query @*[keywords~=balance] %}

</div>

</div>

</div>

---

## Neurological Gait Rehabilitation

<div class="project-card">

<div class="project-top">

<div class="project-media-grid">

<div class="gif-panel">

<video
class="project-video"
autoplay
muted
loop
playsinline>

<source
src="{{ site.url }}{{ site.baseurl }}/videos/projects/patient1_off.mp4"
type="video/mp4">

</video>

<div class="gif-caption">
Patient 1 — Haptic Feedback OFF
</div>

</div>

<div class="gif-panel">

<video
class="project-video"
autoplay
muted
loop
playsinline>

<source
src="{{ site.url }}{{ site.baseurl }}/videos/projects/patient1_on.mp4"
type="video/mp4">

</video>

<div class="gif-caption">
Patient 1 — Haptic Feedback ON
</div>

</div>

<div class="gif-panel">

<video
class="project-video"
autoplay
muted
loop
playsinline>

<source
src="{{ site.url }}{{ site.baseurl }}/videos/projects/patient2_off.mp4"
type="video/mp4">

</video>

<div class="gif-caption">
Patient 2 — Haptic Feedback OFF
</div>

</div>

<div class="gif-panel">

<video
class="project-video"
autoplay
muted
loop
playsinline>

<source
src="{{ site.url }}{{ site.baseurl }}/videos/projects/patient2_on.mp4"
type="video/mp4">

</video>

<div class="gif-caption">
Patient 2 — Haptic Feedback ON
</div>

</div>

</div>

<div class="project-content">

<ul class="project-details">

<li>High-fidelity wearable sensing and acutation systems for real-world gait monitoring</li>

<li>Embedded AI for real-time gait analysis, including motion classification and phase detection</li>

<li>Automated, human-level gait labeling without manual annotation</li>

<li>Lightweight real-time inference on low-power embedded microcontrollers</li>

<li>Closed-loop haptic feedback for pathological gait rehabilitation</li>

<!-- <li>Commercialized as a certified medical device with Magnes AG</li>

<li>Deployed in European hospitals including University Hospital Zurich and CHUV Lausanne</li>

<li>Recognized by Swiss AI Awards, Swiss Excellence Product Award, and CSS Innovation in Health</li>

<li>Featured among “Top 10 Parkinson’s Stories of 2024” by Parkinson’s News Today</li> -->

</ul>


</div>

</div>

<div class="project-publications">

<h4 class="pub-section-title">
Selected Publications
</h4>

<div class="publication-list">

{% bibliography --query @*[keywords~=rehab] %}

</div>

</div>

</div>

---

## Microrobotics for Targeted Therapy

<div class="project-card">

<div class="project-top">

<div class="project-media">

<video
class="project-video-micro"
autoplay
muted
loop
playsinline>

<source
src="{{ site.url }}{{ site.baseurl }}/videos/projects/microrobot.mp4"
type="video/mp4">

</video>

</div>

<div class="project-content">


<!-- <p class="project-summary">

Development of magnetic microrobotic systems capable of precise
navigation in complex biological environments for localized
medical intervention and targeted therapeutic delivery.

</p> -->



<ul class="project-details">
<li>Magnetically actuated microrobotic system for precise navigation in complex biological environments</li>
<li>Adaptive soft-hinged design enabling controllable gait modulation under external fields</li>
<li>Real-time dynamic modeling to predict and compensate stochastic microscale motion</li>
<li>pH-responsive drug delivery for localized and targeted therapeutic release</li>
<li>Bio-inspired control strategies for reliable microrobot guidance in fluid environments</li>
</ul>

</div>

</div>

<div class="project-publications">

<h4 class="pub-section-title">
Selected Publications
</h4>

<div class="publication-list">

{% bibliography --query @*[keywords~=microrobot] %}

</div>

</div>

</div>

<!-- --- -->

## Automatic Control

<div class="project-card">

<div class="project-content">

<ul class="project-details">
<li>Advanced control strategies for robotic and mechatronic systems</li>
<li>Model-based system identification and control synthesis</li>
<li>Adaptive and robust control for uncertain and time-varying dynamics</li>
</ul>

</div>


<div class="project-publications">

<h4 class="pub-section-title">
Selected Publications
</h4>

<div class="publication-list">

{% bibliography --query @*[keywords~=control] %}

</div>

</div>

</div>

---


## Intelligent Sensing Systems

<div class="project-card">

<div class="project-content">

<ul class="project-details">
<li>Flexible sensing platforms</li>
<li>Reconfigurable manipulation interfaces</li>
<li>Reactive material systems</li>
</ul>

</div>


<div class="project-publications">

<h4 class="pub-section-title">
Selected Publications
</h4>

<div class="publication-list">

{% bibliography --query @*[keywords~=others] %}

</div>

</div>

</div>

---