---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download Resume
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: test2.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        <div class="justified-text">
        My research is dedicated to advancing the security and privacy of critical systems using cutting-edge techniques. I design innovative tools and methodologies to detect and mitigate complex security threats, including zero-day vulnerabilities and application-specific logic flaws, particularly in software applications and critical infrastructure like Operational Technology (OT) and Industrial Control Systems (ICS). 

        **Contributions:**

        - **Pervasive Micro Information Flow Tracking (PerMIT):** A fine-grained solution to detect sophisticated security threats by monitoring and managing data flows at a micro level within applications.
        - **SQUIRREL Tool:** An advanced tool that enhances information flow tracking with source-level memory allocation event logging, providing deep insights into application behaviors and vulnerabilities at the code level.
        - **Privacy-Preserving Mechanisms:** Researching and developing comprehensive privacy solutions across the data lifecycle, utilizing cryptographic methods and differential privacy to ensure data security and regulatory compliance.
        - **Securing Communication Devices:** Investigating physical and software-based mechanisms to protect modern communication devices, addressing various vulnerabilities from hardware to software layers.
        - **Machine Learning (ML) Integration:** Leveraging ML for anomaly detection and predictive security, enabling automated identification and mitigation of threats with increased efficiency.
    
        **Focus Areas:**
        
        - **OT/ICS Security:** Strengthening the defenses of critical infrastructures like SCADA systems against evolving cyber threats, ensuring their safety and reliability.
        
        - **Data Privacy:** Developing and deploying privacy-preserving methods such as k-anonymity, differential privacy, and federated learning to secure sensitive information throughout its lifecycle.
        - **Fuzzing Techniques:** Innovating fuzzing approaches that combine AFL, symbolic, and concolic execution to uncover new software vulnerabilities, particularly those hidden in complex software systems.

        My work bridges theoretical advancements with practical implementation, contributing significantly to dependable system security, software security, and data privacy. By focusing on real-world applications, I aim to create impactful solutions that enhance the resilience and security of mission-critical systems.

        Please reach out to collaborate 😃 😃 
        </div>
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!
        
        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
