---
layout: page
permalink: /team/
title: Team
description: Members of the IDMM Lab.
nav: true
nav_order: 2
---

## Principal Investigator

<div class="row mt-3">
  <div class="col-sm-3">
    <img src="{{ '/assets/img/people/kanghyun_lee.jpg' | relative_url }}" 
         alt="Kang-Hyun Lee" class="img-fluid rounded">
  </div>
  <div class="col-sm-9">
    <h3 style="margin-top: 0;">Kang-Hyun Lee, Ph.D.</h3>
    <p><em>Assistant Professor, School of Mechanical Engineering</em><br>
    Soongsil University</p>
    <p>📧 <a href="mailto:kanghyun.lee@ssu.ac.kr">kanghyun.lee@ssu.ac.kr</a></p>
    <p>
      Kang-Hyun Lee is an Assistant Professor in the School of 
      Mechanical Engineering at Soongsil University. Prior to joining 
      Soongsil, he worked as a Postdoctoral Associate in the Department 
      of Mechanical Engineering at the Massachusetts Institute of 
      Technology, where he contributed to a DARPA-funded research 
      project on developing generative artificial intelligence for the 
      design and manufacturing of reusable rocket components.
    </p>
    <p>
      He received his Ph.D. and M.S. from the Department of Aerospace 
      Engineering at Seoul National University, with a research focus 
      on multiphysics and multiscale simulation of metal additive 
      manufacturing processes. His current research lies at the 
      intersection of generative design and advanced manufacturing, 
      aiming to unlock the full potential of manufacturing processes 
      and expand the design space for next-generation engineered 
      systems.
    </p>
  </div>
</div>

---

## Graduate Students

<div class="row mt-3">
{% for member in site.data.members.grad_students %}
  <div class="col-sm-6 col-md-4 mb-4">
    <div class="member-card">
      <img src="{{ member.photo | default: '/assets/img/people/placeholder.jpg' | relative_url }}" 
           alt="{{ member.name }}" 
           class="img-fluid rounded mb-2">
      <h5 style="margin-bottom: 0.2rem;">{{ member.name }}</h5>
      <p style="margin-bottom: 0.3rem;"><em>{{ member.position }}</em></p>
      {% if member.interests %}
        <p style="font-size: 0.9em; color: var(--global-text-color-light);">
          {{ member.interests }}
        </p>
      {% endif %}
      {% if member.email %}
        <p style="font-size: 0.85em;">
          <a href="mailto:{{ member.email }}">{{ member.email }}</a>
        </p>
      {% endif %}
    </div>
  </div>
{% endfor %}
</div>

{% if site.data.members.grad_students.size == 0 %}
<p><em>We are actively recruiting — see <a href="/#join-us">Join Us</a>.</em></p>
{% endif %}

---

## Undergraduate Researchers

{% if site.data.members.undergrads and site.data.members.undergrads.size > 0 %}
<div class="row mt-3">
{% for member in site.data.members.undergrads %}
  <div class="col-sm-6 col-md-4 mb-3">
    <strong>{{ member.name }}</strong><br>
    <em>{{ member.position }}</em>
    {% if member.interests %}<br><small>{{ member.interests }}</small>{% endif %}
  </div>
{% endfor %}
</div>
{% else %}
<p><em>Open positions. Motivated undergraduates are welcome to contact Prof. Lee.</em></p>
{% endif %}

---

## Alumni

{% if site.data.members.alumni and site.data.members.alumni.size > 0 %}
<ul>
{% for member in site.data.members.alumni %}
  <li>
    <strong>{{ member.name }}</strong> — {{ member.degree }} ({{ member.year }})
    {% if member.next %}→ <em>{{ member.next }}</em>{% endif %}
  </li>
{% endfor %}
</ul>
{% else %}
<p><em>This section will be updated as members graduate.</em></p>
{% endif %}

---

## Join Us

We are **actively recruiting** M.S., Ph.D., and undergraduate researchers.
If you are interested in working at the intersection of generative
design, additive manufacturing, and physics-based machine learning,
please email Prof. Lee with:

1. Your CV / transcript
2. A short paragraph (a few sentences) on your research interests and
   why IDMM Lab
3. (Optional) Any prior project, code, or writing you would like us
   to look at

📧 **kanghyun.lee@ssu.ac.kr**
