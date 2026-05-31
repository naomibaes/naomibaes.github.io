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
      title: 'Research Overview'
      subtitle: ''
      text: |-

        I develop theory-informed computational methods for studying how meanings change in mental health, media, and socially contested language. My work sits at the intersection of NLP, computational social science, and psychology, combining historical text corpora, contextual embeddings, lexical resources, large language models, and statistical modeling.

        **Research streams**

        **Semantic and conceptual change**  
        Methods for studying how meanings shift across time, including multidimensional approaches to lexical semantic change and synthetic benchmarks for method evaluation.  
        Key work: [SIBling](/publication/journal-article_2024_acl_sibling/), [LSC-Eval](/publication/preprint_2025/), [Diachronic WSD](/publication/workshop-paper-2026_sense-prevalence/).

        **Mental health language and media discourse**  
        Applications to mental-health concepts and terminology, examining how meanings and representations shift across psychology, news media, books, and everyday language.  
        Selected work: case studies of *trauma*, *schizophrenia*, generic and emotion mental health terminology, and collaborative projects on *ADHD*, *anxiety* and *depression*.

        **Meaning representations in humans and language models**  
        Benchmarking how humans and language models represent word meanings, senses, connotation, denotation, valence, and arousal.  
        Key work: [SenseRel](/publication/journal-article_2026_acl-main/), [LSC-Eval](/publication/preprint_2025/).

        **Socially contested language**  
        Computational social science work on evaluative, dehumanizing, identity-related, and contested language in online and public discourse.  
        Selected collaborative work: ICWSM dehumanization paper, mental-health stigma benchmark, identity/person-first language paper, and common-good work.

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

  - block: markdown
    content:
      title: Highlights
      text: |
        <div style="font-size: 1rem">

        - **ACL 2026:** Joint-first author on *SenseRel*, a sense-level benchmark for denotational and connotational meaning relations, from my Change is Key! internship (https://www.changeiskey.org/post/25-08-04-naomi-visit/).

        - **ICWSM 2026:** Lead author of a computational social science paper on dehumanization in incel discourse.

        - **Research funding:** Co-recipient of **AUD $15,000 Hallmark Research Initiative seed funding** (team of 7) for a project on automatic evaluation of mental-health stigma in online communication, led by the amazing Yulia Otmakhova(https://scholar.google.com/citations?user=yzaozUUAAAAJ&hl=en).

        - **Leadership and service:** Australian English Language Co-Lead with Christine De Kock for the BLEnD SemEval-2026 Shared Task(https://www.codabench.org/competitions/10281/); Program Chair/PC for LChange'26 Workshop (https://www.changeiskey.org/event/2026-eacl-lchange/); Romanian dataset contributos to the ACL 2025 Best Resource Paper Award-winning BRIGHTER dataset (https://aclanthology.org/2025.acl-long.436/).

        - **Invited talks:** Presented work on semantic change at Utrecht University, the University of Gothenburg, the National Research Council Canada, and the University of Melbourne Mental Health PhD Program.

        - **Findings of ACL 2025:** Lead author of **LSC-Eval**, a framework for evaluating methods for detecting dimensions of lexical semantic change using LLM-generated synthetic data.

        - **ACL 2024:** Lead author of **SIBling**, a multidimensional framework for modeling lexical semantic change with social science applications.

        </div>
    design:
      columns: 1
      css_class: mt-4

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
      title: Selected Talks
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


---
