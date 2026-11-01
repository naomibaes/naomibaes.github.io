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
        What can changes in language tell us about how societies understand socially important concepts, groups, and public issues? I draw on social psychology and linguistics alongside computational methods to investigate conceptual change and its relationship to broader social and cultural processes.

        My research has three interconnected strands:

        - **Language and cultural change.** I investigate how the meanings of socially important concepts change over time, including concept creep (the semantic expansion of harm-related concepts), and am extending this interest to how social groups and public issues are represented and framed over time.
        - **Computational methods and evaluation.** I develop and evaluate interpretable methods and benchmarks for measuring distinct dimensions of lexical semantic change, with particular attention to construct validity.
        - **Social and psychological applications.** I study mental health concepts, stigma, identity-related language, and dehumanization in historical texts and online discourse.

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
        - **Computational frameworks.** I led the development of [SIBling](https://aclanthology.org/2024.acl-long.76/) (ACL 2024), a reusable framework for measuring semantic change across Sentiment, Intensity, and Breadth, and [LSC-Eval](https://aclanthology.org/2025.findings-acl.570/) (Findings of ACL 2025), an framework for evaluating semantic change methods using LLM-generated data. I also co-developed the sense relations benchmark [SenseRel](https://www.changeiskey.org/publication/2026-acl/2026.acl.pdf) (ACL 2026).
        - **Conceptual change in mental health.** SIBling has been applied in multiple studies of semantic shifts in mental health concepts, including [ADHD](https://doi.org/10.1016/j.ssmmh.2026.100710) and [schizophrenia](https://aclanthology.org/2026.lchange-1.5/), to investigate changes in semantic breadth, sentiment and intensity, changes relevant to concept creep. My earlier research also examined the [semantic inflation of trauma](https://doi.org/10.58734/plc-2023-0002).
        - **Social and psychological research.** My work also examines [dehumanization](https://ojs.aaai.org/index.php/ICWSM/article/view/42632), [identity-related language](https://doi.org/10.1371/journal.pmen.0000684), and [mental health stigma](https://arxiv.org/abs/2610.02775) in public discourse.
        - **Research community.** I served as Program Chair of [LChange'26](https://www.changeiskey.org/event/2026-eacl-lchange/) and Australian English co-lead for [SemEval 2026 Task 7](https://aclanthology.org/2026.semeval-1.455/), alongside reviewing and programme committee service.

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
