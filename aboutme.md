---
layout: page
title: About me
full-width: true
---

<style>
.about-page {
  max-width: 1000px;
  margin: 0 auto;
  color: #293b4a;
}

.about-intro {
  margin: 8px 0 42px;
  padding: 8px 0 8px 22px;
  border-left: 3px solid #3b8090;
}

.about-intro p {
  margin: 0 0 14px;
  color: #40515e;
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
  border-top: 1px solid #dfe5eb;
}

.about-section h2 {
  margin: 0 0 12px;
  color: #173b57;
  font-size: 1.3rem;
  font-weight: 700;
  line-height: 1.35;
}

.about-section p {
  margin: 0 0 12px;
  color: #52616d;
  font-size: 1rem;
  line-height: 1.7;
}

.about-list {
  margin: 0;
  padding-left: 21px;
  color: #40515e;
  font-size: 1rem;
  line-height: 1.75;
}

.about-list li {
  padding-left: 3px;
}

.about-list li + li {
  margin-top: 4px;
}

.about-certificates {
  grid-column: 1 / -1;
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
      I’m an Associate Professor at ELTE and a Senior Researcher in the Cyber Security and Cryptography Research Group. With more than 15 years of experience in cybersecurity, trusted systems, and privacy-preserving technologies, I work to connect academic research with real-world needs in critical digital infrastructure. I was a short term visiting researcher at BNU, UK. Prior to that, I was a postdoctoral researcher at Institute for Data Science, Cloud Computing and IT-Security, Germany, under supervision of Prof. Christoph Reich. 
    </p>
    <p>
      I hold a Ph.D. in Informatics jointly from Eötvös Loránd University and Furtwangen University, as well as a Diploma in Information Technology from Technical University of Berlin. I also serve as a certified cybersecurity consultant, advising on secure system design, AI governance, and critical infrastructure protection.
    </p>
    <p>
      My current research focuses on secure authentication and AI-driven aggregation for 6G networks, with the goal of making future communication systems more resilient, adaptive, and privacy-aware.
    </p>
  </section>

  <div class="about-grid">
    <section class="about-section">
      <h2>Research interests</h2>
      <p>My work spans cryptography, distributed systems, and artificial intelligence, with current interests in:</p>
      <ul class="about-list">
        <li>Distributed systems security</li>
        <li>Federated AI security</li>
        <li>Applied cryptography and PQ security</li>
        <li>Cryptographic protocols</li>
      </ul>
    </section>

    <section class="about-section">
      <h2>Education</h2>
      <ul class="about-list">
        <li>Ph.D. in Computer Science, ELTE and HFU</li>
        <li>M.Sc. in Computer Science, UoB</li>
        <li>Diploma in Information Technology, TU Berlin</li>
      </ul>
    </section>

    <section class="about-section">
      <h2>Memberships</h2>
      <ul class="about-list">
        <li>6G-IA Security Working Group</li>
        <li>IEEE (Institute of Electrical and Electronics Engineers)</li>
        <li>ACM (Association for Computing Machinery)</li>
        <li>Australian Information Security Association (AISA)</li>
      </ul>
    </section>

    <section class="about-section">
      <h2>Previous industry collaborations</h2>
      <ul class="about-list">
        <li>Atos (ES)</li>
        <li>LogMeIn (EU)</li>
        <li>ConsultingHun (HU)</li>
      </ul>
    </section>

    <section class="about-section about-certificates">
      <h2>Additional certificates</h2>
      <ul class="about-list">
        <li>Certified Cybersecurity Consultant, Concordia (EU)</li>
        <li>Cybersecurity, Infineon Technologies (AT)</li>
        <li>Future IoT, IMT Atlantique (FR)</li>
        <li>Internet of Things and Blockchain, University of Lisbon (PT)</li>
        <li>Foundations of Security Analysis and Design, University of Urbino (IT)</li>
        <li>Cryptography and Privacy, Radboud University (NL)</li>
        <li>Cybersecurity, University of Trento (IT)</li>
        <li>Offensive Security Testing, EIT</li>
        <li>Provable Security, Budapest University of Technology (HU)</li>
      </ul>
    </section>
  </div>
</div>
