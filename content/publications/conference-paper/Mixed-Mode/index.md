---
title: 'Mixed-mode information flow tracking with compile-time taint semantics extraction and offline replay'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yu-Hsin Hung
  - Bing-Jhong Jheng
  - Hong-Wei Li
  - Wen-Yang Lai
  - Sanoop Mallissery
  - Yu-Sung Wu

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2021-01-30T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-01-30T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2021 IEEE Conference on Dependable and Secure Computing*
publication_short: In *DSC*

abstract: Static information flow analysis (IFA) and dynamic information flow tracking (DIFT) have been widely employed in offline security analysis of computer programs. As security attacks become more sophisticated, there is a rising need for IFA and DIFT in production environment. However, existing systems usually deal with IFA and DIFT separately, and most DIFT systems incur significant performance overhead. We propose MIT to facilitate IFA and DIFT in online production environment. MIT offers mixed-mode information flow tracking at byte-granularity and incurs moderate runtime performance overhead. The core techniques consist of the extraction of taint semantics intermediate representation (TSIR) at compile-time and the decoupled execution of TSIR for information flow analysis. We conducted an extensive performance overhead evaluation on MIT to confirm its applicability in production environment. We also outline potential applications of MIT, including the implementation of data provenance checking and information flow based anomaly detection in real-world applications.

# Summary. An optional shortened abstract.
summary: MIT, a mixed-mode information flow tracking system that integrates static information flow analysis (IFA) and dynamic information flow tracking (DIFT) for online production environments. MIT operates at byte-granularity with moderate performance overhead by utilizing taint semantics intermediate representation (TSIR) extracted at compile-time.

tags:
  - Information Flow Tracking (IFT)
  - Static Information Flow Analysis (IFA)
  - Dynamic Information Flow Tracking (DIFT)
  - Mixed-mode Tracking
  - Taint Analysis
  - Data Provenance Checking
  - Anomaly Detection


# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '/My_Paper/mixedmode.pdf'
url_code: 'https://ieeexplore.ieee.org/abstract/document/9346239'
url_dataset: ''
url_poster: ''
url_project: '/My_Paper_Slides/squirrel.pdf'
url_slides: '/My_Paper_Slides/mixedmode.pdf'
url_source: 'https://ieeexplore.ieee.org/document/9346239'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Mixed-Mode DIFT'
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
Yu-Hsin Hung, Bing-Jhong Jheng, Hong-Wei Li, Wen-Yang Lai, Sanoop Mallissery and Yu-Sung Wu, "Mixed-mode Information Flow Tracking with Compile-time Taint Semantics Extraction and Offline Replay," 2021 IEEE Conference on Dependable and Secure Computing (DSC), Aizuwakamatsu, Fukushima, Japan, 2021, pp. 1-8, doi: 10.1109/DSC49826.2021.9346239.
</div>

```BibTeX
@inproceedings{9346239,
  author={Hung, Yu-Hsin and Jheng, Bing-Jhong and Li, Hong-Wei and Lai, Wen-Yang and Mallissery, Sanoop and Wu, Yu-Sung},
  booktitle={2021 IEEE Conference on Dependable and Secure Computing (DSC)}, 
  title={Mixed-mode Information Flow Tracking with Compile-time Taint Semantics Extraction and Offline Replay}, 
  year={2021},
  volume={},
  number={},
  pages={1-8},
  keywords={Runtime;Target tracking;Runtime library;Semantics;Memory management;Servers;Anomaly detection;decoupled dynamic information flow tracking;static information flow tracking;taint propagation;application logic vulnerabilities;anomaly detection},
  doi={10.1109/DSC49826.2021.9346239}}
```
---

##### Related material

+ [Presentation slides](/2p.pdf)
