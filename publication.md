---
layout: page
title: Publications
subtitle: Building Trust, Resilience, and Security
permalink: /publication/
---

<style>
.pub-page {
  max-width: 980px;
  margin: 0 auto;
}

.pub-legend {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 16px;
  margin: 10px 0 28px;
  padding: 16px 18px;
  border: 1px solid #dfe5eb;
  border-radius: 8px;
  background: #f8fafc;
}

.pub-legend a {
  display: flex;
  align-items: center;
}

.pub-legend img {
  display: block;
  max-width: 150px;
  max-height: 48px;
  object-fit: contain;
}

.pub-list {
  display: grid;
  gap: 14px;
}

.pub-card {
  padding: 18px 20px;
  border: 1px solid #dfe5eb;
  border-left: 4px solid #315b78;
  border-radius: 6px;
  background: #fff;
  box-shadow: 0 2px 8px rgba(25, 45, 65, 0.04);
  transition: box-shadow 0.18s ease, border-color 0.18s ease;
}

.pub-card:hover {
  border-color: #c7d2dc;
  border-left-color: #173b57;
  box-shadow: 0 4px 12px rgba(25, 45, 65, 0.08);
}

.pub-topline {
  margin-bottom: 5px;
}

.pub-title {
  color: #173b57;
  font-size: 1.12rem;
  font-weight: 700;
  line-height: 1.4;
  margin: 0;
}

.pub-meta {
  display: flex;
  flex-wrap: wrap;
  gap: 6px 12px;
  margin-bottom: 8px;
  color: #596a78;
  font-size: 0.88rem;
}

.pub-authors {
  margin: 5px 0 7px;
  color: #344452;
  line-height: 1.55;
}

.pub-venue {
  margin: 0 0 10px;
  color: #536371;
  font-style: italic;
}

.pub-badges {
  display: flex;
  flex-wrap: wrap;
  gap: 6px;
  margin: 10px 0 12px;
}

.pub-badge {
  display: inline-flex;
  align-items: center;
  padding: 3px 8px;
  border: 1px solid #d7e0e7;
  border-radius: 4px;
  background: #f4f7f9;
  color: #425563;
  font-size: 0.78rem;
  font-weight: 600;
  line-height: 1.4;
}

.pub-badge-award {
  border-color: #e7d9b8;
  background: #fbf7ed;
  color: #70591f;
}

.pub-badge-open-access {
  border-color: #cfe0d4;
  background: #f1f7f2;
  color: #315c3d;
}

.pub-summary {
  color: #445360;
  margin-bottom: 12px;
  line-height: 1.6;
}

.pub-links {
  display: flex;
  flex-wrap: wrap;
  gap: 7px;
}

.pub-links a {
  text-decoration: none !important;
  font-weight: 600;
  padding: 5px 9px;
  border-radius: 4px;
  border: 1px solid #d4dee6;
  background: #fff;
  color: #315b78;
  font-size: 0.88rem;
}

.pub-links a:hover,
.pub-links a:focus-visible {
  background: #f1f5f8;
  border-color: #9eafbd;
}

@media (max-width: 600px) {
  .pub-card {
    padding: 15px;
  }

  .pub-legend {
    gap: 12px;
  }
}
</style>

{% assign pubs = site.data.publication.items %}
{% assign my_name = "Alshawki, M. B." %}

## Online Repositories
<div class="pub-legend">

<a href="https://scholar.google.com/citations?hl=en&user=fg0AuD8AAAAJ" target="_blank" rel="noopener noreferrer">
  <img src="/assets/img/gs.jpg" alt="Google Scholar">
</a> 

  
<a href="https://www.scopus.com/authid/detail.uri?authorId=57195277220" target="_blank" rel="noopener noreferrer">
  <img src="/assets/img/sc.png" alt="Scopus">
</a>
 

  
<a href="https://ieeexplore.ieee.org/author/893347168306437" target="_blank" rel="noopener noreferrer">
  <img src="/assets/img/ieee.png" alt="IEEE Xplore">
</a> 


<a href="https://dblp.org/pid/400/1551.html" target="_blank" rel="noopener noreferrer">
  <img src="/assets/img/DBLP.png" alt="DBLP">
</a> 


<a href="https://www.webofscience.com/wos/author/record/C-7051-2018" target="_blank" rel="noopener noreferrer">
  <img src="/assets/img/clarivate-web-of-science.png" alt="Web of Science">
</a> 
</div>

---
## Selected Publications

<div class="pub-page">
  <div class="pub-list">
  {% for pub in pubs %}
    <article class="pub-card">
      <div class="pub-topline">
        <h3 class="pub-title">{{ pub.title }}</h3>
      </div>

      <div class="pub-meta">
        {% if pub.year %}<span>{{ pub.year }}</span>{% endif %}
        {% if pub.type == "journal" %}
          <span>Journal article</span>
        {% elsif pub.type == "conference" %}
          <span>Conference paper</span>
        {% elsif pub.type == "book_chapter" %}
          <span>Book chapter</span>
        {% elsif pub.type == "preprint" %}
          <span>Preprint</span>
        {% endif %}
      </div>

      <div class="pub-authors">
        {% for author in pub.authors %}
          {% if author == my_name %}
            <strong>{{ author }}</strong>
          {% else %}
            {{ author }}
          {% endif %}
          {% unless forloop.last %}, {% endunless %}
        {% endfor %}
      </div>

      <div class="pub-venue">{{ pub.venue }}</div>

      {% if pub.quartile == "Q1" or pub.quartile == "Q2" or pub.quartile == "Q3" or pub.quartile == "Q4" or pub.tier == "A" or pub.tier == "B" or pub.selected or pub.open_access %}
      <div class="pub-badges">
        {% if pub.quartile == "Q1" %}<span class="pub-badge">Q1</span>{% endif %}
        {% if pub.quartile == "Q2" %}<span class="pub-badge">Q2</span>{% endif %}
        {% if pub.quartile == "Q3" %}<span class="pub-badge">Q3</span>{% endif %}
        {% if pub.quartile == "Q4" %}<span class="pub-badge">Q4</span>{% endif %}
        {% if pub.tier == "A" %}<span class="pub-badge">Tier A</span>{% endif %}
        {% if pub.tier == "B" %}<span class="pub-badge">Tier B</span>{% endif %}
        {% if pub.selected %}<span class="pub-badge pub-badge-award">Award winner</span>{% endif %}
        {% if pub.open_access %}<span class="pub-badge pub-badge-open-access">Open access</span>{% endif %}
      </div>
      {% endif %}

      {% if pub.summary and pub.summary != "" %}
        <div class="pub-summary">{{ pub.summary }}</div>
      {% endif %}

      <div class="pub-links">
        {% if pub.links.doi and pub.links.doi != "#" %}<a href="{{ pub.links.doi }}">DOI</a>{% endif %}
        {% if pub.links.pdf and pub.links.pdf != "#" %}<a href="{{ pub.links.pdf }}">PDF</a>{% endif %}
        {% if pub.links.code and pub.links.code != "#" %}<a href="{{ pub.links.code }}">Code</a>{% endif %}
        {% if pub.links.project and pub.links.project != "#" %}<a href="{{ pub.links.project }}">Project</a>{% endif %}
        {% if pub.links.slides and pub.links.slides != "#" %}<a href="{{ pub.links.slides }}">Slides</a>{% endif %}
        {% if pub.links.talk and pub.links.talk != "#" %}<a href="{{ pub.links.talk }}">Talk</a>{% endif %}
        {% if pub.links.bibtex and pub.links.bibtex != "#" %}<a href="{{ pub.links.bibtex }}">BibTeX</a>{% endif %}
        {% if pub.links.arxiv and pub.links.arxiv != "#" %}<a href="{{ pub.links.arxiv }}">arXiv</a>{% endif %}
      </div>
    </article>
  {% endfor %}
  </div>
</div>




---


### Services
- <a href="https://globecom2025.ieee-globecom.org/" target="_blank">IEEE Globecom 2025</a>
- <a href="https://ficloud.org/2025/" target="_blank">IEEE FiCloud 2025</a>
- <a href="https://globecom2024.ieee-globecom.org/" target="_blank">IEEE Globecom 2024</a>
- <a href="http://www.wimob.org/wimob2023/" target="_blank">IEEE Wimob 2023</a>
- <a href="https://www.atis2021.conferences.academy/" target="_blank">ATIS 2021</a>
- [CIoT 2019]()
- <a href="https://onlinelibrary.wiley.com/journal/24756725" target="_blank">Security and Privacy</a>
- <a href="https://www.sciencedirect.com/journal/computer-networks" target="_blank">Computer Networks</a>
- <a href="https://www.sciencedirect.com/journal/future-generation-computer-systems" target="_blank">Future Generation Computer Systems</a>
- <a href="https://www.mdpi.com/journal/jcp" target="_blank">Journal of Cybersecurity and Privacy</a>
- <a href="https://www.pearson.com/en-us/subject-catalog/p/information-privacy-engineering-and-privacy-by-design/P200000007406/9780137582341" target="_blank">Information Privacy Engineering and Privacy by Design</a>