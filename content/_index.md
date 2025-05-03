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
        My research investigates how **concepts change meaning over time**, especially in the mental health domain. Together with my PhD supervisors and collaborators, I have developed a set of approaches to model and measure lexical semantic change (LSC).
        - **SIBling:** A theoretical linguistic model that reduces six well-established types of LSC into three core dimensions: **Sentiment, Intensity, Breadth**. 
        - **SIB Toolkit:** A computational implementation of SIBling that measures change along these dimensions, as well as complementary features such as **salience**, **thematic content**.
        - **LSC-Eval** A three-stage evaluation framework that (1) generates synthetic datasets simulating kinds of LSC, (2) tests detection methods against these changes in controlled experiments, and (3) identifies optimal methods for each dimension/domain. 
        - **Application:** I use these tools to examine how mental health concepts like *schizophrenia* and *autism* have evolved historically, and to explore the influence of social and cultural forces such as **concept creep**, **pathologization**, and **stigmatization**.

        This program contributes by:
        1. Proposing a unified model of conceptual change (*SIBling*), grounded in historical linguistics and psychology.  
        2. Developing computational tools to quantify semantic change across the dimensions defined in the SIBling framework.
        3. Developing an evaluation framework (*LSC-Eval*) to test and refine change detection methods.  
        4. Demonstrating the framework’s utility in the mental health domain.  
        5. Laying the groundwork for extending the approach across domains (e.g., law, humanities) and languages.

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