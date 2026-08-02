---
layout: single
title: "Misc & Beyond the Lab"
permalink: /misc/
author_profile: true
---

<h2>Academic & Community Service</h2>
<ul style="list-style:none; padding:0; margin:0 0 24px;">
{%- for s in site.data.service %}
  <li style="padding:6px 0; border-bottom:1px solid #f3f4f6; font-size:0.95rem;">
    <strong>{{ s.role }}</strong>, {{ s.org }} ({{ s.year }})
  </li>
{%- endfor %}
</ul>

<h2 style="margin-top:24px;">Skills & Software</h2>
<ul style="list-style:none; padding:0; margin:0 0 24px;">
  <li style="padding:6px 0; border-bottom:1px solid #f3f4f6; font-size:0.95rem;">
    <strong>Programming & Econometrics:</strong> R (advanced modeling & web scraping); Stata, Python (data analysis & ML); LaTeX, Git, SQL, Excel
  </li>
  <li style="padding:6px 0; border-bottom:1px solid #f3f4f6; font-size:0.95rem;">
    <strong>Financial & Policy Databases:</strong> Bloomberg Terminal/Law, LSEG Refinitiv, FRED, SEC EDGAR, Qualtrics, REDCap
  </li>
</ul>

<h2 style="margin-top:24px;">Global Experience & Interests</h2>
<ul style="list-style:none; padding:0; margin:0 0 24px;">
  <li style="padding:6px 0; border-bottom:1px solid #f3f4f6; font-size:0.95rem;">
    <strong>Study Abroad & Travel:</strong> University of Oxford (Keble College); Scotland, Australia, New Zealand, Fiji, South Korea, Morocco, Netherlands
  </li>
  <li style="padding:6px 0; border-bottom:1px solid #f3f4f6; font-size:0.95rem;">
    <strong>Personal Interests:</strong> Yoga, Georgia Bulldogs college football, art museums, alternative & rock music, political history
  </li>
</ul>

<h2 style="margin-top:28px;">Photo Gallery</h2>

<div class="photo-gallery-grid">
  
  <div class="gallery-card">
    <div class="gallery-img-container">
      <img src="{{ '/images/misc_graduation.jpg' | relative_url }}" alt="Graduation Day">
    </div>
    <div class="gallery-caption">
      <h3 class="gallery-title">Graduation Day</h3>
      <p class="gallery-desc">Graduating Phi Beta Kappa & Magna Cum Laude from UGA Morehead Honors College.</p>
    </div>
  </div>

  <div class="gallery-card">
    <div class="gallery-img-container">
      <img src="{{ '/images/misc_presidential_scholar.jpg' | relative_url }}" alt="With UGA President Jere Morehead">
    </div>
    <div class="gallery-caption">
      <h3 class="gallery-title">Presidential Award of Excellence</h3>
      <p class="gallery-desc">With UGA President Jere W. Morehead as a Presidential Award recipient.</p>
    </div>
  </div>

  <div class="gallery-card">
    <div class="gallery-img-container">
      <img src="{{ '/images/misc_bluekey.jpg' | relative_url }}" alt="Blue Key Honor Society">
    </div>
    <div class="gallery-caption">
      <h3 class="gallery-title">Blue Key Honor Society</h3>
      <p class="gallery-desc">Inducted into the Blue Key Honor Society at the University of Georgia.</p>
    </div>
  </div>

  <div class="gallery-card">
    <div class="gallery-img-container">
      <img src="{{ '/images/misc_uga_arch.jpg' | relative_url }}" alt="The UGA Arch">
    </div>
    <div class="gallery-caption">
      <h3 class="gallery-title">The UGA Arch</h3>
      <p class="gallery-desc">Standing under the historic UGA Arch on North Campus.</p>
    </div>
  </div>

  <div class="gallery-card">
    <div class="gallery-img-container">
      <img src="{{ '/images/misc_uga_mascot.jpg' | relative_url }}" alt="With Uga the Bulldog">
    </div>
    <div class="gallery-caption">
      <h3 class="gallery-title">With Uga the Bulldog</h3>
      <p class="gallery-desc">Meeting Georgia's official mascot, Uga, before a home game in Athens!</p>
    </div>
  </div>

  <div class="gallery-card">
    <div class="gallery-img-container">
      <img src="{{ '/images/misc_laocoon.jpg' | relative_url }}" alt="Vatican Museums">
    </div>
    <div class="gallery-caption">
      <h3 class="gallery-title">Vatican Museums</h3>
      <p class="gallery-desc">Exploring art history in front of the Laocoön statue in Rome.</p>
    </div>
  </div>

  <div class="gallery-card">
    <div class="gallery-img-container">
      <img src="{{ '/images/pres_capitol_floor.jpg' | relative_url }}" alt="Georgia House Chamber Floor">
    </div>
    <div class="gallery-caption">
      <h3 class="gallery-title">Georgia State Capitol</h3>
      <p class="gallery-desc">On the chamber floor of the Georgia House of Representatives.</p>
    </div>
  </div>

  <div class="gallery-card">
    <div class="gallery-img-container">
      <img src="{{ '/images/misc_presidential_luncheon.jpg' | relative_url }}" alt="Presidential Honors Week Luncheon">
    </div>
    <div class="gallery-caption">
      <h3 class="gallery-title">Presidential Honors Week</h3>
      <p class="gallery-desc">Honored at the UGA Presidential Honors Week Luncheon.</p>
    </div>
  </div>

</div>
