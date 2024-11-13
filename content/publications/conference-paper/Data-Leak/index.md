---
title: 'Data leakage detection for health information system based on memory introspection'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Sanoop Mallissery
  - Min-Chieh Wu
  - Chun-An Bau
  - Guan-Zhang Huang
  - Chen-Yu Yang
  - Wei-Chun Lin
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
publication: In *Proceedings of the 15th ACM Asia Conference on Computer and Communications Security*
publication_short: In *ACM ASIA CCS*

abstract: The abundance of highly sensitive personal information in the Health Information System (HIS) has made it a prime target of data breach attacks. However, securing the system with existing Data Leakage Prevention (DLP) solutions is difficult due to a lack of security perimeter and diverse composition of software components. We propose the use of hypervisor-based memory introspection for implementing data leakage detection in such an environment. The approach looks for the presence of sensitive raw data in the memory of both the client machines and the server machines, transcending the dependence of pre-existing security perimeters. It is inherently compatible with different types of application software and robust against transport or at-rest data encryption. A prototype has been built on the Bareflank hypervisor and the OpenEMR platform. The evaluation results confirmed the effectiveness of the approach.

# Summary. An optional shortened abstract.
summary: The proposed hypervisor-based memory introspection method detects data leakage in Health Information Systems (HIS), which are at risk of data breaches due to sensitive personal information. This approach identifies sensitive data in the memory of both client and server machines, overcoming the limitations of traditional Data Leakage Prevention (DLP) solutions that depend on security perimeters. It is compatible with various applications and resilient against encryption. A prototype developed with the Bareflank hypervisor and OpenEMR demonstrated effective results in detecting data leakage.

tags:
  - Data Leakage Prevention (DLP)
  - Health Information Systems (HIS)
  - Hypervisor-Based Memory Introspection
  - Data Breach Detection
  - Sensitive Data Protection
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
Sanoop Mallissery, Min-Chieh Wu, Chun-An Bau, Guan-Zhang Huang, Chen-Yu Yang, Wei-Chun Lin, and Yu-Sung Wu. 2020. POSTER: Data Leakage Detection for Health Information System based on Memory Introspection. In Proceedings of the 15th ACM Asia Conference on Computer and Communications Security (ASIA CCS '20). Association for Computing Machinery, New York, NY, USA, 898–900. https://doi.org/10.1145/3320269.3405437
</div>

```BibTeX
@inproceedings{10.1145/3320269.3405437,
author = {Mallissery, Sanoop and Wu, Min-Chieh and Bau, Chun-An and Huang, Guan-Zhang and Yang, Chen-Yu and Lin, Wei-Chun and Wu, Yu-Sung},
title = {POSTER: Data Leakage Detection for Health Information System based on Memory Introspection},
year = {2020},
isbn = {9781450367509},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3320269.3405437},
doi = {10.1145/3320269.3405437},
booktitle = {Proceedings of the 15th ACM Asia Conference on Computer and Communications Security},
pages = {898–900},
numpages = {3},
keywords = {convolutional neural networks, data privacy, electronic health record, health information system, memory inspection, virtualization},
location = {Taipei, Taiwan},
series = {ASIA CCS '20}
}
```
---

##### Related material

+ [Presentation slides](/2p.pdf)
