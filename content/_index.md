---
title: "Albert"
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      username: admin

  - block: features
    content:
      title: Skills
      items:
        - name: Programming
          description: Python, C++ (LinkedIn certificated), MATLAB (LinkedIn certificated), SQL (LinkedIn certificated)
          icon: r-project
          icon_pack: fab
        - name: Statistics
          description: ML (LinkedIn certificated), Linear Programming, GIS data analysis (QGIS)
          icon: chart-line
          icon_pack: fas
        - name: Electrical Engineering
          description: Signals and systems, circuits, semi-conductors, grids, control theories, simulation
          icon: camera-retro
          icon_pack: fas
  - block: contact
    id:   # Unique ID for this contact block
    content:
      title: Research Interests
      subtitle:
      text: |-
|
      <div style="text-align: center;"> <!-- Center-align text -->
        <p>Time series, Recommender systems</p>
      </div>


  - block: experience
    id: experience
    content:
      title: Experiences
      date_format: Jan 2006
      items:
        - title: 'Product Manager Intern, Algorithm'
          company: LeetCode
          company_url: 'https://leetcode.com/'
          company_logo:
          location: Shanghai (On-site), Singapore (remote), Palo Alto (remote)
          date_start: '2023-04-28'
          date_end: '2023-07-28'
          description: |2-
            - Led and collaborated with Recommender and Ranking Algorithm development; improved the PV-CTR by 5 times compared with the previous algorithms.
            - Collaborated with a cross-functional team of developers to resolve key issues in LeetCode products and improve user experiences.
            - Designed and engineered the deep-learning framework and environment for collaborative filtering, XGBoost training.

        - title: 'in-pool PTA'
          company: Roland Berger
          company_url: 'https://www.rolandberger.com/en/'
          company_logo: 
          location: Shanghai / Singapore
          date_start: '2022-12-01'
          date_end: '2024-02-01'
          description: |2-
            - Conducted desk research on new energy vehicles and related OEM industries, and prepared monthly reports for client companies.
            - Analyzed market conditions, collected and analyzed domestic and foreign market data, and used Excel, Python and other tools to present visual data results.
            - Assisted the project team to conduct expert interviews, sorted out the interview minutes according to the voice of the expert interviews.
            - Based on the industrial data collected, used Thinkcell and Islides to design slides for presentations.

  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      default_button_index: 0
      buttons:
        - name: All
          tag: '*'
        - name: Machine Learning
          tag: Machine Learning
        - name: Other
          tag: Demo

  - block: contact
    id: contact1  # Unique ID for this contact block
    content:
      title: Contact
      subtitle:
      text: |-
        Please feel free to contact me!
      email: huang_xiao@u.nus.edu
      phone: +65 80397262 / +86 15522133486
      appointment_url: '[https://calendly.com](https://calendly.com/2210333248hx/zoom-meeting)'
      address:
        street: 
        city: Singapore
        region: SG
        postcode: '118430'
        country: Singapore
        country_code: SG
      directions: E4A
      autolink: true

  - block: contact
    id: contact2  # Unique ID for this contact block
    content:
      title: Visitor's Map
      directions: |
        <a href='https://clustrmaps.com/site/1bvwo'  title='Visit tracker'><img src='//clustrmaps.com/map_v2.png?cl=080808&w=1000&t=tt&d=QPw1wX8uwINZR0wrjvvevNVwAznnrxHsUuUFYY4C3WM&co=ffffff&ct=808080'/></a>
---
