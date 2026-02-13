---
title: 'Home'
date: 2026-02-13
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Less is more
      text: A personal hub for technical docs, engineering projects, and daily blogs.
      primary_action:
        text: Browse docs
        url: /docs/
        icon: rocket-launch
      secondary_action:
        text: View projects
        url: /projects/
      announcement:
        text: "Welcome to my personal website"
        link:
          text: "Learn more about me"
          url: "/about/"
    design:
      # For full-screen, add `min-h-screen` below
      css_class: ""
      background:
        color: ""
        image:
          # Add your image background to `assets/media/`.
          filename: ""
          filters:
            brightness: 0.5
  - block: stats
    content:
      items:
        - statistic: "Docs"
          description: |
            Technical notes and reference
        - statistic: "Projects"
          description: |
            Engineering work and prototypes
        - statistic: "Blogs"
          description: |
            Reflections and perspectives
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-800"
  - block: features
    id: features
    content:
      title: Focus Areas
      text: Core domains across graphics engineering.
      items:
        - name: Physical simulation
          icon: beaker
          description: The numerical modeling of physical phenomena (such as rigid bodies, fluids, cloth, and collisions) to produce physically plausible behavior in virtual environments.
        - name: Real-time rendering
          icon: bolt
          description: The process of generating visually convincing images at interactive frame rates under strict performance and latency constraints.
        - name: GPU
          icon: server
          description: A highly parallel processor specialized for accelerating graphics pipelines and large-scale data-parallel computations.
        - name: Vulkan
          icon: queue-list
          description: A low-level, explicit graphics and compute API that provides fine-grained control of GPU resources for high-performance, cross-platform rendering.
        - name: Game engine
          icon: cube
          description: A modular software framework that integrates rendering, physics, animation, audio, input, and tools to develop and run interactive applications.
        - name: Deep learning
          icon: cpu-chip
          description: A machine learning paradigm based on multi-layer neural networks that learn complex representations for tasks such as recognition, generation, and optimization.
  - block: cta-card
    content:
      title: "One more thing"
      text: "“The end of labor is to gain leisure.” — Aristotle"
      button:
        text: Read the blogs
        url: /blogs/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
