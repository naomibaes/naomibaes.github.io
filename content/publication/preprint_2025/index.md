---
title: 'LSC-Eval: A General Framework to Evaluate Methods for Assessing Dimensions of Lexical Semantic Change Using LLM-Generated Synthetic Data'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Raphaël Merx
  - Nick Haslam
  - Ekaterina Vylomova
  - Haim Dubossarsky

# Author notes (optional)
author_notes:

date: '2025-03-11T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["preprint"]

# Publication name and optional abbreviated publication name.
publication: "ACL Findings (accepted)"
publication_short: ""

abstract: "Lexical Semantic Change (LSC) provides insight into cultural and social dynamics. Yet, the validity of methods for measuring different kinds of LSC remains unestablished due to the absence of historical benchmark datasets. To address this gap, we propose LSC-Eval, a novel three-stage general-purpose evaluation framework to: (1) develop a scalable methodology for generating synthetic datasets that simulate theory-driven LSC using In-Context Learning and a lexical database; (2) use these datasets to evaluate the sensitivity of computational methods to synthetic change; and (3) assess their suitability for detecting change in specific dimensions and domains. We apply LSC-Eval to simulate changes along the Sentiment, Intensity, and Breadth (SIB) dimensions, as defined in the SIBling framework, using examples from psychology. We then evaluate the ability of selected methods to detect these controlled interventions. Our findings validate the use of synthetic benchmarks, demonstrate that tailored methods effectively detect changes along SIB dimensions, and reveal that a state-of-the-art LSC model faces challenges in detecting affective dimensions of LSC. LSC-Eval offers a valuable tool for dimension- and domain-specific benchmarking of LSC methods, with particular relevance to the social sciences." 

# Summary. An optional shortened abstract.
summary: We introduce a scalable, domain-general framework that creates diachronic, LLM-generated synthetic datasets to simulate theory-driven Lexical Semantic Change (LSC) and evaluates various methods for measuring kinds of LSC--using examples from psychology, we apply this framework to assess the sensitivity of a suite of methods in detecting artificially induced changes in dimensions of Sentiment, Intensity, and Breadth (SIB), ultimately identifying the most suitable approach for each dimension.

tags:
- LLM-Generated Synthetic Data

featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/abs/2503.08042
url_code: 'https://github.com/naomibaes/LSCD_method_evaluation'
url_dataset: 'https://github.com/naomibaes/Synthetic-LSC_pipeline'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Stages of the Evaluation Framework.'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

