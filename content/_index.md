---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: '🔬 My Research'
      subtitle: ''
      text: |-
        My research addresses the **semantic-execution gap** in smart built environments — the divide between what facility data *means* and what systems can *automatically do* with it.

        I develop graph-native, ontology-driven frameworks that transform heterogeneous facility data and management logic into traceable, executable actions. Core contributions include the **Semantic Action Management** methodology and the **TIAA** (Trigger–Inference–Assignment–Action) framework, validated across predictive maintenance, lifecycle carbon governance, and AI-agent-based construction automation.

        My work draws on 20 years of experience spanning architectural practice, high-tech facility engineering at TSMC, and academic research — bridging domain knowledge and intelligent systems in ways that are both theoretically rigorous and practically deployable.

        **Current focus:** Plug-and-play semantic execution architectures for reusable cross-domain digital twin automation.
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation

  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - events
    design:
      view: card

  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      page_type: blog
      count: 10
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      offset: 0
      order: desc
    design:
      view: card
      spacing:
        padding: [0, 0, 0, 0]
---
