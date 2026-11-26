---
layout: page
title: About me
full-width: true
---

<style>
.about-page {
  max-width: 1000px;
  margin: 0 auto;
  color: var(--teal-ink);
}

.about-intro {
  margin: 8px 0 42px;
  padding: 8px 0 8px 22px;
  border-left: 3px solid var(--teal-600);
}

.about-intro p {
  margin: 0 0 14px;
  color: var(--teal-muted);
  font-size: 1.08rem;
  line-height: 1.8;
}

.about-intro p:last-child {
  margin-bottom: 0;
}

.about-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  column-gap: 48px;
  row-gap: 34px;
}

.about-section {
  padding-top: 17px;
  border-top: 1px solid var(--teal-border);
}

.about-section h2::before {
  width: 7px;
  height: 7px;
  flex: 0 0 7px;
  border-radius: 50%;
  background: var(--teal-600);
  content: "";
}

.about-section h2 {
  display: flex;
  align-items: center;
  gap: 10px;
  margin: 0 0 12px;
  color: var(--teal-950);
  font-size: 1.3rem;
  font-weight: 700;
  line-height: 1.35;
}

.about-section p {
  margin: 0 0 12px;
  color: var(--teal-muted);
  font-size: 1rem;
  line-height: 1.7;
}

.about-list {
  margin: 0;
  padding-left: 21px;
  color: var(--teal-muted);
  font-size: 1rem;
  line-height: 1.75;
}

.about-list li {
  padding-left: 3px;
}

.about-list li + li {
  margin-top: 4px;
}

.about-list strong {
  color: var(--teal-900);
  font-weight: 700;
}

.about-research {
  padding: 20px;
  border: 1px solid var(--teal-border);
  border-radius: 12px;
  background: var(--teal-50);
}

.about-research h2::before {
  border-radius: 2px;
  transform: rotate(45deg);
}

.about-education {
  padding: 3px 0 3px 17px;
  border-top: 0;
  border-left: 3px solid var(--teal-500);
}

.about-memberships {
  padding-top: 17px;
  border-top: 2px solid var(--teal-200);
}

.about-memberships h2::before {
  width: 10px;
  height: 10px;
  flex-basis: 10px;
  background: var(--teal-200);
  border: 2px solid var(--teal-700);
}

.about-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin: 0;
  padding: 0;
  list-style: none;
}

.about-tags li,
.about-companies li {
  padding: 5px 10px;
  border: 1px solid var(--teal-border);
  border-radius: 999px;
  background: white;
  color: var(--teal-900);
  font-size: 0.94rem;
  line-height: 1.45;
}

.about-companies {
  display: flex;
  flex-wrap: wrap;
  gap: 9px;
  margin: 0;
  padding: 0;
  list-style: none;
}

.about-companies li {
  border-color: var(--teal-200);
  background: var(--teal-100);
  font-weight: 600;
}

.about-collaborations h2::before {
  border: 2px solid var(--teal-700);
  background: transparent;
  border-radius: 2px;
}

.about-certificates {
  grid-column: 1 / -1;
  padding: 20px;
  border: 1px solid var(--teal-border);
  border-radius: 12px;
}

.about-certificates h2::before {
  width: 10px;
  height: 3px;
  flex-basis: 10px;
  border-radius: 0;
}

.about-certificates .about-list {
  columns: 2;
  column-gap: 48px;
}

.about-certificates .about-list li {
  break-inside: avoid;
  margin-bottom: 5px;
}

@media (max-width: 700px) {
  .about-grid {
    grid-template-columns: 1fr;
    row-gap: 27px;
  }

  .about-certificates {
    grid-column: auto;
  }

  .about-certificates .about-list {
    columns: 1;
  }
}

@media (max-width: 560px) {
  .about-intro {
    margin-bottom: 32px;
    padding-left: 16px;
  }

  .about-intro p {
    font-size: 1rem;
  }
}
</style>

<div class="about-page">
  <section class="about-intro" aria-label="Biography">
    <p>
      I’m an <strong>Associate Professor</strong> at ELTE and a <strong>Senior Researcher</strong> in the Cyber Security and Cryptography Research Group. With more than 15 years of experience in cybersecurity, trusted systems, and privacy-preserving technologies, I work to connect academic research with real-world needs in critical digital infrastructure. I was a short term <strong>visiting researcher</strong> at BNU, UK. Prior to that, I was a <strong>postdoctoral researcher</strong> at the Institute for Data Science, Cloud Computing and IT-Security, Germany, under the supervision of Prof. Christoph Reich.
    </p>
    <p>
      I hold a <strong>Ph.D. in Informatics</strong> jointly from Eötvös Loránd University and Furtwangen University, as well as a <strong>Diploma in Information Technology</strong> from Technical University of Berlin. I also serve as a <strong>certified cybersecurity consultant</strong>, advising on secure system design, AI governance, and critical infrastructure protection.
    </p>
    <p>
      My current research focuses on <strong>secure authentication and AI-driven aggregation for 6G networks</strong>, with the goal of making future communication systems more resilient, adaptive, and privacy-aware.
    </p>
  </section>

  <div class="about-grid">
    <section class="about-section about-research">
      <h2>Research interests</h2>
      <p>My work spans cryptography, distributed systems, and artificial intelligence, with current interests in:</p>
      <ul class="about-list">
        <li>Distributed systems security</li>
        <li>Federated AI security</li>
        <li>Applied cryptography and PQ security</li>
        <li>Cryptographic protocols</li>
      </ul>
    </section>

    <section class="about-section about-education">
      <h2>Education</h2>
      <ul class="about-list">
        <li><strong>Ph.D. in Computer Science</strong> — ELTE and HFU</li>
        <li><strong>M.Sc. in Computer Science</strong> — UoB</li>
        <li><strong>Diploma in Information Technology</strong> — TU Berlin</li>
      </ul>
    </section>

    <section class="about-section about-memberships">
      <h2>Memberships</h2>
      <ul class="about-tags">
        <li>6G-IA Security Working Group</li>
        <li>IEEE (Institute of Electrical and Electronics Engineers)</li>
        <li>ACM (Association for Computing Machinery)</li>
        <li>Australian Information Security Association (AISA)</li>
      </ul>
    </section>

    <section class="about-section about-collaborations">
      <h2>Previous industry collaborations</h2>
      <ul class="about-companies">
        <li>Atos (ES)</li>
        <li>LogMeIn (EU)</li>
        <li>ConsultingHun (HU)</li>
      </ul>
    </section>

    <section class="about-section about-certificates">
      <h2>Additional certificates</h2>
      <ul class="about-list">
        <li><strong>Certified Cybersecurity Consultant</strong> — Concordia (EU)</li>
        <li><strong>Cybersecurity</strong> — Infineon Technologies (AT)</li>
        <li><strong>Future IoT</strong> — IMT Atlantique (FR)</li>
        <li><strong>Internet of Things and Blockchain</strong> — University of Lisbon (PT)</li>
        <li><strong>Foundations of Security Analysis and Design</strong> — University of Urbino (IT)</li>
        <li><strong>Cryptography and Privacy</strong> — Radboud University (NL)</li>
        <li><strong>Cybersecurity</strong> — University of Trento (IT)</li>
        <li><strong>Offensive Security Testing</strong> — EIT</li>
        <li><strong>Provable Security</strong> — Budapest University of Technology (HU)</li>
      </ul>
    </section>
  </div>
</div>
