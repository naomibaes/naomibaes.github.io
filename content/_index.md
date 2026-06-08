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
      title: Highlights
      text: |
        <div style="font-size: 1rem">

        - **Association for Computational Linguistics (ACL) 2026 (Main Conference):** Joint-first author on [*SenseRel*](https://www.changeiskey.org/publication/2026-acl/2026.acl.pdf) — a benchmark testing whether AI language models understand the denotational and connotational layers of meaning between word senses. Developed during my Change is Key! research internship.

        - **International Conference on Web and Social Media (ICWSM) 2026:** Lead author of a computational [study](https://naomibaes.github.io/publication/journal-article_2026_icwsm/) examining how women are dehumanized compared to men in incel online communities.

        - **Language Change Workshop (LChange'26; EACL 2026):** Lead author of a [paper](https://naomibaes.github.io/publication/workshop-paper-2026_sense-prevalence/) extending a hypothesis-driven framework to track how the prevalence of word senses shifts over time, applied to *schizophrenia* — presented at the workshop.

        - **ACL 2025 Findings (Computational Social Science & Cultural Analytics):** Lead author of [LSC-Eval](https://aclanthology.org/2025.findings-acl.570/) — a framework for evaluating whether computational methods are sensitive to detecting dimensions of semantic change, using the mental health domain as a case study.

        - **ACL 2024 Main (Computational Social Science & Cultural Analytics):** Lead author of [SIBling](https://aclanthology.org/2024.acl-long.76/) — a framework for studying lexical semantic change across multiple dimensions (Sentiment, Intensity, Breadth), with applications to social and psychological research.

        - **International Conference on Computational Social Science (IC2S2) 2025:** [Presented](https://naomibaes.github.io/talks/ic2s2_2025/) SIBling and LSC-Eval to an interdisciplinary audience of social scientists and computational researchers.

        - **Public writing:** Co-authored a piece in [*The Conversation*](https://theconversation.com/mental-illness-psychiatric-disorder-or-psychological-problem-what-should-we-call-mental-distress-226748) with Professor Nick Haslam on what we should call mental distress — and why the words we use matter.

        - **Awards and research support:** Australian Government Research Training Program Scholarship; selected for Change is Key! international research internship (Riksbankens Jubileumsfond); Concept Creep research funding for conference travel and dissemination.

        - **Competitive team funding:** Co-recipient of **AUD $15,000 Hallmark Research Initiative seed funding** for a 7-member team project on '*Automatic evaluation of mental health stigma in online communication*', led by Yulia Otmakhova.

        - **Research leadership and service:** Program Chair/PC for the [LChange'26 Workshop](https://www.changeiskey.org/event/2026-eacl-lchange/), co-located with EACL 2026; Australian English Language Co-Lead with Christine de Kock for the [BLEnD SemEval-2026 Shared Task](https://arxiv.org/abs/2605.02601).

        - **ACL 2025 Best Resource Paper Award (Resources & Evaluation):** Contributor to [**BRIGHTER**](https://aclanthology.org/2025.acl-long.436/) — a large multilingual dataset for emotion recognition across 28 languages, including many low-resource languages from Africa, Asia, and Eastern Europe; awarded Best Resource Paper at ACL 2025. Contributed Romanian-language annotation (team lead: Daniela Teodorescu).

        - **Invited talks:** Presented work on computational methods for tracking meaning change in the mental health domain — including SIBling, LSC-Eval, and applied case studies in psychology — at [*Utrecht University*](https://naomibaes.github.io/talks/nltp_lab_2025/), the [*University of Gothenburg*](https://naomibaes.github.io/talks/conceptual_change_2025/), and the [*National Research Council Canada*](https://naomibaes.github.io/talks/nrc_2025/).      

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

  - block: markdown
    content:
      title: 'Research Overview'
      subtitle: ''
      text: |-
        
        I study how word meanings change as concepts move across scientific writing, news media, and general language. My work focuses especially on language with social, cultural, or psychological significance, including mental health concepts and contested social terms. I ask how these terms extend into new contexts, shift in emotional intensity, and acquire more positive or negative associations. To examine these questions, I combine NLP methods with theory from social psychology, computational social science, and corpus linguistics, using historical text corpora, contextual embeddings, lexical resources, large language models, and statistical modeling.

        ### Research streams

        My work clusters around three overlapping streams: (1) diachronic lexical semantic change and evaluation, (2) conceptual change in psychology, and (3) computational social science projects on socially contested language.

        - **Diachronic lexical semantic change and evaluation**  
          I develop computational methods and evaluation resources for tracing different *kinds* of diachronic lexical semantic change in historical text corpora, with applications in psychology, computational social science, linguistics, and NLP method evaluation. Contributions include: 
            - [**SIBling**](/publication/journal-article_2024_acl_sibling/), a multidimensional framework for modeling whether words become broader, more emotionally intense, or acquire more positive or negative connotations over time. 
            - [**LSC-Eval**](/publication/journal-article_2025_acl-findings/), an evaluation framework that uses LLM-generated historical datasets in experimental settings to test whether semantic change methods are sensitive to specific kinds of change. 
            - A [threshold-calibrated sense tracking pipeline](/publication/workshop-paper-2026_sense-prevalence/) for estimating the prevalence of a word's senses in historical corpora. It touches on LSC interpretability by showing how LSC scores may not reflect sense change.
            - [**SenseRel**](/publication/journal-article_2026_acl-main/), a sense-level benchmark for modeling semantic relations between word senses, connecting denotational semantic change types (e.g., metaphor, metonymy) with connotational dimensions of meaning (e.g., valence and arousal). We evaluate how well LLMs and fine-tuned models capture these relations.

        - **Conceptual change in psychology and mental health language**  

          I study how psychological and mental health concepts change in meaning, salience, severity, and use across academic psychology, news media, books, and general language corpora. This stream includes substantive case studies of concepts such as [*trauma*](/publication/journal-article_2023_plc/), [*mental illness*](/publication/journal-article_2024_acl_sibling/), [*schizophrenia*](/publication/workshop-paper-2026_sense-prevalence/), *introversion*, and [generic](/publication/journal-article_2024_acl_sibling/) and [emotion related](/publication/journal-article_2023_12_emnlp/) mental health terminology. Together, these studies examine when concepts become more culturally prominent, more widely used, emotionally intense, or evaluatively charged, interpreted through psychological theory, concept creep research, and corpus evidence.

        - **Social meaning in contested language**  
          I also contribute to collaborative projects that use NLP and computational social science methods to study socially important language, including [dehumanization](/publication/journal-article_2026_icwsm/) of women in incel discourse, mental health stigma detection in online communication, identity/person-first language for mental health conditions, and lay understandings of the [common good](/publication/journal-article_2024_4_bjsp/). These projects extend my broader interest in how language reflects, organizes, and reshapes social and psychological categories.

    design:
      columns: '1'
      css_class: research-overview-wide

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
        <div style="font-size: 1rem">

        Much of my work begins with a measurement problem: existing methods for detecting semantic change often conflate distinct kinds of shift — broadening is not the same as softening or acquiring negative associations, yet most approaches treat these as one phenomenon. I believe getting measurement to approximate the construct as closely as possible is not a technical detail but a substantive one; imprecise tools produce imprecise claims about how language and culture change. SIBling, LSC-Eval, and SenseRel all emerged from this concern — frameworks designed to make semantic change research more interpretable, more evaluable, and more honest about what is and isn't being measured.
        </div>
    design:
      columns: 1
      css_class: research-overview-wide
      spacing: 
        padding: ["2rem", "0", "2rem", "0"]

---