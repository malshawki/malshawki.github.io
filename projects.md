---
layout: page
title: Projects
---

<style>
.projects-page {
  max-width: 1000px;
  margin: 0 auto;
}

.projects-intro {
  margin: 0 0 22px;
  color: var(--teal-muted);
  line-height: 1.6;
}

.project-list {
  display: grid;
  gap: 14px;
}

.project-card {
  display: grid;
  grid-template-columns: minmax(0, 1fr) minmax(150px, 210px);
  gap: 20px;
  align-items: center;
  padding: 18px 20px;
  border: 1px solid var(--teal-border);
  border-left: 4px solid var(--teal-800);
  border-radius: 5px;
  background: #fff;
}

.project-title {
  margin: 0 0 9px;
  color: var(--teal-950);
  font-size: 1.2rem;
  font-weight: 700;
  line-height: 1.35;
}

.project-role {
  margin: 0 0 9px;
  color: var(--teal-muted);
  line-height: 1.55;
}

.project-details {
  margin: 0;
  padding-left: 18px;
  color: var(--teal-muted);
  font-size: 0.94rem;
  line-height: 1.55;
}

.project-details li + li {
  margin-top: 3px;
}

.project-logo {
  display: flex;
  align-items: center;
  justify-content: center;
  min-height: 78px;
  padding: 10px;
  border-left: 1px solid var(--teal-border);
}

.project-logo img {
  display: block;
  width: auto;
  max-width: 100%;
  max-height: 74px;
  object-fit: contain;
}

.projects-disclaimer {
  margin: 24px 0 0;
  padding-top: 14px;
  border-top: 1px solid var(--teal-border);
  color: var(--teal-muted);
  font-size: 0.88rem;
  line-height: 1.55;
}

@media (max-width: 600px) {
  .project-card {
    grid-template-columns: 1fr;
    gap: 12px;
    padding: 15px;
  }

  .project-logo {
    justify-content: flex-start;
    min-height: auto;
    padding: 10px 0 0;
    border-top: 1px solid var(--teal-border);
    border-left: 0;
  }
}
</style>

<div class="projects-page">
  <p class="projects-intro">Selected research projects and collaborations in cybersecurity, privacy, and secure digital infrastructure.</p>

  <div class="project-list">
    <article class="project-card">
      <div>
        <h2 class="project-title">6G Security</h2>
        <p class="project-role">Senior cybersecurity researcher leading the following research pillars:</p>
        <ul class="project-details">
          <li>Pillar 1 - Trust Establishment in B5G/6G Network</li>
          <li>Pillar 2 - Secure Federated Learning in B5G/6G Network</li>
          <li>HORIZON-101139285: NATWORK</li>
        </ul>
      </div>
      <div class="project-logo">
        <img src="/assets/img/eu_funded_en.jpg" alt="Funded by the European Union">
      </div>
    </article>

    <article class="project-card">
      <div>
        <h2 class="project-title">Industrial Internet of Things Security</h2>
        <ul class="project-details">
          <li>Safeguarding Industrial Internet of Things authentication</li>
          <li>EKOP-24-4-2: Postdoctoral Research Scholarship</li>
        </ul>
      </div>
      <div class="project-logo">
        <img src="/assets/img/ekop.png" alt="Funded by the Ministry of Research and Innovation">
      </div>
    </article>

    <article class="project-card">
      <div>
        <h2 class="project-title">Thematic Excellence Program</h2>
        <ul class="project-details">
          <li>Developing secure data validators</li>
          <li>TKP2020-NKA-06: Hungarian National Challenges - Cybersecurity Subprogramme</li>
        </ul>
      </div>
      <div class="project-logo">
        <img src="/assets/img/cofeu.png" alt="Co-funded by the European Union">
      </div>
    </article>

    <article class="project-card">
      <div>
        <h2 class="project-title">Secure Navigation</h2>
        <ul class="project-details">
          <li>Developing a secure Galileo navigation authentication protocol</li>
          <li>1.3-KK: Software and Data-Intensive Services project</li>
        </ul>
      </div>
      <div class="project-logo">
        <img src="/assets/img/cofeu.png" alt="Co-funded by the European Union">
      </div>
    </article>

    <article class="project-card">
      <div>
        <h2 class="project-title">Lightweight Cryptography</h2>
        <ul class="project-details">
          <li>Developing lightweight attribute-based encryption for smart IoT devices</li>
          <li>ÚNKP-22-4: Research Scholarship for Doctoral Candidates</li>
        </ul>
      </div>
      <div class="project-logo">
        <img src="/assets/img/unkp-all.png" alt="Funded by the Ministry of Research and Innovation">
      </div>
    </article>

    <article class="project-card">
      <div>
        <h2 class="project-title">Distributed Security</h2>
        <ul class="project-details">
          <li>Developing secure protocols for distributed environments</li>
          <li>ÚNKP-21-3: Research Scholarship for Doctoral Students</li>
        </ul>
      </div>
      <div class="project-logo">
        <img src="/assets/img/unkp-all.png" alt="Funded by the Ministry of Research and Innovation">
      </div>
    </article>

    <article class="project-card">
      <div>
        <h2 class="project-title">Autonomous Vehicle Control</h2>
        <ul class="project-details">
          <li>Developing lightweight cryptographic protocols</li>
          <li>VEKOP-16: Talent Management in Autonomous Vehicle Control</li>
        </ul>
      </div>
      <div class="project-logo">
        <img src="/assets/img/cofeu.png" alt="Co-funded by the European Union">
      </div>
    </article>

    <article class="project-card">
      <div>
        <h2 class="project-title">Smart Platform for Digital Networks</h2>
        <ul class="project-details">
          <li>Developing secure SDN for cyber-physical systems</li>
          <li>02P17D022: Collaborative smart contracting platform for digital value creation networks</li>
        </ul>
      </div>
      <div class="project-logo">
        <img src="/assets/img/bmbf.png" alt="Funded by BMBF">
      </div>
    </article>

    <article class="project-card">
      <div>
        <h2 class="project-title">Secure Cryptographic Protocols</h2>
        <ul class="project-details">
          <li>Developing secure cryptographic protocols</li>
          <li>EFOP-3.6.2: Innovations in Informatics and Infocommunication</li>
        </ul>
      </div>
      <div class="project-logo">
        <img src="/assets/img/cofeu.png" alt="Co-funded by the European Union">
      </div>
    </article>

    <article class="project-card">
      <div>
        <h2 class="project-title">Orchestration of Financial Services</h2>
        <ul class="project-details">
          <li>Blockchain analyzer</li>
          <li>OFION: Communication and Security Analysis of the Cloud Orchestrator Module</li>
        </ul>
      </div>
      <div class="project-logo">
        <img src="/assets/img/Atos.svg.png" alt="Funded by Atos">
      </div>
    </article>
  </div>

<p class="projects-disclaimer"><strong>Disclaimer:</strong> The projects listed here reflect my involvement and contributions, independently or as part of collaborative efforts. Project descriptions are provided for informational purposes and do not imply sole ownership, authorship, or endorsement by affiliated institutions, collaborators, or sponsors.</p>
</div>
