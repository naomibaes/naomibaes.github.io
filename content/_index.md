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

        - Delighted to share my PhD research in recent and upcoming invited talks in September at (1) the Change is Key! conference in Gothenburg, (2) University of Utrecht, (3) NRC Canada — and at the (4) Mental Health Conference this October!

        - **5 Aug – 30 Sept 2025** — [Interning](https://www.changeiskey.org/post/25-08-04-naomi-visit/) at **[Change is Key!](https://www.changeiskey.org/about/)**. The program develops computational tools to trace how language, society, and culture evolve, applying NLP and corpus methods to study semantic change and variation across linguistics, digital humanities, and the social sciences.

        - Happy to have presented our new method evaluation framework [**LSC-Eval**](https://naomibaes.github.io/publication/preprint_2025/): *A General Evaluation Framework for Assessing Methods for Measuring Lexical Semantic Change with LLM-Generated Synthetic Data*, at **[ACL 2025, Vienna](https://2025.aclweb.org/)** two frameworks for modeling conceptual change — [**SIBling**](https://naomibaes.github.io/publication/journal-article_2024_acl_sibling/) and [**LSC-Eval**](https://naomibaes.github.io/publication/preprint_2025/) — at *[IC2S2’25](https://www.ic2s2-2025.org/)* (Norrköping), the International Conference on Computational Social Science.
        
        - New *corpus data* and *scripts* publicly available — see [Resources](https://naomibaes.github.io/resources/) tab.

        </div>
    design:
      columns: 1
      css_class: mt-4
---