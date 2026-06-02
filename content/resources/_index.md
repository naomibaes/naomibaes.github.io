---
title: 'Code, Data & Benchmarks'
date: 2025-04-23
type: landing

design:
  spacing: '5rem'

sections:
  - block: collection
    content:
      title: Benchmarks & Evaluation Resources
      text: "Resources for evaluating lexical semantic change methods, including synthetic diachronic datasets and benchmark construction pipelines."
      filters:
        tag: benchmark
    design:
      view: article-grid
      columns: 4
      fill_image: false

  - block: collection
    content:
      title: Research Code & Pipelines
      text: "Code and pipelines for modeling semantic change, generating synthetic corpora, processing diachronic text, and evaluating NLP methods."
      filters:
        tag: code
    design:
      view: article-grid
      columns: 4
      fill_image: false

  - block: collection
    content:
      title: Datasets
      text: "Curated datasets, including synthetic and domain-specific diachronic text corpora."
      filters:
        tag: dataset
    design:
      view: article-grid
      columns: 4
      fill_image: false

  - block: collection
    content:
      title: Scripts
      text: "Utility scripts for scraping, preprocessing, and analyzing conceptual change in text corpora."
      filters:
        tag: script
    design:
      view: article-grid
      columns: 4
      fill_image: false
---