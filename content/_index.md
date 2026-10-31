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
      button:
        text: CV
        url: /resume.pdf
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
        I study how the language used to describe people and social issues changes over time, and what these changes can tell us about broader shifts in social and cultural interpretation. My work connects natural language processing with social-psychological theory through three overlapping lines of research:

        - **Language, framing, and cultural change.** My current research is moving beyond changes in individual word meanings to examine how social groups and public issues are framed over time. I am especially interested in linking changes in discourse to social identities, stereotypes, and the boundaries of social inclusion, while distinguishing linguistic evidence from broader claims about cultural change.
        - **Methods for measuring meaning change.** I develop and evaluate interpretable computational methods for distinguishing different kinds of semantic change, including shifts in sentiment, intensity, breadth, and relations between senses.
        - **Social and psychological applications.** I investigate language about mental health, stigma, identity, and dehumanization, using historical corpora and online discourse to study how socially important concepts and groups are represented and evaluated.

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
        - **Social meaning in public discourse (2026).** Studies of [dehumanization in incel communities](https://ojs.aaai.org/index.php/ICWSM/article/view/42632) (*ICWSM*), [identity-first and person-first language](https://doi.org/10.1371/journal.pmen.0000684) (*PLOS Mental Health*), and the automatic evaluation of mental health stigma in online communication (accepted at *AACL-IJCNLP*).
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
        <div style="text-align: center; margin-top: -2rem;">
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
