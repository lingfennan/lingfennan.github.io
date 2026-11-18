---
title: "Simhash-based Dynamic Cloaking Detection"
excerpt: "Client-side detection of search/ad cloaking by comparing simhash summaries of page views."
collection: portfolio
---

Abusive advertisers use cloaking — serving benign content to ad-serving companies for review while delivering non-compliant or malicious content to real users — to evade policy enforcement. IP-based cloaking is especially hard to detect, and prior approaches that impersonate users (proxies, spoofed referrers) can be detected and blocked by spammers.

This work uses **simhash** computed on the user side via a browser plugin, comparing it against the simhash of the same page as seen by the ad-serving company. Large differences indicate cloaking. Separate simhashes for page content and structure improve robustness against naturally dynamic pages while protecting user privacy.

- Paper: [Cloaker Catcher: A Client-based Cloaking Detection System](/publication/2017-10-03-cloaker-catcher) (arXiv:1710.01387)
- [Extended project description](/planetlab_description/cloaking_project_description.html)
