---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
---

<h2>Course Papers & Research Projects</h2>

<ul style="list-style:none; padding:0; margin:0;">
{%- for p in site.data.publications.course_papers %}
  <li style="padding:12px 0; border-bottom:1px solid #e5e7eb;">
    <p style="margin:0; font-size:0.98rem; line-height:1.5;">
      <strong>{{ p.title }}</strong> ({{ p.year }}).
      {{ p.description }}
      {%- if p.status %} <strong>{{ p.status }}</strong>{% endif %}
      <em>{{ p.course }}</em>.
    </p>
  </li>
{%- endfor %}
</ul>
