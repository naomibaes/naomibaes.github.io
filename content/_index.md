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
        My research investigates how concepts change their meaning, focusing on mental health. With my PhD supervisors, I have developed a novel linguistic framework (**SIBling**) and measures to model lexical semantic change (LSC) along three dimensions that are typically overlooked by existing approaches.  

        **Key Contributions:**
        - **SIBling:** A theoretical model integrating insights from historical linguistics and psychology, reducing six types of LSC into three core dimensions: **Sentiment, Intensity, and Breadth (SIB)**. [[Prototype]](https://naomibaes.github.io/publication/journal-article_2024_acl_sibling/)
        - **SIB Toolkit:** Our computational implementation of SIBling, quantifying semantic change across SIB, plus related features (**salience** and **thematic content**). Designed for broad application across the social sciences and language domains (scientific, media, everyday).  
        - **LSC-Eval:** An evaluation framework that uses LLM-generated synthetic corpora to simulate *kinds* of LSC and validate LSC detection methods, identifying optimal dimension- and domain-specific approaches. [[Prototype]](https://naomibaes.github.io/publication/preprint_2025/) 
        - **Applications:** I apply SIBling to trace the historical semantic evolution of mental health-related concepts (e.g., *autism*, *schizophrenia*), analysing related cultural dynamics like **concept creep**, **pathologisation**, and **stigmatisation**.  

        This program: (1) offers a multidimensional model of conceptual change (*SIBling*), (2) develops or identifies computational tools for its application, (3) establishes a principled evaluation framework for LSC detection methods (*LSC-Eval*), and (4) demonstrates its value through detailed case studies. This body of work lays the groundwork for future extensions across disciplines (e.g., law, humanities) and languages.
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

        - **July 22–24, 2025**: Come meet me at *[IC2S2'25](https://www.ic2s2-2025.org/)* (Norrköping, Sweden), the International Conference on Computational Social Science, where I’ll be presenting a **poster** on two frameworks for modeling — and evaluating methods for modeling — conceptual change: [**SIBling**](https://naomibaes.github.io/publication/journal-article_2024_acl_sibling/) and [**LSC-Eval**](https://naomibaes.github.io/publication/preprint_2025/).

        - **July 28, 2025**: Come meet me at **[ACL 2025](https://2025.aclweb.org/)** The 63rd Annual Meeting of the Association for Computational Linguistics (Vienna, Austria) during **Poster Session 5 (6:00–7:30 PM)**, where I’ll be presenting our ACL Findings paper — [**LSC-Eval**](https://naomibaes.github.io/publication/preprint_2025/): *A General Evaluation Framework for Assessing Methods for Measuring Lexical Semantic Change with LLM-Generated Synthetic Data.*

        - Excited to be interning with **[Change is Key!](https://www.changeiskey.org/about/)** — an international research program developing computational tools to trace how language, society, and culture evolve. It applies NLP and corpus-based methods to detect semantic change and variation, supporting interdisciplinary research across linguistics, digital humanities, and the social sciences.

        - Serving on the *[SEM 2025](https://www.aclweb.org/portal/content/14th-joint-conference-lexical-and-computational-semantics)* Program Committee — the 14th Joint Conference on Lexical and Computational Semantics (co-located with EMNLP in Suzhou, China).

        - Serving on the *[NLP4Democracy](https://sites.google.com/andrew.cmu.edu/nlp4democracy/)* Program Committee — the first workshop on NLP for Democracy, held at COLM 2025 (October 10, Montreal, Canada).

        - New *corpus data* and *scripts* publicly available — see [Resources](https://naomibaes.github.io/resources/) tab.

        </div>
    design:
      columns: 1
      css_class: mt-4

---