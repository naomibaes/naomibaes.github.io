---
# Leave the homepage title empty to use the site title
title: "Naomi Baes"
date: 2025-04-05
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 0.7
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: 'Research Program'
      subtitle: ''
      text: |-
        My research program aims to understand conceptual change. 
        
        To this end, I have developed two novel and scalable frameworks with my PhD supervisors and colleagues. "SIBling" is a theoretical linguistic framework that proposes three major dimensions of lexical semantic change. "LSC-Eval" is a three-stage evaluation framework designed to generate synthetic datasets, use them to evaluate change detection methods, and identify the most suitable approach for the dimension and domain of interest. I am currently applying SIBling in the mental health domain to examine how concepts like *schizophrenia* and *autism* have evolved in meaning, and to uncover the social and cultural forces driving this change.

        My work makes four main contributions: 
        - It establishes SIBling as a theoretical linguistic framework that reduces six main types of lexical semantic change, identified by historical linguists, into three major dimensions of semantic change (SIB) and develops a methodological toolkit to measure them, leveraging techniques from natural language processing and psychology. 
        - It harnesses this toolkit to analyze semantic shifts in mental health concepts in large historical text corpora representing discourse ranging from academic psychology to everyday vernacular, providing a window into cultural and social dynamics, such as concept creep, pathologization, and stigmatization. 
        - It positions SIBling as an invaluable resource for researchers aiming to understand and model conceptual change and its social and cultural drivers in various disciplines (e.g., psychology, law, humanities).
        - It lays the groundwork to validate, generalize, and scale the study of conceptual change across domains and languages. 
  
    design:
      columns: '1' 
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Relevant Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Invited Talks
      filters:
        folders:
          - talks
        featured_only: true
    design:
      view: article-grid
      columns: 1
  - block: collection
    id: news
    content:
      title: Recent News
      filters:
        folders:
          - news
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
---
