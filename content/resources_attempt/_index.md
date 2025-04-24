---
title: 'Resources'
date: 2025-04-23
type: landing

design:
  spacing: '5rem'

sections:
  - block: collection
    content:
      title: Datasets
      text: Curated datasets, including synthetic data and domain corpora.
      filters:
        folders:
          - resources/datasets/NYT
          - resources/datasets/psychology_corpus
    design:
      view: article-grid
      columns: 3
      fill_image: false

  - block: collection
    content:
      title: Scripts
      text: Scripts to scrape and process text corpora.
      filters:
        folders:
          - scripts/PSYCH_scimago
          - scripts/sibling
    design:
      view: article-grid
      columns: 3
      fill_image: false

  - block: collection
    content:
      title: Embeddings
      text: Embeddings from language models and domains.
      filters:
        folders:
          - embeddings/semantic_severity
    design:
      view: article-grid
      columns: 3
      fill_image: false
