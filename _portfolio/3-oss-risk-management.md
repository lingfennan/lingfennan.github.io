---
title: "OSSPolice / OSSSanitizer: Automating OSS Risk Management"
excerpt: "Scalable detection of license violations and known-vulnerable OSS versions in app binaries."
collection: portfolio
---

Developers rely heavily on third-party open-source software (OSS) to ship apps quickly, but careless OSS use introduces legal and security risks that are tedious and error-prone to track.

**OSSPolice** is a scalable, fully-automated tool that analyzes app binaries to identify free-software license violations and the use of known-vulnerable OSS versions. It introduces a hierarchical indexing scheme that achieves both scalability and accuracy, comparing app binaries against a database of hundreds of thousands of OSS sources (billions of lines of code). Populated with 60K C/C++ and 77K Java OSS sources, it analyzed 1.6M free Google Play apps — finding over 40K apps potentially violating GPL/AGPL terms and over 100K using known-vulnerable OSS versions.

- Papers: [Identifying Open-Source License Violation and 1-day Security Risk at Large Scale](/publication/2017-10-30-osspolice) (CCS 2017); [Automating Patching of Vulnerable Open-Source Software Versions in Application Binaries](/publication/2019-02-24-osspatcher) (NDSS 2019)
- Supported by an NSF I-Corps award (No. 1851927)
- [Extended project description](/osssanitizer_description/osssanitizer_project_description.html)
