---
# Homepage landing-page sections. The biography above comes from content/authors/admin/_index.md.
title: "Naomi Baes"
date: 2025-04-05
type: landing

design:
  spacing: "3rem"

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ""
      # CV button removed until /resume.pdf is updated (currently June 2026).
    design:
      css_class: dark
      background:
        color: black
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 0.7
          size: cover
          position: center
          parallax: false

  - block: markdown
    content:
      title: Research
      text: |
        How do societies change their interpretations of people, groups, and public issues? I use computational methods and social-psychological theory to study the language through which these interpretations are expressed. My research spans three connected areas:

        - **Language, framing, and cultural change.** I am developing a programme on how public discourse frames social groups and issues over time, including shifts in group boundaries, social identities, and inclusion. A central question is how to distinguish evidence of changing language from evidence of broader cultural change.
        - **Methods for studying meaning change.** I develop interpretable NLP methods and evaluation benchmarks to distinguish changes in semantic sentiment, intensity, breadth, and relations between word senses.
        - **Social and psychological applications.** I analyse mental health language, stigma, identity terminology, and dehumanization in historical corpora and online communities, linking computational measurements to social-psychological constructs.

        [Explore research areas](/research/)
    design:
      columns: 1
      css_class: research-overview-wide
      spacing:
        padding: ["1.5rem", "0", "1rem", "0"]

  - block: markdown
    content:
      title: Selected contributions
      text: |
        - **SIBling (ACL 2024).** Lead author of a framework for tracing semantic change across **Sentiment, Intensity, and Breadth**. [Paper](https://aclanthology.org/2024.acl-long.76/) · [Code](https://github.com/naomibaes/lexical_semantic_change_framework)
        - **LSC-Eval (Findings of ACL 2025).** Lead author of an evaluation framework using LLM-generated diachronic corpora to test what kinds of semantic change computational methods can detect. [Paper](https://aclanthology.org/2025.findings-acl.570/) · [Code](https://github.com/naomibaes/LSCD_method_evaluation)
        - **SenseRel (ACL 2026).** Joint first author of a benchmark for denotational and connotational relations between word senses, including evaluative meaning. [Paper](https://www.changeiskey.org/publication/2026-acl/2026.acl.pdf)
        - **Social meaning in public discourse (2026).** Lead author of [dehumanization research in incel discourse](https://ojs.aaai.org/index.php/ICWSM/article/view/42632) (*ICWSM*); joint first author of [historical identity-first and person-first language research](https://doi.org/10.1371/journal.pmen.0000684) (*PLOS Mental Health*) and a [benchmark for evaluating mental health stigma](https://arxiv.org/abs/2610.02775) (accepted at *AACL-IJCNLP*).
        - **Research community.** Program Chair of [LChange'26](https://www.changeiskey.org/event/2026-eacl-lchange/) and Australian English co-lead for SemEval 2026 Task 7, alongside programme-committee and peer-review service.

        [Recent updates](/updates/)
    design:
      columns: 1
      css_class: research-overview-wide
      spacing:
        padding: ["1rem", "0", "1rem", "0"]

  - block: collection
    id: papers
    content:
      title: Featured publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: markdown
    content:
      title: ""
      text: |
        <div style="text-align: center; margin-top: 0.5rem;">
          <a href="/publication/">View all publications</a>
        </div>
    design:
      columns: 1
      spacing:
        padding: ["0", "0", "0.5rem", "0"]

  - block: collection
    id: talks
    content:
      title: Selected talks
      filters:
        folders:
          - talks
        featured_only: true
    design:
      view: article-grid
      columns: 2
      spacing:
        padding: ["1.5rem", "0", "0", "0"]

  - block: markdown
    content:
      title: ""
      text: |
        <div style="text-align: center; margin-top: 0;">
          <a href="/talks/">View all presentations</a>
        </div>
    design:
      columns: 1
      spacing:
        padding: ["0", "0", "0.5rem", "0"]
---
