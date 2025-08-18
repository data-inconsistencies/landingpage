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
      title: Battle of the Analytics Engines
      text: We rank OLAP and analytics engines using every public benchmark—messy or not—powered by ELO ratings. See the winners, track the history, and add your own results to shape the leaderboard.
#      primary_action:
#        text: See the ranking results
#        url: https://docs.google.com/spreadsheets/d/1Y1Oxw_2LBWd502JtWFFyef2y5TvOyQMkq156cDrKJbA/edit?usp=sharing
#        icon: rocket-launch
#      secondary_action:
#        text: Watch our live deep-dives
#        url: https://www.youtube.com/@datainconsistencies
#      announcement:
#        text: "NEW: 2025 Analytics Engine ELO Report released"
#        link:
#          text: "Read summary"
#          url: "https://docs.google.com/spreadsheets/d/1Y1Oxw_2LBWd502JtWFFyef2y5TvOyQMkq156cDrKJbA/edit?usp=sharing"
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
#   - block: features
#     id: datainconsistencies
#     content:
#       title: "Project: Typical challenges when choosing a data transformation engine"
#       text: Benchmarks are misleading. But still we can source some sensible insights from them. We are computing ELO scores to compare the various engines.
#       items:
#         - name: Use public performance tests
#           icon: magnifying-glass
# #          description: Standard benchmarks may [not fit your workload](https://www.onehouse.ai/blog/measuring-etl-price-performance-on-cloud-data-platforms). Understand the concepts and usage patterns.
#           description: Assume all public performance tests are true.  TPC-DS, TPC-H and SSB Wide table are better but accept the ones that aren't. Collect them all.  Add your performance report by publishing it publically on the web and email atwong@protonmail.com to add it to the ELO rankings. Allow backdated performance reports. 
#         - name: Project vs. Product. OLAP vs. Analytics Engines.  
#           icon: bolt
#           description: Have all the products battle each other in matches.  Sometimes it's 1v1 and in other times in 3 or 4 products being compared in the match.  Doesn't matter, use ELO to determine who is better.
#         - name: See the data and Add more reports
#           icon: sparkles
#           description: See who are the players (analytics engines, OLAP engines, open source projects, open core, closed source, or their commerical equivlants). See a historical view of players and their matches. Allow you to sort the data. 
#         # - name: Add more reports
#         #  icon: code-bracket
#         #  description: Add your performance report by publishing it publically on the web and email atwong@protonmail.com to add it to the ELO rankings. Allow backdated performance reports. 
#         # - name: Highly Rated
#         #   icon: star
#         #   description: Rated 5-stars by the community.
#         # - name: Swappable Blocks
#         #   icon: rectangle-group
#         #   description: Build your pages with blocks - no coding required!
  # - block: cta-image-paragraph
  #   id: rankingsoverview
  #   content:
  #     items:
  #       - title: "Analytics Engine ELO Report: A Dynamic Approach to Comparing Analytics and OLAP Engines" 
  #         text: > 
  #           Traditional benchmarking often provides a static snapshot of performance at a specific point in time and environment. These snapshots cannot be easily compared or even reproduced, even when using similar versions, datasets, instance types, or hardware architectures. Instead, the ELO rating system, originally developed for chess, offers a dynamic and more nuanced alternative. <img referrerpolicy="no-referrer-when-downgrade" src="https://static.scarf.sh/a.png?x-pxid=578d1301-0e72-4879-83e7-f7e7692e7ff5" /> 
  #         feature_icon: check
  #         features:
  #           - "Dynamic and Relative Performance Measurement: Unlike fixed benchmarks, the ELO system continuously adjusts an engine's score based on its performance against other engines. This provides a relative measure of strength that evolves as engines are updated or new competitors emerge."
  #           - "Tournament-Style Head-to-Head Competition: Engines are pitted against each other in a series of competitions on a variety of queries and datasets. This simulates a real-world environment and highlights how engines perform under different loads and conditions."
  #           - "Probabilistic Strength Assessment: An engine's ELO score reflects the probability of it winning against another engine. A win against a higher-rated opponent results in a larger score increase, while a loss against a lower-rated opponent leads to a more significant score decrease. This rewards consistent, high-level performance."
  #           - "Greater Nuance and Insight: The system is excellent for revealing subtle differences in efficiency, latency, and throughput that might be missed in traditional single-metric comparisons. It provides a deeper understanding of an engine's strengths and weaknesses across various workloads."
  #           - "A \"Living\" Leaderboard: The ELO ranking creates a dynamic and up-to-date leaderboard, offering a more sophisticated alternative to a simple \"faster/slower\" comparison. This living document of performance is valuable for both developers and users tracking engine improvements."
  #         # Upload image to `assets/media/` and reference the filename here
  #         image: ranking-overall.png
  #         button:
  #           text: Explore the live rankings
  #           url: https://docs.google.com/spreadsheets/d/1Y1Oxw_2LBWd502JtWFFyef2y5TvOyQMkq156cDrKJbA/edit?usp=sharing
  - block: cta-image-paragraph
    id: rankingsoverview
    content:
      items:
        - title: Who’s the Best Data Analytics Engine? Let’s Find Out.
          text: | 
            Benchmarks lie. But if we collect all of them, a clearer picture emerges.  </br>

            We use **ELO rankings**—the same system used in chess—to pit analytics and OLAP engines against each other, track their wins, and see who really dominates.</br></br>


            **How it works:** </br>
                1. We grab every public performance test (TPC-DS, TPC-H, SSB Wide Table, and more—even the messy ones).</br>
                2. We turn results into “matches” — sometimes 1-on-1, sometimes 3- or 4-way battles.</br>
                3. The ELO system updates the rankings after every match.
            </br></br>

            **Get Involved:**</br>
                - See the full leaderboard and historical performance.</br>
                - Sort and explore engines by data workload: TPC-DS, TPC-H, SSB Wide Table or others.</br>
                - Got results? Publish them online and email <a href="mailto:atwong@alumni.uci.edu">atwong@alumni.uci.edu</a> — we’ll add them (even backdated ones) to the rankings.
            </br></br>

            ***The game is on.***
          image: ranking-overall.png
          button:
            text: Explore the live rankings
            url: https://linkly.link/2DXzx     
  - block: cta-image-paragraph
    id: aboutus
    content:
      items:
        - title: Albert Wong
          text: Albert is a Sales Engineer and DevRel leader with a unique blend of deep technical knowledge and a proven go-to-market mindset. He has a track record of success at both VC-backed startups and major technology companies.<br/><br/>Albert is available to speak at meetups and conferences on ELO analytics engine rankings and offers advisory consulting for analytics engine selection and strategy.
          feature_icon: check
          features:
            - focused on measurable business impact
            - developer with deep data and infrastructure experience
          # Upload image to `assets/media/` and reference the filename here
          image: profile-albert.jpg
          button:
            text: Connect
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
  # - block: cta-card
  #   content:
  #     title: Explore the results
  #     text: Identify the most suitable data engine
  #     button:
  #       text: See the results
  #       url: https://docs.google.com/spreadsheets/d/1Y1Oxw_2LBWd502JtWFFyef2y5TvOyQMkq156cDrKJbA/edit?usp=sharing
  #   design:
  #     card:
  #       # Card background color (CSS class)
  #       css_class: "bg-primary-700"
  #       css_style: ""
  - block: cta-card
    content:
      title: Want to dig deeper?
      text: >
        Book a 30-minute consultation to learn our methodology and how the rankings were built. </br></br>
        
        In this session, we’ll move beyond raw performance metrics—breaking down the strengths and trade-offs of each engine and unpacking the ELO ranking system. You can even bring your own unpublished benchmarks to see how they shift the results.
      button:
        text: Schedule a call
        url: https://calendly.com/geoheil/data-strategy
    design:
      card:
        css_class: "bg-primary-700"
        css_style: ""
---
