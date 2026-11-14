---
layout: page
title: Mohammed B. Alshawki
subtitle: Exploring the Future of Trust, Privacy, and Secure Systems
permalink: /
full-width: true
---


<style>
.home-page {
  max-width: 1100px;
  margin: 0 auto;
  color: var(--teal-ink);
}

.home-intro {
  display: grid;
  grid-template-columns: minmax(0, 1.6fr) minmax(260px, 0.9fr);
  gap: 28px;
  align-items: stretch;
  margin: 12px 0 44px;
}

.home-intro-main {
  padding: 26px 0;
}

.home-eyebrow {
  margin: 0 0 9px;
  color: var(--teal-muted);
  font-size: 0.8rem;
  font-weight: 700;
  letter-spacing: 0.08em;
  text-transform: uppercase;
}

.home-intro-title {
  margin: 0 0 14px;
  color: var(--teal-950);
  font-size: 1.75rem;
  font-weight: 700;
  line-height: 1.25;
}

.home-intro-copy {
  max-width: 680px;
  margin: 0;
  color: var(--teal-muted);
  font-size: 1.06rem;
  line-height: 1.75;
}

.home-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 22px;
}

.home-action {
  display: inline-block;
  padding: 8px 13px;
  border: 1px solid var(--teal-800);
  border-radius: 4px;
  color: var(--teal-800) !important;
  font-size: 0.92rem;
  font-weight: 600;
  text-decoration: none !important;
}

.home-action-primary {
  background: var(--teal-800);
  color: #fff !important;
}

.home-action:hover,
.home-action:focus-visible {
  border-color: var(--teal-950);
  background: var(--teal-100);
  color: var(--teal-950) !important;
}

.home-action-primary:hover,
.home-action-primary:focus-visible {
  background: var(--teal-950);
  color: #fff !important;
}

.home-focus {
  align-self: center;
  padding: 20px 22px;
  border: 1px solid var(--teal-border);
  border-radius: 5px;
  background: var(--teal-50);
}

.home-focus-title {
  margin: 0 0 12px;
  color: var(--teal-950);
  font-size: 1rem;
  font-weight: 700;
}

.home-focus-list {
  margin: 0;
  padding: 0;
  list-style: none;
}

.home-focus-list li {
  padding: 8px 0;
  border-top: 1px solid var(--teal-border);
  color: var(--teal-muted);
  font-size: 0.94rem;
}

.home-section {
  margin: 0 0 46px;
}

.home-section-header {
  display: flex;
  justify-content: space-between;
  align-items: end;
  gap: 16px;
  margin-bottom: 16px;
}

.home-section-title {
  margin: 0;
  color: var(--teal-950);
  font-size: 1.45rem;
  font-weight: 700;
}

.home-section-description {
  margin: 5px 0 0;
  color: var(--teal-muted);
  line-height: 1.5;
}

.explore-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 12px;
}

.explore-card {
  display: flex;
  min-height: 112px;
  flex-direction: column;
  padding: 16px 17px;
  border: 1px solid var(--teal-border);
  border-radius: 5px;
  background: #fff;
  color: inherit !important;
  text-decoration: none !important;
  transition: border-color 0.15s ease, background-color 0.15s ease;
}

.explore-card:hover,
.explore-card:focus-visible {
  border-color: var(--teal-500);
  background: var(--teal-50);
}

.explore-card-title {
  margin-bottom: 5px;
  color: var(--teal-800);
  font-size: 1.02rem;
  font-weight: 700;
}

.explore-card-description {
  color: var(--teal-muted);
  font-size: 0.9rem;
  line-height: 1.5;
}

.news-home {
  margin: 0 0 24px;
}

.news-home-header {
  display: flex;
  justify-content: space-between;
  align-items: end;
  gap: 16px;
  margin-bottom: 16px;
}

.news-more-link {
  flex-shrink: 0;
  color: var(--teal-800) !important;
  font-size: 0.92rem;
  font-weight: 600;
  text-decoration: none !important;
}

.news-more-link:hover,
.news-more-link:focus-visible {
  color: var(--teal-950) !important;
  text-decoration: underline !important;
}

.news-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 12px;
}

.news-card {
  padding: 16px 18px;
  border: 1px solid var(--teal-border);
  border-radius: 5px;
  background: #fff;
}

.news-meta {
  display: flex;
  gap: 8px;
  flex-wrap: wrap;
  align-items: center;
  margin-bottom: 8px;
}

.news-date {
  color: var(--teal-muted);
  font-size: 0.8rem;
  font-weight: 600;
}

.news-badge {
  padding: 2px 7px;
  border: 1px solid var(--teal-border);
  border-radius: 3px;
  background: var(--teal-50);
  color: var(--teal-muted);
  font-size: 0.76rem;
  text-transform: capitalize;
}

.news-badge.featured {
  border-color: var(--teal-200);
  background: var(--teal-100);
  color: var(--teal-800);
}

.news-headline {
  margin: 0 0 7px;
  font-size: 1.02rem;
  font-weight: 700;
  line-height: 1.4;
}

.news-headline a {
  color: var(--teal-800);
  text-decoration: none !important;
}

.news-headline a:hover,
.news-headline a:focus-visible {
  text-decoration: underline !important;
}

.news-summary {
  margin: 0 0 9px;
  color: var(--teal-muted);
  font-size: 0.92rem;
  line-height: 1.55;
}

.news-readmore {
  color: var(--teal-800) !important;
  font-size: 0.88rem;
  font-weight: 600;
  text-decoration: none !important;
}

.news-readmore:hover,
.news-readmore:focus-visible {
  text-decoration: underline !important;
}

@media (max-width: 760px) {
  .home-intro {
    grid-template-columns: 1fr;
    gap: 12px;
    margin-bottom: 36px;
  }

  .home-intro-main {
    padding: 12px 0 0;
  }

  .explore-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
}

@media (max-width: 560px) {
  .home-intro-title {
    font-size: 1.5rem;
  }

  .explore-grid,
  .news-grid {
    grid-template-columns: 1fr;
  }

  .home-section-header,
  .news-home-header {
    align-items: flex-start;
  }
}
</style>

<div class="home-page">
  <section class="home-intro" aria-labelledby="home-intro-title">
    <div class="home-intro-main">
      <h2 class="home-intro-title" id="home-intro-title">Research in security, privacy, and trusted systems</h2>
      <p class="home-intro-copy">
        I’m an Associate Professor at ELTE and a Senior Researcher in the Cyber Security and Cryptography Research Group. My work brings together applied cryptography, AI security, and next-generation networks, with a focus on practical, privacy-aware systems.
      </p>
      <div class="home-actions">
        <a class="home-action home-action-primary" href="aboutme">About me</a>
        <a class="home-action" href="contact">Contact</a>
      </div>
    </div>
    <aside class="home-focus" aria-labelledby="home-focus-title">
      <h3 class="home-focus-title" id="home-focus-title">Research areas</h3>
      <ul class="home-focus-list">
        <li>Distributed Systems security</li>
        <li>Federated AI security</li>
        <li>Applied cryptography and PQ security</li>
        <li>Cryptographic protocols</li>
      </ul>
    </aside>
  </section>

  <section class="home-section" aria-labelledby="explore-title">
    <div class="home-section-header">
      <div>
        <h2 class="home-section-title" id="explore-title">Explore</h2>
        <p class="home-section-description">Research, academic activities, and opportunities.</p>
      </div>
    </div>
    <div class="explore-grid">
      <a class="explore-card" href="projects">
        <span class="explore-card-title">Projects</span>
        <span class="explore-card-description">Research projects and collaborations.</span>
      </a>
      <a class="explore-card" href="activities">
        <span class="explore-card-title">Events &amp; Talks</span>
        <span class="explore-card-description">Talks, workshops, and invited events.</span>
      </a>
      <a class="explore-card" href="supervision">
        <span class="explore-card-title">Supervision &amp; Teaching</span>
        <span class="explore-card-description">Teaching and academic mentoring.</span>
      </a>
      <a class="explore-card" href="publication">
        <span class="explore-card-title">Publications</span>
        <span class="explore-card-description">Research papers and selected publications.</span>
      </a>
      <a class="explore-card" href="opportunities">
        <span class="explore-card-title">Opportunities</span>
        <span class="explore-card-description">Open roles and collaboration opportunities.</span>
      </a>
      <a class="explore-card" href="achievements">
        <span class="explore-card-title">Achievements &amp; Grants</span>
        <span class="explore-card-description">Awards, grants, and recognitions.</span>
      </a>
    </div>
  </section>

{% assign selected_news = site.data.news.items | where: "selected", true | sort: "date" | reverse %}

<section class="news-home">
  <div class="news-home-header">
    <div>
      <h2 class="home-section-title">Recent highlights</h2>
      <p class="home-section-description"></p>
    </div>
  </div>

  <div class="news-grid">
    {% for item in selected_news limit: 4 %}
      <article class="news-card">
        <div class="news-meta">
          {% if item.category and item.category != "" %}
            <span class="news-badge">{{ item.category }}</span>
          {% endif %}
          {% if item.featured %}
            <span class="news-badge featured">Featured</span>
          {% endif %}
        </div>

        <h3 class="news-headline">
          {% if item.url and item.url != "" %}
            <a href="{{ item.url }}" target="_blank" rel="noopener noreferrer">{{ item.title }}</a>
          {% else %}
            {{ item.title }}
          {% endif %}
        </h3>

        {% if item.summary and item.summary != "" %}
          <p class="news-summary">{{ item.summary }}</p>
        {% endif %}

        {% if item.url and item.url != "" %}
          <a class="news-readmore" href="{{ item.url }}" target="_blank" rel="noopener noreferrer">Read more <span aria-hidden="true">→</span></a>
        {% endif %}
      </article>
    {% endfor %}
  </div>
</section>
</div>
