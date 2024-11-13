---
title: 'Identification of data propagation paths for efficient dynamic information flow tracking'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Sanoop Mallissery
  - Yu-Sung Wu
  - Chih-Hao Hsieh
  - Chun-An Bau

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2020-03-30T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2020-03-30T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 35th Annual ACM Symposium on Applied Computing*
publication_short: In *ACM SAC*

abstract: Dynamic information flow tracking is a positive step towards the prevention of untrusted data injection and protection from possible exploits of such data. This emphasizes the importance of tracking the suspicious data flows at run-time to ensure neither the exploitation of data nor security violation. In this work, we have contemplated enhancing the competence of Static Taint Tracking (STT) to seamlessly support Dynamic Taint Tracking (DTT) using data flow analysis. The concept of definition-used (def-use) is used for source code analysis to capture the potential taint propagation paths represented using the Data Flow Graph (DFG). The extracted paths from the DFG provides prior information about all the potential taint propagation paths which extensively needed to be considered for DTT. We have tested our proposed methodology on some well-known benchmarks such as Firefox, SQLite3, Gzip, and Zlib. It is observed that the proposed method can identify all potential taint source propagation paths that cover pointers, branch conditions, inter-procedure, and inter-module data flows. The evaluation results show that this work will be very useful in guiding the dynamic taint tracking to achieve efficient and accurate detection of suspicious information flow.

# Summary. An optional shortened abstract.
summary: This work enhances Dynamic Information Flow Tracking (DIFT) to prevent data injection exploits by extending Static Taint Tracking (STT) with data flow analysis. Using a Data Flow Graph (DFG), it maps taint propagation paths to improve tracking accuracy. Tests on Firefox, SQLite3, Gzip, and Zlib show effective identification of complex taint paths, aiding efficient and precise detection of suspicious data flows.

tags:
  - Static Taint Tracking
  - Dynamic Information Flow Tracking
  - definition-used (def-use)
  - Data Breach Detection
  - Suspicious Data Flow
  - Security Perimeter

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '/My_Paper/dataleak.pdf'
url_code: 'https://dl.acm.org/doi/abs/10.1145/3320269.3405437'
url_dataset: ''
url_poster: ''
url_project: '/My_Paper_Slides/dataleak.pdf'
url_slides: '/My_Paper_Slides/dataleak.pdf'
url_source: 'https://dl.acm.org/doi/10.1145/3320269.3405437'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Sensitive Data Identification'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - AI-Driven Cybersecurity
  - Privacy Preservation Mechanisms
  - Explainable and Interpretable AI

---

##### Citation

<div class="citation">
Sanoop Mallissery, Yu-Sung Wu, Chih-Hao Hsieh, and Chun-An Bau. 2020. Identification of data propagation paths for efficient dynamic information flow tracking. In Proceedings of the 35th Annual ACM Symposium on Applied Computing (SAC '20). Association for Computing Machinery, New York, NY, USA, 92–99. https://doi.org/10.1145/3341105.3373876.
</div>

```BibTeX
@inproceedings{10.1145/3341105.3373876,
author = {Mallissery, Sanoop and Wu, Yu-Sung and Hsieh, Chih-Hao and Bau, Chun-An},
title = {Identification of data propagation paths for efficient dynamic information flow tracking},
year = {2020},
isbn = {9781450368667},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3341105.3373876},
doi = {10.1145/3341105.3373876},
booktitle = {Proceedings of the 35th Annual ACM Symposium on Applied Computing},
pages = {92–99},
numpages = {8},
keywords = {information flow tracking, software security, source code analysis, static taint tracking, taint analysis and propagation},
location = {Brno, Czech Republic},
series = {SAC '20}
}
```
---

##### Related material

+ [Presentation slides](/2p.pdf)
