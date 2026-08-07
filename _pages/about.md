---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<section id="about-me" class="home-section about-section">
  <h1>About Me</h1>
  <div class="about-text">
    <p>
      Hi there! I am a Mathematics PhD student at
      <a href="https://www.utdallas.edu/" target="_blank" rel="noopener">The University of Texas at Dallas</a>,
      advised by
      <a href="https://personal.utdallas.edu/~bxc190014/" target="_blank" rel="noopener">Professor Baris Coskunuzer</a> (Math)
      and
      <a href="https://www.yapengtian.com/" target="_blank" rel="noopener">Professor Yapeng Tian</a> (CS).
      My research focuses on post-training for long-horizon LLM agents, particularly agentic
      reinforcement learning, credit assignment, and self-evolving agents.
    </p>
    <p>
      Before coming to UT Dallas, I received my M.S. in Mathematics from Capital Normal University
      and my B.S. in Computational Mathematics from Xiamen University.
    </p>
  </div>
</section>

<section id="news" class="home-section news-section">
  <h1>News</h1>
  <div class="news-scroll" role="region" aria-label="Recent news" tabindex="0">
    <ul>
      <li>
        <span class="news-date">2026.08</span>
        <span class="news-content">Submitted AVSG, an audio–visual scene graph benchmark for omni-modal models, to ACL ARR.</span>
      </li>
      <li>
        <span class="news-date">2026.05</span>
        <span class="news-content">Awarded the NSM Summer Research Fellowship at UT Dallas.</span>
      </li>
      <li>
        <span class="news-date">2025.08</span>
        <span class="news-content">Started as a Teaching Assistant at UT Dallas for Linear Algebra and Differential Calculus.</span>
      </li>
      <li>
        <span class="news-date">2024.09</span>
        <span class="news-content">Joined UT Dallas as a Mathematics PhD student with the NSM McDermott PhD Admission Fellowship.</span>
      </li>
      <li>
        <span class="news-date">2024.06</span>
        <span class="news-content">Received my M.S. in Mathematics from Capital Normal University.</span>
      </li>
    </ul>
  </div>
</section>

<section id="publications" class="home-section publications-section">
  <h1>Selected Research</h1>
  <p class="pub-note"><em>* indicates equal contribution</em></p>

  <div class="publication-list">
    <article class="publication-card">
      <figure class="publication-image">
        <img src="{{ '/images/publications/dwdpo.png' | relative_url }}" alt="dwDPO teaser" onerror="this.parentElement.classList.add('is-missing'); this.remove();">
        <span class="publication-image-fallback">Image pending</span>
      </figure>
      <div class="publication-body">
        <h2>dwDPO: Training Multi-Turn LLM Agents via Divergence-Weighted Direct Preference Optimization</h2>
        <p class="publication-authors"><strong><em>Yuanqing Wang*</em></strong> (co-first author)</p>
        <p class="publication-venue">EMNLP 2026 (in submission)</p>
      </div>
    </article>

    <article class="publication-card">
      <figure class="publication-image">
        <img src="{{ '/images/publications/skill-cdpo.png' | relative_url }}" alt="Skill-CDPO teaser" onerror="this.parentElement.classList.add('is-missing'); this.remove();">
        <span class="publication-image-fallback">Image pending</span>
      </figure>
      <div class="publication-body">
        <h2>Skill-CDPO: Evolving Agent Tool-Use via Critical Step Preference Optimization</h2>
        <p class="publication-authors"><strong><em>Yuanqing Wang</em></strong></p>
        <p class="publication-venue">EMNLP 2026 (in submission)</p>
      </div>
    </article>

    <article class="publication-card">
      <figure class="publication-image">
        <img src="{{ '/images/publications/avsg.png' | relative_url }}" alt="AVSG teaser" onerror="this.parentElement.classList.add('is-missing'); this.remove();">
        <span class="publication-image-fallback">Image pending</span>
      </figure>
      <div class="publication-body">
        <h2>AVSG: Audio–Visual Scene Graphs Measure What Omni-Modal Models Actually Hear</h2>
        <p class="publication-authors"><strong><em>Yuanqing Wang</em></strong> (first author)</p>
        <p class="publication-venue">ACL ARR 2026 (in submission)</p>
      </div>
    </article>

    <article class="publication-card">
      <figure class="publication-image">
        <img src="{{ '/images/publications/heat-field-signatures.png' | relative_url }}" alt="Heat Field Signatures teaser" onerror="this.parentElement.classList.add('is-missing'); this.remove();">
        <span class="publication-image-fallback">Image pending</span>
      </figure>
      <div class="publication-body">
        <h2>Heat Field Signatures: Density-Aware Geometry for Point Cloud Classification</h2>
        <p class="publication-authors"><strong><em>Yuanqing Wang</em></strong> (first author)</p>
        <p class="publication-venue">ICLR 2027 (to be submitted)</p>
      </div>
    </article>

    <article class="publication-card">
      <figure class="publication-image">
        <img src="{{ '/images/publications/croc.png' | relative_url }}" alt="CROC teaser" onerror="this.parentElement.classList.add('is-missing'); this.remove();">
        <span class="publication-image-fallback">Image pending</span>
      </figure>
      <div class="publication-body">
        <h2>When Do Critics Beat Groups? A Crossover Rule for Credit Assignment in Long-Horizon Agents</h2>
        <p class="publication-authors"><strong><em>Yuanqing Wang</em></strong></p>
        <p class="publication-venue">In progress (ICLR 2027 target)</p>
      </div>
    </article>
  </div>
</section>

<section id="education" class="home-section education-section" markdown="1">

# Education

- *2024.08 - Present*, **The University of Texas at Dallas, Richardson, TX**<br>
  PhD Student in Mathematics

- *2021.09 - 2024.06*, **Capital Normal University, Beijing, China**<br>
  M.S. in Mathematics

- *2016.09 - 2021.06*, **Xiamen University, Xiamen, China**<br>
  B.S. in Computational Mathematics (Elite Students' Program)

</section>

<section id="experience" class="home-section experience-section" markdown="1">

# Experience

- *2025 - 2026*, **The University of Texas at Dallas**<br>
  Teaching Assistant — Linear Algebra, Differential Calculus

- *2023 - 2024*, **Capital Normal University**<br>
  Teaching Assistant — Real Analysis, Complex Analysis

- *2021.06 - 2021.08*, **Gathssen Investment Co., Ltd., Shenzhen, China**<br>
  Quantitative Strategy Developer Intern

</section>

<section id="honors" class="home-section service-section" markdown="1">

# Honors & Awards

- NSM Summer Research Fellowship, UT Dallas (Summer 2026)

- NSM McDermott PhD Admission Fellowship, UT Dallas (2024)

- Excellent Academic Scholarship, Capital Normal University (2022 - 2023)

- China Undergraduate Mathematical Contest in Modeling, 1st Prize, Fujian Province (2018)

- Elite Students' Scholarship, Xiamen University (2018 - 2019)

</section>

<footer class="home-footer">
  <p>&copy; 2026 Yuanqing Wang · Last updated: August 2026</p>
  <p>Based on the <a href="https://github.com/RayeRen/acad-homepage.github.io" target="_blank" rel="noopener">AcadHomepage</a> template.</p>
</footer>
