---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Profile
======
Cybersecurity engineer and security researcher with 15+ years of experience across penetration testing, vulnerability research, intrusion detection, and applied AI for security monitoring. PhD in Cybersecurity (Goethe University Frankfurt, in collaboration with CERN). Published researcher with 200+ peer-reviewed papers and 6 assigned CVEs, including a Microsoft-acknowledged memory-corruption vulnerability. Experienced across the full security lifecycle: ethical hacking and source code audits for banks and ISPs, large-scale distributed systems security at CERN, and founding a security startup.

Education
======
* PhD, Computer Science (Cybersecurity), Goethe University, Frankfurt am Main, Germany, 2013–2019
  * Thesis: *"Deep Learning and Isolation Based Security for Intrusion Detection and Prevention in Grid Computing"*
* BTA Certified Blockchain Security Professional, Blockchain Training Alliance, 2021
* BSc, Computer Science, Universidad de Antioquia, Medellín, Colombia, 2003–2011
  * Awarded thesis: *"Fast Selection of Radial Basis Function Network Centers Based on Marginal Data Analysis"*

Work experience
======
* 2026–Present: Part-Time Professor, Security/Blockchain
  * Costa Rica Institute of Technology (TEC)
  * Teach within the Cybersecurity Master's program, covering blockchain security fundamentals.

* 2025–2026: Security Developer
  * Modulo Labs
  * Analyzed and developed cryptographic code and smart contracts for Panther, a privacy-enhancing protocol, with a focus on security review.

* 2020–Present: Co-Founder & CEO
  * Sakundi ÖU
  * Founded and lead a security, privacy, and digital identity startup, setting technical direction and client strategy.
  * Deliver security audits, monitoring solutions, and identity infrastructure to enterprise and protocol clients.

* 2013–2020: DevOps Engineer
  * Goethe University Frankfurt / CERN
  * Built and maintained the security monitoring system for the ALICE High-Level Trigger (HLT) computing cluster using Zabbix.
  * Managed infrastructure-as-code and configuration management for the ALICE HLT cluster using Puppet.

* 2013–2019: PhD Researcher, Computer Science (Cybersecurity)
  * Goethe University Frankfurt / CERN
  * Researched deep learning (generative models) and isolation-based methods for intrusion detection and prevention on the Worldwide LHC Computing Grid (WLCG), one of the largest distributed computing infrastructures in the world.
  * Built a Python/Perl framework implementing the research; co-authored 3 peer-reviewed papers from this work.

* 2011–2013: Security Researcher
  * Fluid Attacks
  * Performed penetration tests, source code audits, and vulnerability assessments for banks, software development companies, and ISPs.
  * Conducted ethical hacking engagements; identified and reported multiple CVEs, including a Microsoft DirectShow memory-overwrite vulnerability (MS13-056).

Skills
======
* Offensive Security
  * Penetration testing, source code auditing, fuzzing, vulnerability research & exploit development, ethical hacking
* Defensive Security
  * Intrusion detection & prevention, security monitoring for distributed/grid systems, distributed digital identity
* AI / ML for Security
  * Deep learning, machine learning, NLP — TensorFlow, Keras, scikit-learn, pandas, NumPy, SciPy, Gensim
* Languages
  * Python, JavaScript/Node.js, C/C++, Java, Solidity
* DevOps / Infra
  * Docker, Ansible, Puppet, Foreman, Vagrant, Git, OpenStack, Linux (Debian, Ubuntu, CentOS, Tails)
* Blockchain
  * Ethereum, Bitcoin, Polygon, Antelope (EOSIO), Dash, Nym — validator/node infrastructure, zero-knowledge proofs
* Spoken Languages
  * Spanish (Native), English (Fluent), German (Basic)

Selected projects
======
* **[Tikuna](https://github.com/sakundi/tikuna)** — AI-based security monitoring system for the Ethereum P2P network (nodes & validators), funded by an Ethereum Foundation Academic Research grant.
* **[Arhuaco](https://github.com/kuronosec/arhuaco)** — PhD thesis project at CERN: deep learning and isolation-based intrusion detection for distributed high-throughput computing.
* **[Zikuani](https://github.com/kuronosec/zikuani)** — Privacy-preserving identity verification system using zero-knowledge proofs. Backed by ZK Bankai and Polygon; DIF 2025 hackathon winner.
* **[ZK Voto Digital](https://github.com/kuronosec/zk-voto-digital)** — Secure voting system using Zikuani to verify voter eligibility (humanity, citizenship, age) without exposing personal identity.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

CVEs & disclosures
======
* 6 CVEs assigned: CVE-2011-4620, CVE-2012-1189, CVE-2012-2090, CVE-2012-2091, CVE-2012-4552, CVE-2012-5576
* Including MS13-056 (DirectShow memory-overwrite vulnerability), published in the National Vulnerability Database

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

References
======
* Available upon request, including former supervisors at CERN and Fluid Attacks.
