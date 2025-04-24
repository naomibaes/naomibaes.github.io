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
      text: "Curated datasets, including synthetic data and large-scale domain-specific corpora."
      filters:
        folders:
          - datasets/*
    design:
      view: article-grid
      page_type: resource
      columns: 3
      fill_image: false

  - block: collection
    content:
      title: Scripts
      text: "Scripts to scrape, process, structure and analyze conceptual change in large corpora."
      filters:
        folders:
          - scripts/*
    design:
      view: article-grid
      page_type: resource
      columns: 3
      fill_image: false

  - block: collection
    content:
      title: Embeddings
      text: "To come: Embeddings from various contextualized language models, domain-specific corpora and targets."
      filters:
        folders:
          - embeddings/*
    design:
      view: article-grid
      page_type: resource
      columns: 3
      fill_image: false
---
