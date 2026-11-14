---
layout: page
title: News
permalink: /news/
---

{% assign news_items = site.data.news.items | sort: "date" | reverse %}

<div class="news-list">

{% assign current_year = "" %}
{% for item in news_items %}
  {% assign item_year = item.date %}
  {% if item_year != current_year %}
    {% if current_year != "" %}
      </div>
    </section>
    {% endif %}
    <section class="news-year">
      <h2 class="news-year-title">{{ item_year }}</h2>
      <div class="news-year-items">
    {% assign current_year = item_year %}
  {% endif %}

    <article class="news-entry">
      <div class="news-entry-heading">
        {% if item.url and item.url != "" %}
          <strong><a href="{{ item.url }}" target="_blank" rel="noopener noreferrer">{{ item.title }}</a></strong>
        {% else %}
          <strong>{{ item.title }}</strong>
        {% endif %}
        {% if item.category and item.category != "" %}
          <span class="news-category">{{ item.category }}</span>
        {% endif %}
      </div>
      {% if item.summary and item.summary != "" %}
        <p class="news-summary">{{ item.summary }}</p>
      {% endif %}
    </article>

{% endfor %}
{% if current_year != "" %}
      </div>
    </section>
{% endif %}

</div>

<style>
.news-list {
  max-width: 920px;
  margin: auto;
}

.news-year {
  margin: 24px 0 30px;
}

.news-year-title {
  margin: 0 0 4px;
  padding-bottom: 7px;
  border-bottom: 1px solid var(--teal-border);
  color: var(--teal-950);
  font-size: 1.45rem;
  font-weight: 700;
}

.news-year-items {
  display: grid;
}

.news-entry {
  padding: 10px 0;
  border-bottom: 1px solid var(--teal-border);
}

.news-entry-heading {
  display: flex;
  flex-wrap: wrap;
  align-items: baseline;
  gap: 5px 10px;
  line-height: 1.45;
}

.news-category {
  padding: 1px 6px;
  border: 1px solid var(--teal-border);
  border-radius: 3px;
  background: var(--teal-50);
  color: var(--teal-muted);
  font-size: 0.75rem;
  text-transform: capitalize;
}

.news-summary {
  margin: 3px 0 0;
  color: var(--teal-muted);
  font-size: 0.93rem;
  line-height: 1.5;
}

.news-entry a {
  color: var(--teal-800);
  text-decoration: none !important;
}

.news-entry a:hover,
.news-entry a:focus-visible {
  text-decoration: underline !important;
}
</style>