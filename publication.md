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
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  align-items: center;
  gap: 12px 20px;
  margin: 10px 0 28px;
  padding: 16px 18px;
  border: 1px solid #dfe5eb;
  border-radius: 8px;
  background: #f8fafc;
}

.pub-legend a {
  display: flex;
  align-items: center;
  justify-content: center;
  min-height: 76px;
}

.pub-legend img {
  display: block;
  width: auto;
  max-width: 190px;
  max-height: 68px;
  object-fit: contain;
}

.pub-list {
  display: grid;
  gap: 10px;
}

.pub-card {
  padding: 12px 16px;
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
  margin-bottom: 3px;
}

.pub-title {
  color: #173b57;
  font-size: 1.05rem;
  font-weight: 700;
  line-height: 1.35;
  margin: 0;
}

.pub-authors {
  margin: 3px 0 2px;
  color: #344452;
  line-height: 1.4;
}

.pub-venue {
  margin: 0;
  color: #536371;
  font-style: italic;
  line-height: 1.4;
}

.pub-labels {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 5px 7px;
  margin-top: 7px;
  color: #596a78;
  font-size: 0.88rem;
}

.pub-year {
  margin-right: 2px;
  font-weight: 600;
}

.pub-badge {
  display: inline-flex;
  align-items: center;
  padding: 2px 7px;
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
  margin: 7px 0 0;
  line-height: 1.45;
}

.pub-labels a {
  text-decoration: none !important;
  font-weight: 600;
  padding: 2px 7px;
  border-radius: 4px;
  border: 1px solid #d4dee6;
  background: #fff;
  color: #315b78;
  font-size: 0.82rem;
}

.pub-labels a:hover,
.pub-labels a:focus-visible {
  background: #f1f5f8;
  border-color: #9eafbd;
}

@media (max-width: 600px) {
  .pub-legend {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }

  .pub-card {
    padding: 11px 12px;
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

      <div class="pub-labels">
        {% if pub.year %}<span class="pub-year">{{ pub.year }}</span>{% endif %}
        {% if pub.quartile == "Q1" %}<span class="pub-badge">Q1</span>{% endif %}
        {% if pub.quartile == "Q2" %}<span class="pub-badge">Q2</span>{% endif %}
        {% if pub.quartile == "Q3" %}<span class="pub-badge">Q3</span>{% endif %}
        {% if pub.quartile == "Q4" %}<span class="pub-badge">Q4</span>{% endif %}
        {% if pub.tier == "A" %}<span class="pub-badge">Tier A</span>{% endif %}
        {% if pub.tier == "B" %}<span class="pub-badge">Tier B</span>{% endif %}
        {% if pub.selected %}<span class="pub-badge pub-badge-award">Award winner</span>{% endif %}
        {% if pub.open_access %}<span class="pub-badge pub-badge-open-access">Open access</span>{% endif %}
        {% if pub.links.doi and pub.links.doi != "#" %}<a href="{{ pub.links.doi }}" target="_blank" rel="noopener noreferrer">DOI</a>{% endif %}
        {% if pub.links.pdf and pub.links.pdf != "#" %}<a href="{{ pub.links.pdf }}">PDF</a>{% endif %}
        {% if pub.links.code and pub.links.code != "#" %}<a href="{{ pub.links.code }}">Code</a>{% endif %}
        {% if pub.links.project and pub.links.project != "#" %}<a href="{{ pub.links.project }}">Project</a>{% endif %}
        {% if pub.links.slides and pub.links.slides != "#" %}<a href="{{ pub.links.slides }}">Slides</a>{% endif %}
        {% if pub.links.talk and pub.links.talk != "#" %}<a href="{{ pub.links.talk }}">Talk</a>{% endif %}
        {% if pub.links.bibtex and pub.links.bibtex != "#" %}<a href="{{ pub.links.bibtex }}">BibTeX</a>{% endif %}
        {% if pub.links.arxiv and pub.links.arxiv != "#" %}<a href="{{ pub.links.arxiv }}">arXiv</a>{% endif %}
      </div>

      {% if pub.summary and pub.summary != "" %}
        <div class="pub-summary">{{ pub.summary }}</div>
      {% endif %}
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