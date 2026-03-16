---
layout: page
title: Mohammed B. Alshawki
subtitle: Exploring the Future of Trust, Privacy, and Secure Systems
permalink: /
---


<style>
.news-home {
  margin: 2.5rem 0 1rem 0;
}

.news-home-header {
  display: flex;
  justify-content: space-between;
  align-items: end;
  gap: 1rem;
  flex-wrap: wrap;
  margin-bottom: 1rem;
}

.news-home-title {
  margin: 0;
  font-size: 1.7rem;
  font-weight: 800;
}

.news-home-subtitle {
  margin: 0.35rem 0 0 0;
  color: #666;
}

.news-more-link {
  text-decoration: none !important;
  font-weight: 700;
  padding: 0.65rem 1rem;
  border-radius: 12px;
  border: 1px solid #ece7df;
  background: #faf8f4;
}

.news-more-link:hover {
  background: #fff3df;
  border-color: #ffd79a;
}

.news-grid {
  display: grid;
  gap: 16px;
}

.news-card {
  border: 1px solid #ece7df;
  border-left: 5px solid #ffa500;
  border-radius: 18px;
  padding: 16px 18px;
  background: #fff;
  box-shadow: 0 8px 24px rgba(0,0,0,0.05);
  transition: transform 0.18s ease, box-shadow 0.18s ease;
}

.news-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 12px 30px rgba(0,0,0,0.08);
}

.news-meta {
  display: flex;
  gap: 10px;
  flex-wrap: wrap;
  align-items: center;
  margin-bottom: 8px;
}

.news-date {
  color: #666;
  font-size: 0.72rem;
  font-weight: 600;
}

.news-badge {
  display: inline-block;
  padding: 5px 10px;
  border-radius: 888px;
  font-size: 0.7rem;
  font-weight: 500;
  background: #fff3df;
  color: #b96d00;
  border: 1px solid #ffe0ad;
}

.news-badge.featured {
  background: #fff0f0;
  color: #b42318;
  border-color: #ffd3d0;
}

.news-headline {
  margin: 0 0 8px 0;
  font-size: 0.85rem;
  line-height: 1.1;
}

.news-headline a {
  text-decoration: none !important;
}

.news-summary {
  color: #4a4a4a;
  line-height: 1.15;
  margin: 0 0 10px 0;
}

.news-readmore {
  text-decoration: none !important;
  font-weight: 500;
}

@media (max-width: 640px) {
  .news-home-title {
    font-size: 1.05rem;
  }
}
</style>




### Welcome to My Site
I’m Mohammed B. Alshawki, an **Associate Professor** and **Certified Consultant**. I specialize in developing secure protocotol, securing AI-driven systems and critical distributed infrastructures. 
<br>
<a href=aboutme> More about me </a>


<h3 style="margin-bottom:18px;">Explore</h3>

<div id="explore-grid" style="display:grid; grid-template-columns:repeat(3, minmax(0,1fr)); gap:20px;">


<a class="explore-card" href="projects" style="display:block; padding:22px 18px; border:1px solid #e7e1d8; border-radius:16px; background:#fff; text-decoration:none; color:#1e1e1e; min-height:126px;">
<div style="font-size:1.4rem;margin-bottom:10px;">📁</div>
<div style="font-size:1.02rem;font-weight:700;margin-bottom:6px;">Projects</div>
<div style="font-size:0.9rem;color:#555;">Research projects and collaborations.</div>
</a>

<a class="explore-card" href="activities" style="display:block; padding:22px 18px; border:1px solid #e7e1d8; border-radius:16px; background:#fff; text-decoration:none; color:#1e1e1e; min-height:126px;">
<div style="font-size:1.4rem;margin-bottom:10px;">🎤</div>
<div style="font-size:1.02rem;font-weight:700;margin-bottom:6px;">Events &amp; Talks</div>
<div style="font-size:0.9rem;color:#555;">Talks, workshops, and invited events.</div>
</a>

<a class="explore-card" href="supervision" style="display:block; padding:22px 18px; border:1px solid #e7e1d8; border-radius:16px; background:#fff; text-decoration:none; color:#1e1e1e; min-height:126px;">
<div style="font-size:1.4rem;margin-bottom:10px;">🎓</div>
<div style="font-size:1.02rem;font-weight:700;margin-bottom:6px;">Supervision &amp; Teaching</div>
<div style="font-size:0.9rem;color:#555;">Teaching and academic mentoring.</div>
</a>

<a class="explore-card" href="publication" style="display:block; padding:22px 18px; border:1px solid #e7e1d8; border-radius:16px; background:#fff; text-decoration:none; color:#1e1e1e; min-height:126px;">
<div style="font-size:1.4rem;margin-bottom:10px;">📚</div>
<div style="font-size:1.02rem;font-weight:700;margin-bottom:6px;">Publications</div>
<div style="font-size:0.9rem;color:#555;">Papers, articles, and preprints.</div>
</a>

<a class="explore-card" href="opportunities" style="display:block; padding:22px 18px; border:1px solid #e7e1d8; border-radius:16px; background:#fff; text-decoration:none; color:#1e1e1e; min-height:126px;">
<div style="font-size:1.4rem;margin-bottom:10px;">🌱</div>
<div style="font-size:1.02rem;font-weight:700;margin-bottom:6px;">Opportunities</div>
<div style="font-size:0.9rem;color:#555;">Open roles and collaboration opportunities.</div>
</a>

<a class="explore-card" href="achievements" style="display:block; padding:22px 18px; border:1px solid #e7e1d8; border-radius:16px; background:#fff; text-decoration:none; color:#1e1e1e; min-height:126px;">
<div style="font-size:1.4rem;margin-bottom:10px;">🏆</div>
<div style="font-size:1.02rem;font-weight:700;margin-bottom:6px;">Achievements &amp; Grants</div>
<div style="font-size:0.9rem;color:#555;">Awards, grants, and recognitions.</div>
</a>


</div>


{% assign selected_news = site.data.news.items | where: "selected", true | sort: "date" | reverse %}

<section class="news-home">
  <div class="news-home-header">
    <div>
      <h2 class="news-home-title">Selected Recent News</h2>
      <p class="news-home-subtitle">Recent highlights, awards, talks, publications, and updates.</p>
    </div>
    <a class="news-more-link" href="/news/">Read all news →</a>
  </div>

  <div class="news-grid">
    {% for item in selected_news limit: 4 %}
      <article class="news-card">
        <div class="news-meta">
          <span class="news-date">{{ item.date | date: "%Y %b" }}</span>
          {% if item.category and item.category != "" %}
            <span class="news-badge">{{ item.category }}</span>
          {% endif %}
          {% if item.featured %}
            <span class="news-badge featured">Featured</span>
          {% endif %}
        </div>

        <h3 class="news-headline">
          <a href="{{ item.url }}" target="_blank">{{ item.title }}</a>
        </h3>

        {% if item.summary and item.summary != "" %}
          <p class="news-summary">{{ item.summary }}</p>
        {% endif %}

        <a class="news-readmore" href="{{ item.url }}" target="_blank">
          Read more →
        </a>
      </article>
    {% endfor %}
  </div>
</section>




