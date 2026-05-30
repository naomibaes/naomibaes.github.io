---
# Leave the homepage title empty to use the site title
title: "Naomi Baes"
date: 2025-04-05
type: landing

design:
  # Default section spacing
  spacing: "3rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within content/authors/)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: CV
        url: /resume.pdf
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

        Broadly, my research uses computational methods to study how meanings and concepts change over time, and how those shifts reflect wider cultural and social dynamics. At the intersection of NLP, computational social science, and psychology, I develop theory-informed approaches for tracing semantic and conceptual change in historical text corpora using contextual embeddings, large language models, lexical resources, and statistical modeling. My current work focuses especially on mental health language, media discourse, and socially contested language.

        **Research themes**

        **Semantic and conceptual change**  
        Methods for studying how meanings shift across time, including multidimensional approaches to lexical semantic change and synthetic benchmarks for method evaluation.  
        Key work: [SIBling](/publication/journal-article_2024_acl_sibling/), [LSC-Eval](/publication/preprint_2025/), [Schizophrenia WSD](/publication/workshop-paper-2026_sense-prevalence/).

        **Mental health language and media discourse**  
        Applications to mental-health concepts and terminology, examining how meanings and representations shift across psychology, news media, books, and everyday language.  
        Key work: trauma, schizophrenia, ADHD, anxiety/depression, and generic mental-health terminology papers.

        **Meaning representations in humans and language models**  
        Benchmarking how humans and language models represent word meanings, senses, connotation, denotation, valence, and arousal.  
        Key work: [SenseRel](/publication/journal-article_2026_acl-main/), [LSC-Eval](/publication/preprint_2025/).

        **Socially contested language**  
        Computational social science work on evaluative, dehumanizing, identity-related, and contested language in online and public discourse.  
        Key work: ICWSM dehumanization paper, mental-health stigma benchmark, identity/person-first language paper, and common-good work.

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
      title: Selected Publications
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
      title: Highlights
      text: |
        <div style="font-size: 1rem">

        - New sense-tracking pipeline for estimating the prevalence of word senses in historical text corpora: [link](https://www.linkedin.com/feed/update/urn:li:activity:7443471238037106688/?originTrackingId=xIHOlBlkEQxOUDp18rzxEQ%3D%3D)

        - Delighted to share my PhD research at (1) the Change is Key! conference in Gothenburg (Sweden), (2) University of Utrecht (Netherlands), (3) National Research Council Canada, (4) the Mental Health PhD Program Conference!, and (5) The LChange'26 Workshop, colocated with EACL.

        - **5 Aug – 30 Sept 2025** — [Interned](https://www.changeiskey.org/post/25-08-04-naomi-visit/) at **[Change is Key!](https://www.changeiskey.org/about/)**. The program develops computational tools to trace how language, society, and culture evolve, applying NLP and corpus methods to study semantic change and variation across linguistics, digital humanities, and the social sciences.

        - *Corpus data* and *scripts* publicly available — see [Resources](https://naomibaes.github.io/resources/) tab.

        </div>
    design:
      columns: 1
      css_class: mt-4
---
