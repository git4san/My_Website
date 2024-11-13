---
# A section created with the Portfolio widget.
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: ''
subtitle: ''

content:
  page_type: project
  filter_default: 0
  filter_button:
    - name: All
      tag: '*'
    - name: Machine Learning
      tag: AIC
    - name: Security & Privacy
      tag: DPP
    - name: Systems Security
      tag: SSS
    - name: Fuzzing
      tag: OTS
    #- name: OT
    #  tag: SSS
    - name: IoT & IIoT
      tag: SPD

design:
  view: masonry
  columns: '1' # Still set to 1 for masonry
  css_class: custom-masonry
  spacing: { padding: [20, 20, 20, 20] }
---
