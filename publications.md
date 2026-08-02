---
layout: single
title: "Publications & Presentations"
permalink: /publications/
author_profile: true
---

{%- assign scholar_base = "https://scholar.google.com/scholar?q=" -%}

<h2>Journal Articles</h2>
<ul class="cite-list">
{%- for p in site.data.publications.articles %}
  <li style="padding:10px 0; border-bottom:1px solid #e5e7eb;">
    <p style="margin:0; font-size:0.98rem; line-height:1.5;">
      {{ p.authors | replace: "Rachwalski, A.", "<strong>Rachwalski, A.</strong>" }} ({{ p.year }}).
      <a href="{{ scholar_base }}{{ p.title | url_encode }}" target="_blank" rel="noopener">{{ p.title }}</a>.
      <em>{{ p.venue }}</em>.
      {%- if p.doi %} <a href="https://doi.org/{{ p.doi }}" target="_blank" rel="noopener" style="font-size:0.85rem; color:#6b7280;">doi:{{ p.doi }}</a>{% endif %}
    </p>
  </li>
{%- endfor %}
</ul>

<h2 style="margin-top:28px;">Book Chapters</h2>
<ul class="cite-list">
{%- for p in site.data.publications.chapters %}
  <li style="padding:10px 0; border-bottom:1px solid #e5e7eb;">
    <p style="margin:0; font-size:0.98rem; line-height:1.5;">
      {{ p.authors | replace: "Rachwalski, A.", "<strong>Rachwalski, A.</strong>" }} ({{ p.year }}).
      <a href="{{ scholar_base }}{{ p.title | url_encode }}" target="_blank" rel="noopener">{{ p.title }}</a>.
      {{ p.venue }}.
    </p>
  </li>
{%- endfor %}
</ul>

<h2 style="margin-top:28px;">Work Under Review</h2>
<ul class="cite-list">
{%- for p in site.data.publications.under_review %}
  <li style="padding:10px 0; border-bottom:1px solid #e5e7eb;">
    <p style="margin:0; font-size:0.98rem; line-height:1.5;">
      {{ p.authors | replace: "Rachwalski, A.", "<strong>Rachwalski, A.</strong>" }}.
      {{ p.title }}.
      <em>{{ p.venue }}</em>.
    </p>
  </li>
{%- endfor %}
</ul>

<h2 style="margin-top:28px;">Other Contributions & Policy Reports</h2>
<ul class="cite-list">
{%- for p in site.data.publications.other_contributions %}
  <li style="padding:10px 0; border-bottom:1px solid #e5e7eb;">
    <p style="margin:0; font-size:0.98rem; line-height:1.5;">
      {{ p.authors | replace: "Rachwalski, A.", "<strong>Rachwalski, A.</strong>" }} ({{ p.year }}).
      {%- if p.url %} <a href="{{ p.url }}" target="_blank" rel="noopener">{{ p.title }}</a>.{% else %} {{ p.title }}.{% endif %}
      {{ p.venue }}.
      {%- if p.note %} <span style="color:#6b7280; font-style:italic;">({{ p.note }})</span>{% endif %}
    </p>
  </li>
{%- endfor %}
</ul>

<h2 style="margin-top:28px;">Conference & Research Presentations</h2>

<div class="cite-list">
  
  <!-- CURO Symposium 2026 -->
  <div class="pres-item">
    <div class="pres-img-wrapper">
      <img src="{{ '/images/pres_curo.jpg' | relative_url }}" alt="CURO Research Symposium Presentation">
    </div>
    <div class="pres-text">
      <p style="margin:0; font-size:0.96rem; line-height:1.5;">
        <strong>Rachwalski, A.</strong> (2026).
        READINESS for an Economic Downturn: Building Legislative Crisis Management Capacity.
        <em><a href="https://curo.uga.edu/symposium/" target="_blank" rel="noopener">UGA CURO Symposium</a></em>, Athens, GA.
      </p>
    </div>
  </div>

  <!-- SPIA Undergrad Colloquium 2026 -->
  <div class="pres-item">
    <div class="pres-img-wrapper">
      <img src="{{ '/images/pres_spia_symposium.jpg' | relative_url }}" alt="SPIA Undergraduate Research Colloquium">
    </div>
    <div class="pres-text">
      <p style="margin:0; font-size:0.96rem; line-height:1.5;">
        <strong>Rachwalski, A.</strong> (2026).
        READINESS for an Economic Downturn: Building Legislative Crisis Management Capacity.
        <em><a href="https://spia.uga.edu/news-events/signature-events/undergraduate-research-colloquium/" target="_blank" rel="noopener">SPIA Undergraduate Research Colloquium</a></em>, Athens, GA.
      </p>
    </div>
  </div>

  <!-- Georgia State Capitol Poster & Testimony 2026 -->
  <div class="pres-item">
    <div class="pres-img-wrapper">
      <img src="{{ '/images/pres_capitol_cspan.jpg' | relative_url }}" alt="Georgia Capitol Legislative Testimony">
    </div>
    <div class="pres-text">
      <p style="margin:0; font-size:0.96rem; line-height:1.5;">
        <strong>Rachwalski, A.</strong> (2026).
        READINESS for an Economic Downturn: Building Legislative Crisis Management Capacity.
        <em>Poster Presentation & Committee Testimony, Georgia State Capitol</em>, Atlanta, GA.
      </p>
    </div>
  </div>

  <!-- GRAIL Research Panel -->
  <div class="pres-item">
    <div class="pres-img-wrapper">
      <img src="{{ '/images/pres_grail_panel.jpg' | relative_url }}" alt="GRAIL Panel Presentation">
    </div>
    <div class="pres-text">
      <p style="margin:0; font-size:0.96rem; line-height:1.5;">
        Shivers, B. N., Flaker, L., Kirkpatrick, K., <strong>Rachwalski, A.</strong>, Wang, Y., Jin, Y., Anton, A., Ravazzani, S., van der Meer, T. G. L. A., & Coombs, W. T. (2026).
        Organizational GenAI Culture: Catalysts and Constraints for Crisis READINESS.
        <em>GRAIL Research Panel & Crisis Insights Analytics Lab</em>, Athens, GA.
      </p>
    </div>
  </div>

  <!-- SVIC Recognition Poster -->
  <div class="pres-item">
    <div class="pres-img-wrapper">
      <img src="{{ '/images/pres_spia_poster.jpg' | relative_url }}" alt="SVIC Recognition in Africa Poster Presentation">
    </div>
    <div class="pres-text">
      <p style="margin:0; font-size:0.96rem; line-height:1.5;">
        Duffy, A., <strong>Rachwalski, A.</strong>, Zeitlin, D., Handa, S., & Cohen, J. (2025).
        Combating Conflict: SVIC Recognition in Africa.
        <em>Women and World Politics Symposium, Richard B. Russell Library Gallery</em>, Athens, GA.
      </p>
    </div>
  </div>

  <!-- CVIOG Presentation -->
  <div class="pres-item">
    <div class="pres-img-wrapper">
      <img src="{{ '/images/pres_cviog.jpg' | relative_url }}" alt="CVIOG Internship Presentation">
    </div>
    <div class="pres-text">
      <p style="margin:0; font-size:0.96rem; line-height:1.5;">
        <strong>Rachwalski, A.</strong> (2025).
        Workforce & Economic Development Benchmarking Strategy: Middle Flint & Marion County.
        <em>Carl Vinson Institute of Government</em>, Athens, GA.
      </p>
    </div>
  </div>

  <!-- Stanford GSB Summit -->
  <div class="pres-item">
    <div class="pres-img-wrapper">
      <img src="{{ '/images/pres_stanford_gsb.jpg' | relative_url }}" alt="Stanford GSB Certificate Presentation">
    </div>
    <div class="pres-text">
      <p style="margin:0; font-size:0.96rem; line-height:1.5;">
        <strong>Rachwalski, A.</strong> (2026).
        Summit@Stanford Graduate School of Business Program.
        <em>Stanford Graduate School of Business</em>, Stanford, CA.
      </p>
    </div>
  </div>

  <!-- Tim Coombs & Crisis Comms -->
  <div class="pres-item">
    <div class="pres-img-wrapper">
      <img src="{{ '/images/pres_tim_coombs.jpg' | relative_url }}" alt="With W. Timothy Coombs">
    </div>
    <div class="pres-text">
      <p style="margin:0; font-size:0.96rem; line-height:1.5;">
        Ravazzani, S., Jin, Y., Conti, S., <strong>Rachwalski, A.</strong>, Robinson, S., & Mazzei, A. (2023–2024).
        Seeking Social Change from the Inside Out: Employee Activism & Crisis Management.
        <em>7th International Crisis Communication Conference & ICA</em>, Gothenburg, Sweden & Sydney, Australia.
      </p>
    </div>
  </div>

</div>
