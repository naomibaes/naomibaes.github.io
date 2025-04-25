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
        My research program aims to understand conceptual change. 
        
        To this end, I have developed two novel and scalable frameworks with my PhD supervisors and collaborators. "SIBling" is a theoretical linguistic framework that proposes three major dimensions of lexical semantic change. "LSC-Eval" is a three-stage evaluation framework designed to generate synthetic datasets, use them to evaluate change detection methods, and identify the most suitable approach for the dimension and domain of interest. I am currently applying SIBling in the mental health domain to examine how concepts like *schizophrenia* and *autism* have evolved in meaning, and to uncover the social and cultural forces influencing this change.

        My work makes four main contributions: 
        - It establishes SIBling as a theoretical linguistic framework that reduces six main types of lexical semantic change, identified by historical linguists, into three major dimensions (Sentiment, Intensity, and Breadth) and develops a methodological toolkit to measure them, leveraging techniques from natural language processing and psychology. 
        - It harnesses this toolkit to analyze semantic shifts in mental health concepts in large historical text corpora representing discourse ranging from academic psychology to everyday vernacular, providing a window into cultural and social dynamics, such as concept creep, pathologization, and stigmatization. 
        - It positions SIBling as a valuable resource for researchers aiming to understand and model conceptual change and their social and cultural drivers in various disciplines (e.g., psychology, law, humanities).
        - It lays the groundwork to generalize and scale the study of conceptual change across domains and languages. 
  
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
        <div style="font-size: 0.9rem">

        - **July 21–24, 2025**: Presenting at *[IC2S2'25 Norrköping](https://www.ic2s2-2025.org/)*, International Conference for Computational Social Science on "SIBling" & "LSC-Eval" (Norrköping, Sweden).
        - New *corpus data* + *scripts* now available — see [Resources](https://naomibaes.github.io/resources/) tab.
        - Serving on the *[SEM 2025](https://www.aclweb.org/portal/content/14th-joint-conference-lexical-and-computational-semantics)* Program Committee, 14th Joint Conference on Lexical and Computational Semantics (co-located with EMNLP - Suzhou, China).

        </div>
    design:
      columns: 1
      css_class: mt-4

---