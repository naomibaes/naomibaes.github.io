---
# Leave the homepage title empty to use the site title
title: "Naomi Baes"
date: 2025-04-05
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within content/authors/)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to assets/media/.
          filename: stacked-peaks.svg
          filters:
            brightness: 0.7
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: 'Research Program'
      subtitle: ''
      text: |-
        My research investigates how concepts change meaning over time, with a focus on the mental health domain. With my PhD supervisors, I have developed a novel framework - **SIBling** - to model and measure lexical semantic change (LSC) along three dimensions that are typically overlooked by existing approaches, which treat semantic change as unitary.  
        - **SIBling:** A theoretical model that integrates insights from historical linguistics and psychology, reducing six established types of LSC into three core dimensions: **Sentiment, Intensity, and Breadth**. [Prototype paper](https://naomibaes.github.io/publication/journal-article_2024_acl_sibling/).
        - **SIB Toolkit:** A computational implementation of the framework that quantifies change along these dimensions, as well as related features: **salience** and **thematic content**.  
        - **LSC-Eval:** An evaluation pipeline designed to validate methods for detecting LSC. It (1) creates LLM-generated synthetic corpora simulating *kinds* of change, (2) tests detection methods in controlled experiments, and (3) identifies optimal approaches for dimensions and domains. [Prototype paper](https://naomibaes.github.io/publication/preprint_2025/) 
        - **Applications:** I apply this framework to trace the historical semantic evolution of mental health-related concepts (e.g., *autism*, *schizophrenia*), and to analyse related social and cultural dynamics such as **concept creep**, **pathologisation**, and **stigmatisation**.  
        This program contributes by:
        1. Proposing a multidimensional model of conceptual change (*SIBling*) grounded in psychological and linguistic theory.    
        2. Developing computational tools to operationalise and apply the framework across concepts and domains.  
        3. Establishing a principled evaluation framework (*LSC-Eval*) for testing LSC methods.  
        4. Demonstrating the value of *SIBling* through detailed case studies in the mental health domain.  
        5. Laying the groundwork for future extensions across domains (e.g., law, humanities) and languages.  

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
      title: Relevant Publications
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
      title: Invited Talks
      filters:
        folders:
          - talks
        featured_only: true
    design:
      view: article-grid
      columns: 1
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      filters:
        folders:
          - news
        exclude_folders:
          - resources
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      page_type: post
      count: 5
      offset: 0
      order: desc
    design:
      view: date-title-summary
      spacing:
        padding: [0, 0, 0, 0]

  - block: markdown
    content:
      title: Quick Updates
      text: |
        <div style="font-size: 1rem">

        - **July 21–24, 2025**: Accepted to present at *[IC2S2'25 Norrköping](https://www.ic2s2-2025.org/)*, the International Conference for Computational Social Science, on my frameworks for modelling, and evaluating methods for assessing, conceptual change: "SIBling" & "LSC-Eval" (Norrköping, Sweden).

        - New *corpus data* + *scripts* now publicly available — see [Resources](https://naomibaes.github.io/resources/) tab.

        - Committed my recent PhD paper to **[ACL 2025](https://2025.aclweb.org/)** - read our preprint [here](https://arxiv.org/abs/2503.08042)

        - Serving on the *[SEM 2025](https://www.aclweb.org/portal/content/14th-joint-conference-lexical-and-computational-semantics)* Program Committee, 14th Joint Conference on Lexical and Computational Semantics (co-located with EMNLP - Suzhou, China).

        </div>
    design:
      columns: 1
      css_class: mt-4

---