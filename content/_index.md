---
title: 'Home'
date: 2025-07-01
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: We solve your hardest data challenges
      text: Georg & Albert design, build and benchmark modern data platforms so you can
        ship faster, cut cost and sleep better.
      primary_action:
        text: See the ranking results
        url: https://docs.google.com/spreadsheets/d/1Y1Oxw_2LBWd502JtWFFyef2y5TvOyQMkq156cDrKJbA/edit?usp=sharing
        icon: rocket-launch
      secondary_action:
        text: Watch our live deep-dives
        url: https://www.youtube.com/@datainconsistencies
      announcement:
        text: "NEW: 2025 Cloud Data Platform Benchmark released"
        link:
          text: "Read summary"
          url: "https://docs.google.com/spreadsheets/d/1Y1Oxw_2LBWd502JtWFFyef2y5TvOyQMkq156cDrKJbA/edit?usp=sharing"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: bg-triangles.svg
          filters:
            brightness: 0.5
  # - block: stats
  #   content:
  #     items:
  #       - statistic: "1M+"
  #         description: |
  #           Websites built  
  #           with Hugo Blox
  #       - statistic: "10k+"
  #         description: |
  #           GitHub stars  
  #           since 2016
  #       - statistic: "3k+"
  #         description: |
  #           Discord community  
  #           for support
  #   design:
  #     # Section background color (CSS class)
  #     css_class: "bg-gray-100 dark:bg-gray-900"
  #     # Reduce spacing
  #     spacing:
  #       padding: ["1rem", 0, "1rem", 0]
  - block: cta-image-paragraph
    id: aboutus
    content:
      items:
        - title: Albert Wong
          text: Sales Engineer & DevRel lead at VC-backed startups.
            Albert pairs deep technical chops with a proven go-to-market mindset.
          feature_icon: check
          features:
            - business impact
            - data experience
          # Upload image to `assets/media/` and reference the filename here
          image: profile-albert.jpg
          button:
            text: Conncect
            url: https://www.linkedin.com/in/atwong/
        - title: Dr. Georg 
          text: "[Georg](geoheil.com) is a **Senior data expert** at Magenta and a ML-ops engineer at ASCII. He is **solving challenges with data**. His interests include geospatial graphs and time series. Georg transitions the data platform of Magenta to the cloud and is handling large scale multi-modal ML-ops challenges at ASCII."
          feature_icon: bolt
          features:
            - data architecture
            - solving challenges with data
          # Upload image to `assets/media/` and reference the filename here
          image: profile-georg.jpg
          button:
            text: Connect
            url: https://www.linkedin.com/in/geoheil/
  - block: cta-image-paragraph
    id: rankingsoverview
    content:
      items:
        - title: ELO ranking
          text: > 
            Compare the otherwise really hard to compare performance:
            Apples-to-apples comparisons of query engines, based on publicly
            reproducible workloads.
          feature_icon: check
          features:
            - Transparent methodology
            - Community contributions welcome
            - Plain ELO for binary rankings
            - Enhanced R-ELO for multi-class rankings
            - Matches as observations
            - We can compare the results from benchmarks from all over the web
          # Upload image to `assets/media/` and reference the filename here
          image: ranking-overall.png
          button:
            text: Explore the live rankings
            url: https://docs.google.com/spreadsheets/d/1Y1Oxw_2LBWd502JtWFFyef2y5TvOyQMkq156cDrKJbA/edit?usp=sharing
  # - block: cta-image-paragraph
  #   id: datainconsistencies
  #   content:
  #     items:
  #       - title: Elements of a data platform
  #         text: Storage, compute, pipelines and metadata
  #         feature_icon: check
  #         features:
  #           - Compute (SQL)
  #           - Data Orchestrator
  #           - Data catalog
  #           - Data Table format
  #           - Data Storage
  #         # Upload image to `assets/media/` and reference the filename here
  #         image: data-inconsistencies-logo.jpg
  #         button:
  #           text: See the rankings
  #           url: https://docs.google.com/spreadsheets/d/1Y1Oxw_2LBWd502JtWFFyef2y5TvOyQMkq156cDrKJbA/edit?usp=sharing
  #       # - title: Large Community
        #   text: Join our large community on Discord - ask questions and get live responses
        #   feature_icon: bolt
        #   features:
        #     - "Dedicated support channel"
        #     - "3,000+ users on Discord"
        #     - "Share your site and get feedback"
        #   # Upload image to `assets/media/` and reference the filename here
        #   image: data-inconsistencies-logo.jpg
        #   button:
        #     text: Join Discord
        #     url: https://discord.gg/z8wNYzb
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: features
    id: datainconsistencies
    content:
      title: Typical challenges when choosing a data transformation engine
      text: Benchmarks are misleading. But still we can source some sensible insights from them. We are computing ELO scores to compare the various engines.
      items:
        - name: Workload specific
          icon: magnifying-glass
          description: Standard benchmarks may [not fit your workload](https://www.onehouse.ai/blog/measuring-etl-price-performance-on-cloud-data-platforms). Understand the concepts and usage patterns.
        - name: Gamed benchmakrs
          icon: bolt
          description: Only trust the statistics you have faked yourself - sometimes it can happen vendors are overly optimizing the benchmarks in their favor
        - name: Measure
          icon: sparkles
          description: Collect the data of the various engines in a way it can becompre comparable.
        # - name: No-Code
        #   icon: code-bracket
        #   description: Edit and design your site just using rich text (Markdown) and configurable YAML parameters.
        # - name: Highly Rated
        #   icon: star
        #   description: Rated 5-stars by the community.
        # - name: Swappable Blocks
        #   icon: rectangle-group
        #   description: Build your pages with blocks - no coding required!
  # - block: testimonials
  #   content:
  #     title: ""
  #     text: ""
  #     items:
  #       - name: "Hugo Smith"
  #         role: "Marketing Executive at X" Upload image to `assets/media/` and reference the filename here
  #         image: "ranking-overall.png"
  #         text: "Awesome, so easy to use and saved me so much work with the swappable pre-designed sections!"
  #   design:
  #     spacing:
  #       Reduce bottom spacing so the testimonial appears vertically centered between sections
  #       padding: ["6rem", 0, 0, 0]
  - block: cta-card
    content:
      title: Explore the results
      text: Identify the most suitable data engine
      button:
        text: See the results
        url: https://docs.google.com/spreadsheets/d/1Y1Oxw_2LBWd502JtWFFyef2y5TvOyQMkq156cDrKJbA/edit?usp=sharing
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
  # - block: cta-card
  #   content:
  #     title: Ready to solve your data challenge?
  #     text: >
  #       Book a free 30-minute consultation. We'll review your current stack
  #       and point you to quick wins—no strings attached.
  #     button:
  #       text: Schedule a call
  #       url: https://calendly.com/geoheil/data-strategy
  #   design:
  #     card:
  #       css_class: "bg-primary-700"
  #       css_style: ""
---
