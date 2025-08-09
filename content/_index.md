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
      text: Albert & Georg design, build and benchmark modern data platforms so you can
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
    id: rankingsoverview
    content:
      items:
        - title: Analytics Engine ELO Report: A Dynamic Approach to Comparing Analytics and OLAP Engines 
          text: > 
            This report outlines the benefits of adopting the Elo rating system as a robust method for evaluating and comparing the performance of various analytics and Online Analytical Processing (OLAP) engines.

Traditional benchmarking often provides a static snapshot of performance, which may not fully capture an engine's capabilities under diverse, real-world conditions. The Elo rating system, originally developed for chess, offers a dynamic and more nuanced alternative.

<img referrerpolicy="no-referrer-when-downgrade" src="https://static.scarf.sh/a.png?x-pxid=578d1301-0e72-4879-83e7-f7e7692e7ff5" /> 
          feature_icon: check
          features:
            - Dynamic and Relative Performance Measurement: Unlike fixed benchmarks, the Elo system continuously adjusts an engine's score based on its performance against other engines. This provides a relative measure of strength that evolves as engines are updated or new competitors emerge.
            - Tournament-Style Head-to-Head Competition: Engines are pitted against each other in a series of competitions on a variety of queries and datasets (TPC-H, TPC-DS, SSB Wide Table). This simulates a real-world environment and highlights how engines perform under different loads and conditions.
            - Probabilistic Strength Assessment: An engine's Elo score reflects the probability of it winning against another engine. A win against a higher-rated opponent results in a larger score increase, while a loss against a lower-rated opponent leads to a more significant score decrease. This rewards consistent, high-level performance.
            - Greater Nuance and Insight: The system is excellent for revealing subtle differences in efficiency, latency, and throughput that might be missed in traditional single-metric comparisons. It provides a deeper understanding of an engine's strengths and weaknesses across various workloads.
            - A "Living" Leaderboard: The Elo ranking creates a dynamic and up-to-date leaderboard, offering a more sophisticated alternative to a simple "faster/slower" comparison. This living document of performance is valuable for both developers and users tracking engine improvements.
          # Upload image to `assets/media/` and reference the filename here
          image: ranking-overall.png
          button:
            text: Explore the live rankings
            url: https://docs.google.com/spreadsheets/d/1Y1Oxw_2LBWd502JtWFFyef2y5TvOyQMkq156cDrKJbA/edit?usp=sharing
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
  - block: cta-image-paragraph
    id: aboutus
    content:
      items:
        - title: Albert Wong
          text: Albert is a Sales Engineer and DevRel leader with a unique blend of deep technical knowledge and a proven go-to-market mindset. He has a track record of success at both VC-backed startups and major technology companies.<br/>Albert is available to speak at meetups and conferences on ELO analytics engine rankings and offers advisory consulting for analytics engine selection and strategy.
          feature_icon: check
          features:
            - focused on measurable business impact
            - developer with deep data and infrastructure experience
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
