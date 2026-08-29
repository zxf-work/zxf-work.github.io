---
layout: homepage
---
<div id="top"></div>

<section class="hero" aria-labelledby="hero-title">
  <p class="eyebrow">Associate Professor of Computer Science · University of Memphis</p>
  <h1 id="hero-title">Xiaofei Zhang</h1>
  <div class="profile-links" aria-label="Profile links">
    <a href="{{ site.google_scholar }}" target="_blank" rel="noopener" aria-label="Google Scholar" title="Google Scholar">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
        <path d="m3 10 9-5 9 5-9 5-9-5Z"/>
        <path d="M7 12.2v4.3c2.8 2 7.2 2 10 0v-4.3M21 10v6"/>
      </svg>
    </a>
    <a href="{{ site.orcid }}" target="_blank" rel="noopener" aria-label="ORCID" title="ORCID">
      <svg viewBox="0 0 24 24" fill="currentColor" aria-hidden="true">
        <path d="M12 0C5.372 0 0 5.372 0 12s5.372 12 12 12 12-5.372 12-12S18.628 0 12 0ZM7.369 4.945c.705 0 1.277.572 1.277 1.277S8.074 7.5 7.369 7.5a1.278 1.278 0 1 1 0-2.555Zm-.918 4.31h1.836v9.8H6.451v-9.8Zm4.608 0h4.97c3.735 0 5.373 2.668 5.373 4.9 0 2.519-1.967 4.9-5.347 4.9h-4.996v-9.8Zm1.836 1.66v6.48h2.927c3.29 0 3.644-2.498 3.644-3.24 0-1.209-.769-3.24-3.644-3.24h-2.927Z"/>
      </svg>
    </a>
    <a href="{{ site.github_link }}" target="_blank" rel="noopener" aria-label="GitHub" title="GitHub">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
        <path d="M15 22v-4a4.8 4.8 0 0 0-1-3.5c3.28-.36 6.72-1.61 6.72-7.25A5.65 5.65 0 0 0 19.22 3.3 5.3 5.3 0 0 0 19.08.35S17.9 0 15 1.85a13.4 13.4 0 0 0-6 0C6.1 0 4.92.35 4.92.35a5.3 5.3 0 0 0-.14 2.95 5.65 5.65 0 0 0-1.5 3.95c0 5.63 3.44 6.88 6.72 7.25A4.8 4.8 0 0 0 9 18v4"/>
        <path d="M9 19c-3 .92-3-1.5-4.2-2"/>
      </svg>
    </a>
    <a href="mailto:xiaofei.zhang@memphis.edu" aria-label="Email" title="Email">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
        <rect x="3" y="5" width="18" height="14" rx="2"/>
        <path d="m3 7 9 6 9-6"/>
      </svg>
    </a>
  </div>
</section>

<section class="content-section about" aria-labelledby="about-title">
  <div class="section-title">
    <p class="section-kicker">About</p>
    <h2 id="about-title">Data systems for evolving and connected worlds</h2>
  </div>
  <div class="section-body prose">
    <p>I am an Associate Professor in the Department of Computer Science at the University of Memphis, where I direct the Data System Research (DSR) Lab. My research develops scalable data systems for <strong>dynamic, distributed, and graph-structured data</strong>, with current interests in temporal graph systems, federated data services, and reliable AI for data systems.</p>
    <p>I received my Ph.D. from HKUST and was a postdoctoral fellow at the University of Waterloo, CUHK, and HKUST.</p>
  </div>
</section>

<section class="content-section" aria-labelledby="news-title">
  <div class="section-intro compact">
    <div>
      <p class="section-kicker">Updates</p>
      <h2 id="news-title">Recent news</h2>
    </div>
  </div>

  <dl class="news-list">
    <div><dt>Aug 2026</dt><dd>Named a Distinguished Reviewer for the VLDB 2026 conference.</dd></div>
    <div><dt>Aug 2026</dt><dd>Our work <strong>Hawkeye: Seeing One Layer Deeper — A Cohesion-Aware Structural Channel for Temporal Link Prediction</strong>, led by Jiacheng, was accepted as a full research paper at CIKM 2026.</dd></div>
    <div><dt>May 2026</dt><dd>Our work <strong>SAGA: Synthetic Agentic Graph Architecture for Temporal Benchmark Generation</strong>, led by Jiacheng, was accepted to the VLDB 2026 Demonstrations track. We look forward to presenting the demo.</dd></div>
    <div><dt>Apr 2026</dt><dd>Received a Distinguished PC Award from ICDE 2026.</dd></div>
    <div><dt>Jan 2026</dt><dd>Elected a full member of the Sigma Xi Scientific Research Honor Society.</dd></div>
  </dl>
</section>

<section class="content-section publications-section" aria-labelledby="publications">
  <p class="section-kicker">Publications</p>
  {% include_relative _includes/publications.md %}
</section>

<section class="student-callout" id="students" aria-labelledby="students-title">
  <div>
    <p class="section-kicker">Join the group</p>
    <h2 id="students-title">Prospective students</h2>
  </div>
  <div>
    <p>I welcome inquiries from students interested in graph data systems, temporal data management, distributed data services, and reliable AI for databases. Please include a brief description of your research interests and relevant preparation.</p>
    <a class="text-link" href="mailto:xiaofei.zhang@memphis.edu">Get in touch <span aria-hidden="true">→</span></a>
  </div>
</section>
