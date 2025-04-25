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
        My research program aims to understand **conceptual change**. To this end, I have developed four scalable components, together with my PhD supervisors and collaborators. 
        - **"SIBling"** is a theoretical linguistic model that reduces six well-established types of lexical semantic change (LSC) into three key dimensions: **Sentiment, Intensity, Breadth**. 
        - The **SIB Toolkit** is a computational implementation of SIBling. It measures change along these three core dimensions, and complementary variables (salience, thematic content) to uncover influential cultural forces.
        - **"LSC-Eval"** is a three-stage evaluation framework designed to (1) generate synthetic datasets simulating kinds of LSC, (2) use these to evaluate the sensitivity of various change detection methods, and (3) identify the most suitable approach for the dimension and domain of interest. 
        - I am currently **applying** *SIBling* to the mental health domain to examine how concepts like *schizophrenia* and *autism* have evolved over time, and to uncover  cultural forces (e.g., concept creep, pathologization, and stigmatization).

        This program of study makes four main contributions: 
        1. It introduces *SIBling*, a unified model of conceptual change grounded in historical linguistics and psychology, along with a methodological toolkit that draws on natural language processing and an evaluation framework (*LSC-Eval*) for testing and refining detection methods.
        2. It applies this toolkit to analyze semantic change in mental health discourse across historical corpora, spanning academic, media, and everyday language. 
        3. It positions *SIBling* as a cross-disciplinary resource for studying conceptual change and its cultural drivers in domains such as psychology, law, and the humanities.
        4. It lays the foundation for generalizing this model of conceptual change across other domains and languages. 
  
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