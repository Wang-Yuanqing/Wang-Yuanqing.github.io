---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<section id="about-me" class="home-section about-section">
  <h1>About Me</h1>
  <div class="about-text">
    <p>
      Hi there! I am Yuanqing Wang (王源清), and I also go by Yuan.
      I am a Mathematics PhD student at
      <a href="https://cs.utdallas.edu/583/president-determined-for-utd-to-reach-tier-one/" target="_blank" rel="noopener">The University of Texas at Dallas</a>,
      advised by
      <a href="https://personal.utdallas.edu/~bxc190014/" target="_blank" rel="noopener">Professor Baris Coskunuzer</a>.
    </p>
    <p>
      My research focuses on post-training for long-horizon LLM agents, particularly agentic
      reinforcement learning, credit assignment, and self-improving agents.
    </p>
    <p>
      Before coming to UT Dallas, I received my M.S. in Mathematics from
      <a href="https://en.wikipedia.org/wiki/Capital_Normal_University" target="_blank" rel="noopener">Capital Normal University</a>
      and my B.S. in Information and Computational Science from
      <a href="https://en.wikipedia.org/wiki/Xiamen_University" target="_blank" rel="noopener">Xiamen University</a>.
    </p>
    <p>
      <strong>I am actively seeking internship opportunities</strong> and would be happy to connect with researchers and teams working on related problems. Please feel free to reach out!
    </p>
  </div>
</section>

<section id="news" class="home-section news-section">
  <h1>News</h1>
  <div class="news-scroll" role="region" aria-label="Recent news" tabindex="0">
    <ul>
      <li>
        <span class="news-date">2026.08</span>
        <span class="news-content">Co-first-author paper dwDPO accepted to <strong>EMNLP 2026 Main</strong>, and Skill-CDPO accepted to <strong>EMNLP 2026 Findings</strong>.</span>
      </li>
    </ul>
  </div>
</section>

<section id="publications" class="home-section publications-section">
  <h1>Publications</h1>
  <div class="publication-list">
    <article class="publication-card">
      <figure class="publication-image">
        <img src="{{ '/images/publications/dwdpo.jpg' | relative_url }}" alt="dwDPO teaser" onerror="this.parentElement.classList.add('is-missing'); this.remove();">
        <span class="publication-image-fallback">Image pending</span>
      </figure>
      <div class="publication-body">
        <h2>dwDPO: Training Multi-Turn LLM Agents via Divergence-Weighted Direct Preference Optimization</h2>
      <p class="publication-authors">
  Jinghao Lin<sup>*</sup>, Yuhang Wu<sup>*</sup>, 
  <strong><em>Yuanqing Wang</em></strong><sup>*</sup>, 
  Yuchen Li, Kangtianxingjian, 
  Baris Coskunuzer<sup>†</sup>, Xiawu Zheng<sup>†</sup>
</p>
        <p class="publication-venue">EMNLP 2026 Main</p>
        <p class="publication-summary">Uses implicit rewards to pinpoint the critical steps in long-horizon agent trajectories, then weights each step by a principled measure of how much it mattered. The weighting is cheap and drop-in, and gives stable gains over standard DPO across six benchmarks.</p>
      </div>
    </article>

    <article class="publication-card">
      <figure class="publication-image">
        <img src="{{ '/images/publications/skill-cdpo.png' | relative_url }}" alt="Skill-CDPO teaser" onerror="this.parentElement.classList.add('is-missing'); this.remove();">
        <span class="publication-image-fallback">Image pending</span>
      </figure>
      <div class="publication-body">
        <h2>Skill-CDPO: Evolving Agent Tool-Use via Critical Step Preference Optimization</h2>
        <p class="publication-authors">Yuchen Li, Jinghao Lin, <strong><em>Yuanqing Wang</em></strong></p>
        <p class="publication-venue">EMNLP 2026 Findings</p>
        <p class="publication-summary">Finds where an agent's tool use breaks down by comparing expert and local rollouts, then builds preference pairs weighted by step criticality and score gap. An 8B model trained this way matches or beats GPT-5.2 on medical agent benchmarks.</p>
      </div>
    </article>

    <article class="publication-card">
      <figure class="publication-image">
        <img src="{{ '/images/publications/avsg.jpg' | relative_url }}" alt="AVSG teaser" onerror="this.parentElement.classList.add('is-missing'); this.remove();">
        <span class="publication-image-fallback">Image pending</span>
      </figure>
      <div class="publication-body">
        <h2>AVSG: Audio–Visual Scene Graphs Measure What Omni-Modal Models Actually Hear</h2>
        <p class="publication-authors"><strong><em>Yuanqing Wang</em></strong>, Shijian Deng, Baris Coskunuzer<sup>†</sup>, Yapeng Tian<sup>†</sup></p>
        <p class="publication-venue">In submission</p>
      </div>
    </article>

    <article class="publication-card">
      <figure class="publication-image">
        <img src="{{ '/images/publications/heat-field-signatures.jpg' | relative_url }}" alt="Heat Field Signatures teaser" onerror="this.parentElement.classList.add('is-missing'); this.remove();">
        <span class="publication-image-fallback">Image pending</span>
      </figure>
      <div class="publication-body">
        <h2>Heat Field Signatures: Density-Aware Geometry for Point Cloud Classification</h2>
        <p class="publication-authors"><strong><em>Yuanqing Wang</em></strong>, Baris Coskunuzer<sup>†</sup></p>
        <p class="publication-venue">In submission</p>
      </div>
    </article>
  </div>
</section>

<section id="education" class="home-section education-section" markdown="1">

# Education

- *2024.08 - Present*, **The University of Texas at Dallas, Richardson, TX**<br>
  PhD Student in Mathematics

- *2021.09 - 2024.06*, **Capital Normal University, Beijing, China**<br>
  M.S. in Mathematics<br>
  Master's thesis: Notes on Calabi Conjecture and Kähler–Einstein Metric — <a href="{{ '/files/Master_thesis.pdf' | relative_url }}" target="_blank" rel="noopener">English</a> · <a href="{{ '/files/Master_thesis_Chinese.pdf' | relative_url }}" target="_blank" rel="noopener">中文</a>

- *2016.09 - 2021.06*, **Xiamen University, Xiamen, China**<br>
  B.S. in Information and Computational Science (Elite Students' Program)

</section>

<section id="experience" class="home-section experience-section" markdown="1">

# Experience

- *2021.06 - 2021.08*, **Gathssen Investment Co., Ltd., Shenzhen, China**<br>
  Quantitative Strategy Developer Intern

</section>

<footer class="home-footer">
  <p>&copy; 2026 Yuanqing Wang · Last updated: August 2026</p>
  <p>Based on the <a href="https://github.com/RayeRen/acad-homepage.github.io" target="_blank" rel="noopener">AcadHomepage</a> template.</p>
</footer>
