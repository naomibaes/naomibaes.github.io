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
        
        I study how meanings shift as concepts move across scientific, media, and general-language contexts, especially when language carries social, cultural, or psychological significance. My work asks how mental health concepts and socially contested terms extend into new contexts, change in severity or emotional force, and acquire new evaluative associations. To examine these questions, I combine NLP methods with theory and concepts from social psychology, computational social science, and corpus linguistics, using historical text corpora, contextual embeddings, lexical resources, large language models, and statistical modeling.

        ### Research streams

        My work clusters around three overlapping streams: (1) historical semantic shifts in mental health concepts, (2) computational methods for semantic and conceptual change, and (3) collaborative computational social science projects on socially contested language.

        - **Mental health concepts and category boundaries**  

          I study how mental health concepts and terminology change over time across psychology, news media, books, and general language corpora. This stream examines how terms such as [*trauma*](/publication/journal-article_2023_plc/), *[mental illness](/publication/journal-article_2024_acl_sibling/)*, [*schizophrenia*](/publication/workshop-paper-2026_sense-prevalence/), and related [generic](/publication/journal-article_2024_acl_sibling/) and [emotion related](/publication/journal-article_2023_12_emnlp/) mental health terminology change in meaning, severity, salience, and use across domains, interpreted through the lens of psychological theory and concept creep research.

        - **Semantic and conceptual change**  
          I develop computational methods for tracing and evaluating different *kinds* of semantic change over time. This stream includes [**SIBling**](/publication/journal-article_2024_acl_sibling/) and [**LSC-Eval**](/publication/journal-article_2025_acl-findings/), my key framework and evaluation resource contributions for modeling whether words become broader, more emotionally intense, or come to acquire more positive or negative connotations across historical corpora. It also includes work on [diachronic word sense tracking](/publication/workshop-paper-2026_sense-prevalence/) and human-LLM representations of meaning ([**SenseRel**](/publication/journal-article_2026_acl-main/)).

        - **Computational social science**  
          I also contribute to collaborative projects that use NLP and computational social science methods to study socially important language, including [dehumanization](/publication/journal-article_2026_icwsm/) of women in incel discourse, mental health stigma detection in online communication, identity/person-first language for mental health conditions, and lay understandings of the [common good](/publication/journal-article_2024_4_bjsp/). These projects are related to my central interest in how language reflects social and psychological categories.

    design:
      columns: '1'
      css_class: research-overview-wide

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
      title: ''
      text: |
        <div style="text-align: center; margin-top: -3.5rem; margin-bottom: -1rem;">
          <a href="/publication/" style="display: inline-block; padding: 0.45rem 0.85rem; border: 1px solid #d1d5db; border-radius: 0.45rem; text-decoration: none; font-size: 0.9rem; font-weight: 400;">
            See all papers
          </a>
        </div>
    design:
      columns: 1
      spacing:
        padding: ["0", "0", "1rem", "0"]

  - block: markdown
    content:
      title: Highlights
      text: |
        <div style="font-size: 1rem">

        - **ACL 2026:** Joint-first author on *SenseRel*, a sense-level benchmark for denotational and connotational meaning relations, developed through my Change is Key! research internship.

        - **Findings of ACL 2025:** Lead author of **LSC-Eval**, a framework for evaluating methods for detecting dimensions of lexical semantic change using LLM-generated synthetic data.

        - **ACL 2024:** Lead author of **SIBling**, a multidimensional framework for modeling lexical semantic change with social science applications.

        - **ICWSM 2026:** Lead author of a computational social science [paper](https://naomibaes.github.io/publication/journal-article_2026_icwsm/) on dehumanization of women and men in incel discourse.

        - **Awards and research support:** Australian Government Research Training Program Scholarship; selected for Change is Key! research support for an international research internship and collaboration; supported by Concept Creep research funding for conference travel and research dissemination.

        - **Competitive team funding:** Co-recipient of **AUD $15,000 Hallmark Research Initiative seed funding** for a 7-member team project on 'Automatic evaluation of mental health stigma in online communication', led by Yulia Otmakhova.

        - **Research leadership and service:** Australian English Language Co-Lead with Christine de Kock for the [BLEnD SemEval-2026 Shared Task](https://arxiv.org/abs/2605.02601); Program Chair/PC for the [LChange'26 Workshop](https://www.changeiskey.org/event/2026-eacl-lchange/), co-located with EACL 2026.

        - **ACL Best Resource Paper Award:** Contributor to [**BRIGHTER: BRIdging the Gap in Human-Annotated Textual Emotion Recognition Datasets for 28 Languages**](https://aclanthology.org/2025.acl-long.436/), awarded Best Resource Paper at ACL 2025; contributed Romanian-language gold-standard annotation (team lead: Daniela Teodorescu).

        - **Invited talks:** Presented PhD work on modeling semantic change in mental-health concepts at international research groups: *Utrecht University*, the *University of Gothenburg*, and the *National Research Council Canada*.
        
        <div style="text-align: center; margin-top: 1.2rem;">
          <a href="/updates/" style="display: inline-block; padding: 0.45rem 0.85rem; border: 1px solid #d1d5db; border-radius: 0.45rem; text-decoration: none; font-size: 0.9rem; font-weight: 400;">
            See all updates
          </a>        
        </div>

        </div>
    design:
      columns: 1
      css_class: research-overview-wide
      spacing:
        padding: ["2rem", "0", "2rem", "0"]

  - block: collection
    id: talks
    content:
      title: Selected Presentations
      filters:
        folders:
          - talks
        featured_only: true
    design:
      view: article-grid
      columns: 2
      spacing:
        padding: ["2rem", "0", "0", "0"]

  - block: markdown
    content:
      title: ''
      text: |
        <div style="text-align: center; margin-top: -3.5rem; margin-bottom: -1rem;">
          <a href="/talks/" style="display: inline-block; padding: 0.45rem 0.85rem; border: 1px solid #d1d5db; border-radius: 0.45rem; text-decoration: none; font-size: 0.9rem; font-weight: 400;">
            See all presentations
          </a>
        </div>
    design:
      columns: 1
      spacing:
        padding: ["0", "0", "1rem", "0"]

  - block: markdown
    content:
      title: Research Ethos
      text: |
        <div style="font-size: 1rem">

        My work is motivated by substantive questions about language, meaning, mental health, and the shifting boundaries of social and psychological categories. I use computational methods and careful measurement to better understand how these categories change, and to make clearer, responsible claims about socially important questions. Theory only becomes useful empirically when we can make clear, interpretable, and well-grounded claims about what we are measuring.

        </div>
    design:
      columns: 1
      css_class: research-overview-wide
      spacing: 
        padding: ["2rem", "0", "2rem", "0"]

---