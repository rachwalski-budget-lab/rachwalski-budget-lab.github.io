---
layout: single
title: "Experience"
permalink: /experience/
author_profile: true
---

<div class="cv-list" style="border-left: 2px solid #e5e7eb; padding-left: 20px; margin-top: 16px;">
{%- for r in site.data.research %}
  <div style="margin-bottom: 24px; position: relative;">
    <div style="font-size: 1.05rem; font-weight: 600; color: #111827;">
      {{ r.role }}
      {%- if r.advisor %} <span style="font-weight: 400; color: #6b7280; font-size: 0.9rem;">(Advisor: {{ r.advisor }})</span>{% endif %}
    </div>
    <div style="font-size: 0.95rem; color: #1e3a8a; font-weight: 500;">{{ r.org }}</div>
    <div style="font-size: 0.8rem; font-weight: 600; text-transform: uppercase; color: #6b7280; margin: 2px 0 6px;">{{ r.dates }}{% if r.location %} &bull; {{ r.location }}{% endif %}</div>
    <div style="font-size: 0.94rem; color: #374151; line-height: 1.55;">{{ r.detail }}</div>
  </div>
{%- endfor %}
</div>
