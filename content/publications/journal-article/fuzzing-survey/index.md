---
title: "Demystify the fuzzing methods: A comprehensive survey"
authors:
- Sanoop Mallissery
- Yu-Sung Wu
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2023-10-05T00:00:00Z"
doi: ""

abstract: Massive software applications possess complex data structures or parse complex data structures; in such cases, vulnerabilities in the software become inevitable. The vulnerabilities are the source of cyber-security threats, and discovering this before the software deployment is challenging. Fuzzing is a vulnerability discovery solution that resonates with random-mutation, feedback-driven, coverage-guided, constraint-guided, seed-scheduling, and target-oriented strategies. Each technique is wrapped beneath the black-, white-, and grey-box fuzzers to uncover diverse vulnerabilities. It consists of methods such as identifying structural information about the test cases to detect security vulnerabilities, symbolic and concrete program states to explore the unexplored locations, and full semantics of code coverage to create new test cases. We methodically examine each kind of fuzzers and contemporary fuzzers with a profound observation that addresses various research questions and systematically reviews and analyze the gaps and their solutions. Our survey comprised the recent related works on fuzzing techniques to demystify the fuzzing methods concerning the application domains and the target that, in turn, achieves higher code coverage and sound vulnerability detection.

# Summary. An optional shortened abstract.
summary: This work explores fuzzing as a solution to uncover vulnerabilities in complex software applications, which pose cybersecurity risks. It reviews various fuzzing techniques—random mutation, feedback-driven, and constraint-guided—across black-, white-, and grey-box fuzzers. The study highlights how these methods detect vulnerabilities through structural test case analysis, symbolic program states, and code coverage. It also identifies gaps in current fuzzing techniques and suggests improvements for better vulnerability detection.

tags:
- Fuzzing
- Vulnerabilities
- Cybersecurity
- Software Security
- Code Coverage
- Black-box Fuzzing
- White-box Fuzzing
- Grey-box Fuzzing
- Vulnerability Detection
- Security Testing

featured: true

url_pdf: https://wcventure.github.io/FuzzingPaper/Paper/ACM_CSUR22_Demystify_Fuzzing.pdf
url_code: 'https://dl.acm.org/doi/10.1145/3623375'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Constraint-guided Fuzzing Process'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - "Fuzzing OT Apps"

---

##### Citation

Sanoop Mallissery and Yu-Sung Wu. 2023. Demystify the Fuzzing Methods: A Comprehensive Survey. ACM Comput. Surv. 56, 3, Article 71 (March 2024), 38 pages. https://doi.org/10.1145/3623375.

```BibTeX
@article{10.1145/3623375,
author = {Mallissery, Sanoop and Wu, Yu-Sung},
title = {Demystify the Fuzzing Methods: A Comprehensive Survey},
year = {2023},
issue_date = {March 2024},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
volume = {56},
number = {3},
issn = {0360-0300},
url = {https://doi.org/10.1145/3623375},
doi = {10.1145/3623375},
journal = {ACM Comput. Surv.},
month = oct,
articleno = {71},
numpages = {38},
keywords = {vulnerability discovery, code inspection, fuzzing, Automated testing}
}
```

---

##### Related material

+ [Presentation slides](/2p.pdf)

