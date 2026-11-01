---
# Homepage landing-page sections. The biography above comes from content/authors/admin/index.md.
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
        How do societies change their understandings of people, groups, and public issues? I combine computational methods with social psychological theory to investigate how language reflects these changes. My research spans three connected areas:

        - **Language and cultural change.** I am developing research on how meanings, frames, and social representations evolve over time, and what these shifts may reveal about broader cultural processes.
        - **Computational methods.** I develop interpretable methods and evaluation benchmarks for measuring distinct dimensions of lexical semantic change.
        - **Social and psychological applications.** I study mental health language, stigma, identity, and dehumanization in historical text and online discourse.

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
        - **Methods for studying meaning change.** I led the development of [SIBling](https://aclanthology.org/2024.acl-long.76/) (ACL 2024) and [LSC-Eval](https://aclanthology.org/2025.findings-acl.570/) (Findings of ACL 2025), and co-developed [SenseRel](https://www.changeiskey.org/publication/2026-acl/2026.acl.pdf) (ACL 2026).
        - **Social and psychological applications.** My work examines [dehumanization](https://ojs.aaai.org/index.php/ICWSM/article/view/42632), [identity-related language](https://doi.org/10.1371/journal.pmen.0000684), and [mental health stigma](https://arxiv.org/abs/2610.02775) in public discourse.
        - **Research community.** I served as Program Chair of [LChange'26](https://www.changeiskey.org/event/2026-eacl-lchange/) and Australian English co-lead for SemEval 2026 Task 7, alongside reviewing and programme-committee service.

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
---
