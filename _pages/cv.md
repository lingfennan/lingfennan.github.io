---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- To add a downloadable PDF CV: compile a current résumé, place it at files/cv.pdf,
     and restore a link here. Do NOT reuse the old docs/resume.pdf — it contains a
     personal phone number and outdated (PhD-era) information. -->

Education
======
* Ph.D. in Computer Science, Georgia Institute of Technology, 2012–2019
  * Advisors: Prof. Wenke Lee and Prof. Brendan Saltaformaggio
  * Dissertation: *Toward Solving the Security Risks of Open-Source Software Use*
* B.E. in Computer Science and Technology, Tsinghua University, 2008–2012

Experience
======
* Assistant Professor, Department of Computer Science and Technology, Tsinghua University (present)
* Principal Researcher, Palo Alto Networks, Inc., 2020–2024 (previously Senior Staff / Staff Security Researcher)
  * Cloud-Delivered Security Services
  * Research contributed to the Advanced DNS Security and Advanced IP Defense products — detecting and blocking DNS tunneling, DNS relaying, NXNS-based DDoS, DNS-misconfiguration vulnerabilities (dangling DNS records, claimable non-existent domains), and malicious direct-to-IP traffic
* Graduate Research Assistant, Georgia Institute of Technology, 2012–2019
  * Software, web, and DNS security; open-source software risk identification, automated 1-day patching, and supply-chain attack detection
* Software Engineer Intern, Google Inc., Summers 2013–2015
  * Impersonation app detection (Google Play), search-engine cloaking detection, and personal-search data analytics
* Research Assistant, Tsinghua University, 2011–2012
  * Networking: algorithms for routers and switches, with theoretical bounds and simulation/emulation

Research interests
======
* Network security (especially DNS security)
* Software and supply-chain security
* AI security
* Web security, mobile security, malware analysis

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Patents
======
See the full list of granted patents and applications on the [Patents page](/patents/).

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Awards and grants
======
* NSF SBIR — *Securing Open-Source Software Supply Chain* (Award No. 2112368), 2021
* NSF I-Corps — *OSSPolice* (Award No. 1851927), 2018
* Winner, Atlanta Startup Battle, 2018
* Commercial Track Winner, Georgia Tech IISP Cybersecurity Demo Day, 2018
* National Endeavor Scholarship, 2009 & 2011
* Tsinghua University — Volunteer Scholarship (2011), Wang Wang Scholarship (2010)

Service
======
* Program Committee: USENIX Security 2027, ICICS 2021
* Reviewer: DSN 2026, JCS 2026, TDSC 2023/2025, SPE 2023, IEEE S&P 2019, RAID 2017/2018/2019, NDSS 2015/2016/2018/2019, USENIX Security 2016/2017, CCS 2016, CSUR 2016, ISC 2019, IC3 2017, DSN 2014, NSDI 2013

Skills
======
* Programming: C/C++, Java, Python, JavaScript, Shell, Assembly; familiar with Ruby, PHP, VHDL, Verilog
* Tools: Linux, MATLAB, LaTeX
