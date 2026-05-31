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
        
        I study how meanings shift as concepts move across scientific, media, and everyday contexts, especially in domains where language carries social, cultural, and psychological significance. My work focuses on questions about mental health concepts, social representation, and contested language: how terms expand to new contexts, shift in severity or emotional force, acquire new evaluative associations, or become embedded in dehumanizing and stigmatizing patterns of language use. To answer these questions, I combine methods from NLP, computational social science, and psychology, including historical text corpora, contextual embeddings, lexical resources, large language models, and statistical modeling.

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

        - **ACL 2026:** Equal-first author on *SenseRel*, a sense-level benchmark for denotational and connotational meaning relations, developed through my Change is Key! research internship.

        - **Findings of ACL 2025:** Lead author of **LSC-Eval**, a framework for evaluating methods for detecting dimensions of lexical semantic change using LLM-generated synthetic data.

        - **ACL 2024:** Lead author of **SIBling**, a multidimensional framework for modeling lexical semantic change with social science applications.

        - **ICWSM 2026:** Lead author of a computational social science paper on dehumanization of women versus men in incel discourse.

        - **Individual awards and research support:** Australian Government Research Training Program Scholar; recipient of selected Change is Key! research support for an international research internship and collaboration; supported by Concept Creep research funding for conference travel and research dissemination.

        - **Competitive team funding:** Co-recipient of **AUD $15,000 Hallmark Research Initiative seed funding** for a 7-member team project on 'Automatic evaluation of mental health stigma in online communication', led by Yulia Otmakhova.

        - **Shared-task and workshop leadership:** Australian English Language Co-Lead with Christine de Kock for the BLEnD SemEval-2026 Shared Task; Program Chair/PC for LChange'26, co-located with EACL 2026.

        - **Community resources:** Contributor to the ACL 2025 Best Resource Paper Award-winning **BRIGHTER** dataset, providing Romanian-language gold-standard annotation (team lead: Daniela Teodorescu).

        - **Invited talks:** Presented PhD work on modeling semantic change in mental health concepts at *Utrecht University*, the *University of Gothenburg*, the *National Research Council Canada*, and the University of Melbourne *Mental Health PhD Program*.

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

  - block: markdown
    content:
      title: Research Ethos
      text: |
        <div style="font-size: 1rem">

        My work is motivated by substantive questions about language, meaning, and social life. I see computational methods and careful measurement as tools for answering those questions responsibly: theory only becomes useful empirically when we can make clear, interpretable, and well-grounded claims about what we are measuring.

        </div>
    design:
      columns: 1
      css_class: mt-4



---
