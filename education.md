---
layout: single
title: "Education & Honors"
permalink: /education/
author_profile: true
---

{%- assign d = site.data.education.degree -%}

<div style="margin-bottom: 28px;">
  <h2 style="font-size: 1.3rem; font-weight: 600; margin-bottom: 4px;">{{ d.award }}</h2>
  <div style="font-size: 1.05rem; color: #1e3a8a; font-weight: 600;">{{ d.institution }}</div>
  <div style="font-size: 0.88rem; color: #6b7280; margin-bottom: 10px;">{{ d.dates }} &bull; GPA: {{ d.gpa }}</div>
  {%- if d.honors %}
  <div style="display:flex; flex-wrap:wrap; gap:6px;">
    {%- for h in d.honors %}
    <span style="background:#eff6ff; color:#1e3a8a; border:1px solid #bfdbfe; padding:3px 10px; border-radius:12px; font-size:0.82rem; font-weight:600;">{{ h }}</span>
    {%- endfor %}
  </div>
  {%- endif %}
</div>

{%- if site.data.education.awards.size > 0 %}
<h2 style="font-size: 1.25rem; margin-top:24px; border-bottom:1px solid #e5e7eb; padding-bottom:6px;">Awards & Fellowships</h2>
<ul style="list-style:none; padding:0; margin:0 0 24px;">
  {%- for a in site.data.education.awards %}
  <li style="padding:8px 0; border-bottom:1px solid #f3f4f6; font-size:0.95rem;">
    <strong>{{ a.title }}</strong>{% if a.org %}, {{ a.org }}{% endif %}{% if a.year %} ({{ a.year }}){% endif %}
    {%- if a.note %} <span style="color:#6b7280; font-size:0.88rem;">&bull; {{ a.note }}</span>{% endif %}
  </li>
  {%- endfor %}
</ul>
{%- endif %}

{%- if site.data.education.coursework.size > 0 %}
<h2 style="font-size: 1.25rem; margin-top:24px; border-bottom:1px solid #e5e7eb; padding-bottom:6px;">Relevant Coursework</h2>
{%- for group in site.data.education.coursework %}
<div style="margin-bottom: 14px;">
  <h3 style="font-size:0.92rem; font-weight:600; color:#374151; margin-bottom:6px;">{{ group.category }}</h3>
  <div style="display:flex; flex-wrap:wrap; gap:6px;">
    {%- for c in group.courses %}
    <span style="background:#f3f4f6; color:#374151; border:1px solid #e5e7eb; padding:3px 10px; border-radius:12px; font-size:0.82rem;">{{ c }}</span>
    {%- endfor %}
  </div>
</div>
{%- endfor %}
{%- endif %}
