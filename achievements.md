---
layout: page
title: Selected Achievements and Grants
---

<style>
.recognition-page {
  max-width: 960px;
  margin: 0 auto;
  color: var(--teal-ink);
}

.recognition-intro {
  position: relative;
  overflow: hidden;
  margin: 8px 0 34px;
  padding: 28px 30px;
  border-radius: 6px;
  background: var(--teal-950);
  color: #fff;
}

.recognition-intro::after {
  position: absolute;
  top: -62px;
  right: -25px;
  width: 210px;
  height: 210px;
  border: 1px solid rgba(255, 255, 255, 0.14);
  border-radius: 50%;
  box-shadow: 0 0 0 24px rgba(255, 255, 255, 0.04), 0 0 0 52px rgba(255, 255, 255, 0.035);
  content: "";
  pointer-events: none;
}

.recognition-kicker {
  margin: 0 0 8px;
  color: var(--teal-200);
  font-size: 0.78rem;
  font-weight: 700;
  letter-spacing: 0.1em;
  text-transform: uppercase;
}

.recognition-heading {
  position: relative;
  z-index: 1;
  max-width: 640px;
  margin: 0;
  color: #fff;
  font-size: 1.65rem;
  font-weight: 700;
  line-height: 1.3;
}

.recognition-lede {
  position: relative;
  z-index: 1;
  max-width: 650px;
  margin: 10px 0 0;
  color: var(--teal-100);
  line-height: 1.6;
}

.recognition-list {
  position: relative;
  margin: 0;
  padding: 0;
  list-style: none;
}

.recognition-list::before {
  position: absolute;
  top: 10px;
  bottom: 10px;
  left: 53px;
  width: 1px;
  background: var(--teal-border);
  content: "";
}

.recognition-item {
  position: relative;
  display: grid;
  grid-template-columns: 76px minmax(0, 1fr);
  gap: 18px;
  align-items: start;
  padding: 0 0 14px;
}

.recognition-year {
  position: relative;
  z-index: 1;
  padding-top: 17px;
  color: var(--teal-800);
  font-size: 1rem;
  font-weight: 700;
}

.recognition-year::after {
  position: absolute;
  top: 22px;
  right: 14px;
  width: 9px;
  height: 9px;
  border: 2px solid #fff;
  border-radius: 50%;
  background: var(--teal-600);
  box-shadow: 0 0 0 1px var(--teal-600);
  content: "";
}

.recognition-card {
  padding: 15px 18px;
  border: 1px solid var(--teal-border);
  border-left: 3px solid var(--teal-600);
  border-radius: 5px;
  background: #fff;
  transition: border-color 0.15s ease, box-shadow 0.15s ease;
}

.recognition-card:hover {
  border-color: var(--teal-border);
  box-shadow: 0 3px 12px rgba(18, 78, 80, 0.07);
}

.recognition-card.grant {
  border-left-color: var(--teal-600);
}

.recognition-card-header {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 7px 10px;
}

.recognition-title {
  margin: 0;
  color: var(--teal-950);
  font-size: 1.03rem;
  font-weight: 700;
  line-height: 1.4;
}

.recognition-kind {
  padding: 2px 7px;
  border: 1px solid var(--teal-border);
  border-radius: 3px;
  background: var(--teal-100);
  color: var(--teal-800);
  font-size: 0.72rem;
  font-weight: 600;
}

.recognition-card.grant .recognition-kind {
  border-color: var(--teal-200);
  background: var(--teal-100);
  color: var(--teal-950);
}

.recognition-detail {
  margin: 5px 0 0;
  color: var(--teal-muted);
  font-size: 0.92rem;
  line-height: 1.5;
}

.recognition-partners {
  margin-top: 22px;
  padding: 18px 20px;
  border: 1px solid var(--teal-border);
  border-radius: 5px;
  background: var(--teal-50);
}

.recognition-partners-title {
  margin: 0 0 14px;
  color: var(--teal-muted);
  font-size: 0.86rem;
  font-weight: 700;
}

.recognition-logos {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(130px, 1fr));
  gap: 14px 20px;
  align-items: center;
}

.recognition-logos img {
  display: block;
  width: auto;
  max-width: 100%;
  max-height: 60px;
  margin: 0 auto;
  object-fit: contain;
}

.recognition-disclaimer {
  margin: 20px 0 0;
  padding-top: 13px;
  border-top: 1px solid var(--teal-border);
  color: var(--teal-muted);
  font-size: 0.84rem;
  line-height: 1.55;
}

@media (max-width: 560px) {
  .recognition-intro {
    padding: 22px 20px;
  }

  .recognition-heading {
    font-size: 1.4rem;
  }

  .recognition-list::before {
    left: 39px;
  }

  .recognition-item {
    grid-template-columns: 56px minmax(0, 1fr);
    gap: 12px;
  }

  .recognition-year {
    font-size: 0.9rem;
  }

  .recognition-year::after {
    right: 5px;
  }

  .recognition-card {
    padding: 12px 13px;
  }

  .recognition-partners {
    padding: 15px;
  }
}
</style>

<div class="recognition-page">
  <ol class="recognition-list">
    <li class="recognition-item">
      <time class="recognition-year" datetime="2026">2026</time>
      <article class="recognition-card">
        <div class="recognition-card-header">
          <h3 class="recognition-title">Most Inspiring 6G Use Case Award</h3>
          <span class="recognition-kind">Award</span>
        </div>
        <p class="recognition-detail">As part of NATWORK · 6G Summit, Spain</p>
      </article>
    </li>
    <li class="recognition-item">
      <time class="recognition-year" datetime="2024">2024</time>
      <article class="recognition-card grant">
        <div class="recognition-card-header">
          <h3 class="recognition-title">Postdoctoral Grant</h3>
          <span class="recognition-kind">Grant</span>
        </div>
        <p class="recognition-detail">EKOP · ELTE/IDACUS · Hungary and Germany</p>
      </article>
    </li>
    <li class="recognition-item">
      <time class="recognition-year" datetime="2023">2023</time>
      <article class="recognition-card grant">
        <div class="recognition-card-header">
          <h3 class="recognition-title">Project Proposal Grant</h3>
          <span class="recognition-kind">Grant</span>
        </div>
        <p class="recognition-detail">NATWORK · European Union</p>
      </article>
    </li>
    <li class="recognition-item">
      <time class="recognition-year" datetime="2022">2022</time>
      <article class="recognition-card">
        <div class="recognition-card-header">
          <h3 class="recognition-title">Best Paper Award</h3>
          <span class="recognition-kind">Award</span>
        </div>
        <p class="recognition-detail">IEEE ICISPP · Southeast University, China</p>
      </article>
    </li>
    <li class="recognition-item">
      <time class="recognition-year" datetime="2022">2022</time>
      <article class="recognition-card grant">
        <div class="recognition-card-header">
          <h3 class="recognition-title">Research Grant</h3>
          <span class="recognition-kind">Grant</span>
        </div>
        <p class="recognition-detail">UNKP · ELTE University, Hungary</p>
      </article>
    </li>
    <li class="recognition-item">
      <time class="recognition-year" datetime="2021">2021</time>
      <article class="recognition-card">
        <div class="recognition-card-header">
          <h3 class="recognition-title">Bronze Award</h3>
          <span class="recognition-kind">Award</span>
        </div>
        <p class="recognition-detail">EIT Health Innovation Day · European Union</p>
      </article>
    </li>
    <li class="recognition-item">
      <time class="recognition-year" datetime="2020">2020</time>
      <article class="recognition-card">
        <div class="recognition-card-header">
          <h3 class="recognition-title">Best Paper Award</h3>
          <span class="recognition-kind">Award</span>
        </div>
        <p class="recognition-detail">IEEE ICCECE · University of Essex, UK</p>
      </article>
    </li>
    <li class="recognition-item">
      <time class="recognition-year" datetime="2019">2019</time>
      <article class="recognition-card">
        <div class="recognition-card-header">
          <h3 class="recognition-title">Gold Award</h3>
          <span class="recognition-kind">Award</span>
        </div>
        <p class="recognition-detail">EIT Health Innovation Day · European Union</p>
      </article>
    </li>
    <li class="recognition-item">
      <time class="recognition-year" datetime="2018">2018</time>
      <article class="recognition-card grant">
        <div class="recognition-card-header">
          <h3 class="recognition-title">NeCS Tuition Grant</h3>
          <span class="recognition-kind">Grant</span>
        </div>
        <p class="recognition-detail">University of Trento, Italy</p>
      </article>
    </li>
    <li class="recognition-item">
      <time class="recognition-year" datetime="2010">2010</time>
      <article class="recognition-card grant">
        <div class="recognition-card-header">
          <h3 class="recognition-title">Research Grant</h3>
          <span class="recognition-kind">Grant</span>
        </div>
        <p class="recognition-detail">DAAD · TU Berlin, Germany</p>
      </article>
    </li>
    <li class="recognition-item">
      <time class="recognition-year" datetime="2008">2008</time>
      <article class="recognition-card">
        <div class="recognition-card-header">
          <h3 class="recognition-title">Minister of Higher Education Award</h3>
          <span class="recognition-kind">Award</span>
        </div>
        <p class="recognition-detail">For holding the highest GPA</p>
      </article>
    </li>
    <li class="recognition-item">
      <time class="recognition-year" datetime="2008">2008</time>
      <article class="recognition-card">
        <div class="recognition-card-header">
          <h3 class="recognition-title">Deputy Prime Minister Award</h3>
          <span class="recognition-kind">Award</span>
        </div>
        <p class="recognition-detail">For holding the highest GPA</p>
      </article>
    </li>
  </ol>

  <section class="recognition-partners" aria-labelledby="recognition-partners-title">
    <h2 class="recognition-partners-title" id="recognition-partners-title"></h2>
    <div class="recognition-logos">
      <img src="/assets/img/DAAD.png" alt="DAAD">
      <img src="/assets/img/ekop.png" alt="EKOP">
      <img src="/assets/img/eu.png" alt="European Union">
      <img src="/assets/img/necs.jpg" alt="NeCS">
      <img src="/assets/img/unkp.png" alt="UNKP">
      <img src="/assets/img/ac.png" alt="Academic partner">
    </div>
  </section>

  <p class="recognition-disclaimer"><strong>Disclaimer:</strong> The achievements, awards, and grants listed here reflect my individual contributions and involvement in collaborative efforts. Recognition and funding may have been awarded to individuals, teams, or institutions, and their inclusion does not imply sole ownership, individual attribution, or endorsement by the awarding or funding organizations.</p>
</div>
