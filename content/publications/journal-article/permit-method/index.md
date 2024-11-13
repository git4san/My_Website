---
title: "Pervasive Micro Information Flow Tracking"
authors:
- Sanoop Mallissery
- Kun-Yi Chiang
- Chun-An Bau
- Yu-Sung Wu
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2024-07-15T00:00:00Z"
doi: ""

publishDate: "2024-07-15T00:00:00Z"
publication_types: ["article-journal"]

publication: "*IEEE Transactions on Dependable and Secure Computing* 21(4)"
publication_short: "IEEE TDSC"

abstract: "Detection of advanced security attacks that exploit zero-day vulnerabilities or application-specific logic loopholes has been challenging due to the lack of attack signatures or substantial deviations in the overall system behavior. One has to zoom in to the affected code regions and look for local anomalies distinguishable from the benign workload to detect such attacks. We propose pervasive micro information flow tracking ( PerMIT ) that realizes variable-level online dynamic information flow tracking (DIFT) as a means to detect the attacks. The system uses hardware virtualization extension to monitor access to taint source variables and performs asynchronous code emulation to infer the local information flow. We demonstrate that the pervasive micro information flow can sufficiently capture the attacks and incurs only a small overhead. Given the program source code, the system can further enrich the semantics of micro information flow by embedding the variable names. We have integrated the system with machine learning algorithms to demonstrate the effectiveness of anomaly detection for zero-day attacks with pervasive micro information flow."

summary: "This paper proposes Pervasive Micro Information Flow Tracking (PerMIT), a fine-grained approach for detecting complex security threats in software systems. By monitoring data flow at the micro level, PerMIT addresses zero-day vulnerabilities and logic flaws often missed by conventional security methods."

tags:
- Information Flow Tracking
- Security
- Software Security
- Zero-day Vulnerabilities
- PerMIT
featured: true

url_pdf: '/My_Paper/permit.pdf'
url_code: 'https://ieeexplore.ieee.org/abstract/document/10023951'
url_dataset: ''
url_poster: ''
url_project: 'AI-Driven Cybersecurity'
url_slides: ''
url_source: 'https://www.computer.org/csdl/journal/tq/2023/06/10023951/1K9syrJjOEM'
url_video: ''

image:
  caption: 'Micro-level Information Flow Tracking'
  focal_point: ""
  preview_only: false

projects:
  - "AI-Driven Cybersecurity"

---

##### Citation

<div class="citation">
Sanoop Mallissery, Kun-Yi Chiang, Chun-An Bau, and Yu-Sung Wu, "Pervasive Micro Information Flow Tracking," in IEEE Transactions on Dependable and Secure Computing, vol. 20, no. 6, pp. 4957-4975, Nov.-Dec. 2023, doi: 10.1109/TDSC.2023.3238547.
</div>

```BibTeX
@article{10023951,
  author={Mallissery, Sanoop and Chiang, Kun-Yi and Bau, Chun-An and Wu, Yu-Sung},
  journal={IEEE Transactions on Dependable and Secure Computing}, 
  title={Pervasive Micro Information Flow Tracking}, 
  year={2023},
  volume={20},
  number={6},
  pages={4957-4975},
  keywords={Target tracking;Security;Codes;Malware;Source coding;Emulation;Anomaly detection;Anomaly detection;dynamic information flow tracking;online taint analysis;production system;zero-day attacks},
  doi={10.1109/TDSC.2023.3238547}
}
```
---

##### Related material

+ [Presentation slides](/2p.pdf)
