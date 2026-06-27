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
      title: "Methods, tools, and applications"
      text: |
        I develop computational tools for measuring how word meanings change over time. My work sits between basic science and application: I build methods for studying semantic change, then apply them to culturally important language about mental health, harm, identity, and social evaluation.

        <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)); gap: 1rem; margin-top: 1.4rem;">

          <div style="border: 1px solid #e5e7eb; border-radius: 0.8rem; padding: 1rem; background: #fff;">
            <h3 style="margin-top: 0;">SIBling</h3>
            <p>A multidimensional framework for measuring semantic change across <strong>Sentiment</strong>, <strong>Intensity</strong>, and <strong>Breadth</strong>.</p>
            <p style="font-size: 0.95rem;">Useful for studying broadening, emotional intensification, evaluative shift, concept creep, and changing mental health language.</p>
            <p><a href="/publication/journal-article_2024_acl_sibling/">Paper</a> · <a href="https://github.com/naomibaes/lexical_semantic_change_framework">Code</a></p>
          </div>

          <div style="border: 1px solid #e5e7eb; border-radius: 0.8rem; padding: 1rem; background: #fff;">
            <h3 style="margin-top: 0;">LSC-Eval</h3>
            <p>An evaluation framework for testing whether semantic change methods detect specific kinds of change under controlled conditions.</p>
            <p style="font-size: 0.95rem;">Useful for method evaluation, synthetic diachronic corpora, benchmarking, and interpretable NLP.</p>
            <p><a href="/publication/journal-article_2025_acl-findings/">Paper</a> · <a href="https://github.com/naomibaes/LSCD_method_evaluation">Code</a></p>
          </div>

          <div style="border: 1px solid #e5e7eb; border-radius: 0.8rem; padding: 1rem; background: #fff;">
            <h3 style="margin-top: 0;">Sense tracking</h3>
            <p>A threshold-calibrated pipeline for estimating how the prevalence of a word's senses changes across historical corpora.</p>
            <p style="font-size: 0.95rem;">Useful for distinguishing contextual change from shifts in literal, metaphorical, or diagnostic senses.</p>
            <p><a href="/publication/workshop-paper-2026_sense-prevalence/">Project</a></p>
          </div>

          <div style="border: 1px solid #e5e7eb; border-radius: 0.8rem; padding: 1rem; background: #fff;">
            <h3 style="margin-top: 0;">Substantive applications</h3>
            <p>I apply these tools to changing social and psychological concepts, including mental health language, diagnostic terms such as <em>schizophrenia</em>, and broader language about harm, stigma, identity, and social evaluation.</p>
            <p style="font-size: 0.95rem;">These applications show how computational methods can help study changing cultural understandings of harm, disorder, identity, and social evaluation.</p>
            <p><a href="/research/mental-health-language/">Mental health</a> · <a href="/research/social-meaning/">Social meaning</a></p>
          </div>

        </div>
    design:
      columns: 1
      css_class: research-overview-wide
      spacing:
        padding: ["2rem", "0", "2rem", "0"]

  - block: markdown
    content:
      title: Highlights
      text: |

        Selected work showing methodological contribution, uptake, and recognition.

        - **SIBling — reusable framework for measuring semantic change:** Lead author, [**ACL 2024 Main**](https://naomibaes.github.io/publication/journal-article_2024_acl_sibling/). Introduced a multidimensional framework and toolkit for measuring semantic change across **Sentiment, Intensity, and Breadth**. **Impact:** provides a way to distinguish broadening, emotional intensification, and evaluative shift rather than collapsing them into a single change score. **Uptake:** applied and extended in [computational linguistics](https://www.changeiskey.org/event/2026-eacl-lchange/slides/18.pdf) to track semantic change in Japanese economic news, and in social psychology to study concept creep in mental health concepts. [[paper](https://aclanthology.org/2024.acl-long.76/) · [code](https://github.com/naomibaes/lexical_semantic_change_framework)]

        - **LSC-Eval — controlled evaluation for semantic change methods:** Lead author, [**ACL Findings 2025**](https://naomibaes.github.io/publication/journal-article_2025_acl-findings/). Developed an evaluation framework using LLM generated diachronic synthetic corpora to test whether methods detect specific dimensions of semantic change. **Impact:** helps researchers evaluate not only whether a method detects change, but what kind of change it is sensitive to. [[paper](https://aclanthology.org/2025.findings-acl.570/) · [code](https://github.com/naomibaes/LSCD_method_evaluation)]

        - **SenseRel — benchmark for sense-level semantic relations:** Joint first author, [**ACL 2026 Main**](https://naomibaes.github.io/publication/journal-article_2026_acl-main/). Co-developed a gold standard benchmark for testing whether AI language models represent both referential and evaluative relations between word senses. **Impact:** connects denotational relations such as metaphor and metonymy with connotational dimensions such as valence and arousal. Developed during my Change is Key! research [internship](https://www.changeiskey.org/post/25-08-04-naomi-visit/). [[paper](https://www.changeiskey.org/publication/2026-acl/2026.acl.pdf)]

        - **Computational social science applications:** Lead author, [**ICWSM 2026**](https://naomibaes.github.io/publication/journal-article_2026_icwsm/). Studied how women are dehumanized compared to men in incel discourse across five dimensions: *negative evaluation, moral disgust, animal likeness, mind denial, and agency denial*. **Impact:** extends my broader interest in interpretable language measurement to harmful online communication and socially contested discourse. [[paper](https://ojs.aaai.org/index.php/ICWSM/article/view/42632) · [code](https://github.com/lraszewski/words-against-women)]

        - **International research visibility:** Presented work on computational methods for tracking meaning change in the mental health domain at [Utrecht University](https://naomibaes.github.io/talks/nltp_lab_2025/), the [University of Gothenburg](https://naomibaes.github.io/talks/conceptual_change_2025/), and the [National Research Council Canada](https://naomibaes.github.io/talks/nrc_2025/) — spanning the Netherlands, Sweden, and Canada.

        - **Awards and research support:** Australian Government Research Training Program Scholarship; Change is Key! international research internship; ARC Concept Creep dissemination funding; University of Melbourne Hallmark Research Initiative support for Fighting Harmful Online Communication.

        <div style="text-align: center; margin-top: 1.2rem;">
          <a href="/updates/" style="display: inline-block; padding: 0.45rem 0.85rem; border: 1px solid #d1d5db; border-radius: 0.45rem; text-decoration: none; font-size: 0.9rem; font-weight: 400;">
            See all updates
          </a>
        </div>

    design:
      columns: 1
      css_class: research-overview-wide
      spacing:
        padding: ["2rem", "0", "2rem", "0"]

  - block: markdown
    content:
      title: Research
      text: |
        My work clusters around three overlapping streams:

        - **Methods & tools for semantic change:** frameworks, benchmarks, and pipelines for measuring different kinds of meaning change.
        - **Mental health and conceptual change:** studies of how psychological and mental health concepts change across scientific, media, and general language.
        - **Social meaning in contested language:** computational social science projects on dehumanization, stigma, identity language, and social evaluation.

        <div style="text-align: center; margin-top: 1.2rem;">
          <a href="/research/" style="display: inline-block; padding: 0.45rem 0.85rem; border: 1px solid #d1d5db; border-radius: 0.45rem; text-decoration: none; font-size: 0.9rem; font-weight: 400;">
            Explore research streams
          </a>
        </div>
    design:
      columns: 1
      css_class: research-overview-wide
      spacing:
        padding: ["2rem", "0", "2rem", "0"]

  - block: collection
    id: papers
    content:
      title: Featured Work
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
      title: ""
      subtitle: ""
      text: |
        <hr style="margin: 0 auto 1.6rem auto; max-width: 520px;">

        <div style="text-align: center; margin-top: 0; margin-bottom: 0;">
          <div style="font-size: 0.7rem; text-transform: uppercase; letter-spacing: 1.5px; color: #777; font-weight: 600; margin-bottom: 0.8rem;">
            Invited Talks
          </div>
          <div style="display: flex; justify-content: center; align-items: center; gap: 1.4rem; flex-wrap: nowrap; width: 100%; max-width: 620px; margin: 0 auto;">
            <img src="/media/logos/utrecht-university.svg" alt="Utrecht University" style="max-height: 32px; max-width: 135px; object-fit: contain; opacity: 0.82;">
            <img src="/media/logos/university-of-gothenburg.svg" alt="University of Gothenburg" style="max-height: 46px; max-width: 95px; object-fit: contain; border-radius: 4px; opacity: 0.85;">
            <img src="/media/logos/nrc-canada.jpg" alt="National Research Council Canada" style="max-height: 26px; max-width: 165px; object-fit: contain; opacity: 0.82;">
          </div>
    design:
      columns: '1'
      spacing:
        padding: ["0", "0", "0", "0"]

  - block: markdown
    content:
      title: ''
      text: |
        <div style="text-align: center; margin-top: 0; margin-bottom: 0;">
          <a href="/talks/" style="display: inline-block; padding: 0.45rem 0.85rem; border: 1px solid #d1d5db; border-radius: 0.45rem; text-decoration: none; font-size: 0.9rem; font-weight: 400;">
            See all presentations
          </a>
        </div>
    design:
      columns: 1
      spacing:
        padding: ["0", "0", "0.5rem", "0"]

  - block: markdown
    content:
      title: Research Ethos
      text: |
        Much of my work begins with a measurement problem: existing methods for detecting semantic change often conflate distinct kinds of shift — broadening is not the same as softening or acquiring negative associations, yet most approaches treat these as one phenomenon. I believe getting measurement to approximate the construct as closely as possible is not a technical detail but a substantive one; imprecise tools produce imprecise claims about how language and culture change. SIBling, LSC-Eval, and SenseRel all emerged from this concern — frameworks designed to make semantic change research more interpretable, more evaluable, and more honest about what is and isn't being measured.
    design:
      columns: 1
      css_class: research-overview-wide
      spacing: 
        padding: ["2rem", "0", "2rem", "0"]

---