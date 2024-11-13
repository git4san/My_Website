---
title: 'Enriching the Semantics of Information Flow Tracking with Source-Level Memory Allocation Event Logging'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Sanoop Mallissery
  - Yu-Sung Wu

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2023-11-07T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-11-07T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2023 IEEE Conference on Dependable and Secure Computing*
publication_short: In *DSC*

abstract: Information flow tracking (IFT) reveals how a program accesses its data throughout its execution. It can effectively detect the leakage of sensitive data or the corruption of critical data. Much of its strength depends on the semantics of the variables involved. Here, we have devised SQUIRREL, a configurable static code instrumentation and runtime logging tool, which enriches the semantics of information flow representation with detailed source-code level variable mappings. System administrators or intrusion detection systems (IDS) will have precise insight into the information flow, making it possible to detect attacks on zero-day vulnerabilities or application-specific logic loopholes. We evaluate SQUIRREL with various real-world programs and generate information flow with source-level variable mappings and discuss the efficiency of SQUIRREL concerning performance overhead and memory usage with existing profiling tools.

# Summary. An optional shortened abstract.
summary: This paper presents SQUIRREL, a tool that enhances information flow tracking (IFT) by providing detailed source-code-level variable mappings. It helps detect sensitive data leaks and critical data corruption, improving attack detection on zero-day vulnerabilities or application-specific logic flaws. The tool’s efficiency is demonstrated through evaluations on real-world programs, showing minimal performance overhead and memory usage compared to existing profiling tools.

tags:
  - Information Flow Tracking (IFT)
  - Static Code Instrumentation
  - Runtime Logging
  - Zero-day Vulnerabilities
  - Data Leak Prevention
  - Source Code Analysis

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '/My_Paper/squirrel.pdf'
url_code: 'https://ieeexplore.ieee.org/abstract/document/10354156'
url_dataset: ''
url_poster: ''
url_project: '/My_Paper_Slides/squirrel.pdf'
url_slides: '/My_Paper_Slides/squirrel.pdf'
url_source: 'https://ieeexplore.ieee.org/abstract/document/10354156'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'SQUIRREL'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - "AI-Driven Cybersecurity"

---

##### Citation

<div class="citation">
Sanoop Mallissery and Yu-Sung Wu, "Enriching the Semantics of Information Flow Tracking with Source-Level Memory Allocation Event Logging," 2023 IEEE Conference on Dependable and Secure Computing (DSC), Tampa, FL, USA, 2023, pp. 1-10, doi: 10.1109/DSC61021.2023.10354156.
</div>

```BibTeX
@inproceedings{10354156,
  author={Mallissery, Sanoop and Wu, Yu-Sung},
  booktitle={2023 IEEE Conference on Dependable and Secure Computing (DSC)}, 
  title={Enriching the Semantics of Information Flow Tracking with Source-Level Memory Allocation Event Logging}, 
  year={2023},
  volume={},
  number={},
  pages={1-10},
  keywords={Analytical models;Runtime;Codes;Instruments;Computational modeling;Semantics;Memory management;code instrumentation;code analysis;dynamic information flow tracking code sanitization},
  doi={10.1109/DSC61021.2023.10354156}}
```
---

##### Related material

+ [Presentation slides](/2p.pdf)
