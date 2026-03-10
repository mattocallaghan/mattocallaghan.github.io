---
permalink: /
title: ""
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<div class="profile-summary">
  <img src="{{ '/images/profile.png' | relative_url }}" alt="Matthew O'Callaghan portrait" />
  <div class="profile-summary__content">
    <h2>Matthew O'Callaghan</h2>
    <p class="profile-affiliation">Astronomer · Postdoctoral Researcher · University of Cambridge</p>
    <div class="profile-links">
      {% if site.author.googlescholar %}
        <a href="{{ site.author.googlescholar }}" aria-label="Google Scholar">
          <i class="ai ai-google-scholar ai-fw" aria-hidden="true"></i> Google Scholar
        </a>
      {% endif %}
      {% if site.author.nasaads %}
        <a href="{{ site.author.nasaads }}" aria-label="NASA ADS">
          <i class="fas fa-fw fa-book-open" aria-hidden="true"></i> NASA ADS
        </a>
      {% endif %}
      {% if site.author.arxiv %}
        <a href="{{ site.author.arxiv }}" aria-label="arXiv">
          <i class="ai ai-arxiv ai-fw" aria-hidden="true"></i> arXiv
        </a>
      {% endif %}
      {% if site.author.github %}
        <a href="https://github.com/{{ site.author.github }}" aria-label="GitHub">
          <i class="fab fa-fw fa-github" aria-hidden="true"></i> GitHub
        </a>
      {% endif %}
      {% assign linkedin_link = site.author.linkedin_url %}
      {% if linkedin_link == nil or linkedin_link == "" %}
        {% if site.author.linkedin %}
          {% assign linkedin_link = "https://www.linkedin.com/in/" | append: site.author.linkedin | append: "/" %}
        {% endif %}
      {% endif %}
      {% if linkedin_link and linkedin_link != "" %}
        <a href="{{ linkedin_link }}" aria-label="LinkedIn">
          <i class="fab fa-fw fa-linkedin" aria-hidden="true"></i> LinkedIn
        </a>
      {% endif %}
      <a href="mailto:mo503@cam.ac.uk" aria-label="email Matthew O'Callaghan">
        <i class="fas fa-fw fa-envelope" aria-hidden="true"></i> mo503@cam.ac.uk
      </a>
    </div>
  </div>
</div>

<div class="research-grid">
  <article class="research-card">
    <h3>Dust Mapping and Stellar Parameter Inference</h3>
    <p>
      Data-driven extinction and reddening inference from Gaia distances and photometric surveys, with probabilistic
      modeling of intrinsic colors to recover robust stellar and dust posteriors.
    </p>
  </article>
  <article class="research-card">
    <h3>Robust Simulation-Based Inference</h3>
    <p>
      Methods that remain reliable under simulator misspecification, with careful summary-statistic learning and
      posterior calibration to bridge simulation and observation.
    </p>
  </article>
  <article class="research-card">
    <h3>Supernovae Cosmology</h3>
    <p>
      Using BayeSN in lensing-aware inference pipelines to constrain cosmological parameters, including <em>H</em><sub>0</sub>,
      from Type Ia supernova observations.
    </p>
  </article>
</div>

<section class="timeline-block">
  <h3>Timeline</h3>
  <ul class="timeline-list">
    <li>
      <span class="timeline-year">Sep 2026</span>
      <p>I have accepted an offer to work at the Centre for Astrophysics | Harvard & Smithsonian with Catherine Zucker, where I will be looking at stellar paramter and dust inference for Nasa's Nancy Grace Roman Space Telescope.</p>
    </li>
    <li>
      <span class="timeline-year">Feb 2026</span>
      <p>I have started a postoctoral position at the University of Cambridge working with Kaisey Mandel on infererence for supernovae cosmology.</p>
    </li>
    <li>
      <span class="timeline-year">Nov 2025</span>
      <p>I succesfully defended my thesis at the University of Cambridge!</p>
    </li>
    <li>
      <span class="timeline-year">Nov 2025</span>
      <p>My paper "Data Driven Dust Inference at High Galactic Latitudes using Probabalistic Machine Learning" was accepted for publication at MNRAS.</p>
    </li>
    <li>
      <span class="timeline-year">Dec 2024</span>
      <p>My paper "Quantifying Extinction at High Galactic Latitudes" has been accepted for publication in MNRAS.</p>
    </li>
    <li>
      <span class="timeline-year">Mar 2024</span>
      <p>I have started a six-month research assistant position at the National Observatory in Athens, working on inference for atmospheric dust particles.</p>
    </li>
    <li>
      <span class="timeline-year">Mar 2022</span>
      <p>I have been awarded the Loyds Exhebition Prize and Gold Medal from Trinity College Dublin.</p>
    </li>
    <li>
      <span class="timeline-year">Oct 2021</span>
      <p>I have started my PhD in Astronomy and Data Intensive Sciences as a Gianna Angelopoulous Science and Innovation Scholar at the University of Cambridge, where I will be working with Gerry Gilmore and Kaisey Mandel.</p>
    </li>
    <li>
      <span class="timeline-year">Jul 2021</span>
      <p>I have graduated from the Part III MASt in Mathematics at the University of Cambridge.</p>
    </li>
    <li>
      <span class="timeline-year">Nov 2020</span>
      <p>Graduated with B.A. in Mathematics from Trinity College Dublin.</p>
    </li>
  </ul>
</section>
