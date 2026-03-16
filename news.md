---
layout: page
title: News
permalink: /news/
---

{% assign news_items = site.data.news.items | sort: "date" | reverse %}

<div class="news-list">

{% for item in news_items %}

<div class="news-entry">

<span class="news-date">
{{ item.date | date: "%Y %b" }}
</span>

{% if item.category %}
<span class="news-category">
{{ item.category }}
</span>
{% endif %}

<br>
<strong>
<a href="{{ item.url }}" target="_blank">
{{ item.title }}
</a>
</strong>

{% if item.summary %}
<br>
{{ item.summary }}
{% endif %}

</div>

{% endfor %}

</div>

<style>
.news-list {
  max-width: 900px;
  margin: auto;
}

.news-entry {
  padding: 14px 0;
  border-bottom: 1px solid #eee;
  line-height: 1.6;
}

.news-date {
  font-weight: 600;
  color: #666;
  margin-right: 8px;
}

.news-category {
  background: #fff3df;
  color: #b96d00;
  font-size: 0.75rem;
  padding: 3px 8px;
  border-radius: 6px;
  margin-right: 8px;
}

.news-entry a {
  text-decoration: none;
}

.news-entry a:hover {
  text-decoration: underline;
}
</style>