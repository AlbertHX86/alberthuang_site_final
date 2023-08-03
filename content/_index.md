---
title: 
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
          description: Python, C++, MATLAB
          icon: r-project
          icon_pack: fab
        - name: Statistics
          description: ML, Linear Programming 
          icon: chart-line
          icon_pack: fas
        - name: Research
          description: smart grids, dynamic pricing
          icon: camera-retro
          icon_pack: fas

  - block: experience
    content:
      title: Experiences
      date_format: Jan 2006
      items:
        - title: 'Product Manager Intern, Algorithm'
          company: LeetCode
          company_url: 'https://leetcode.com/'
          company_logo:
          location: Shanghai, Singapore (remote)
          date_start: '2023-04-28'
          date_end: '2023-07-28'
          description: |2-
            - Recommender and ranking algorithm development for feed stream contents.
            - C-end product management.
            - PRD designs.

        - title: 'PTA'
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

        - title: 'Intern'
          company: Ernst & Young Parthenon
          company_url: 'https://www.ey.com/en_gl/strategy/about-ey-parthenon'
          company_logo:
          location: Shanghai
          date_start: '2022-05-01'
          date_end: '2022-08-01'
          description: |2-
            - Partnered with project members to conduct desk researches of OEM and NEV companies, and design monthly reports for the client company.
            - Collected and analyzed domestic and foreign market data using Excel, Python and other analysis tools so as to facilitate the quantitative analysis of the project.

    design:
      columns: '2'
  
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
    design:
      columns: '1'
      view: showcase
      flip_alt_rows: false

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Please feel free to contact me!
      email: huang_xiao@u.nus.edu
      phone: +65 80397262 / +86 15522133486
      appointment_url: 'https://calendly.com'
      address:
        street: 
        city: Singapore
        region: SG
        postcode: '118430'
        country: Singapore
        country_code: SG
      directions: E4A
      autolink: true
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          captcha: false
    design:
      columns: '2'
    
  - block: contact
    id: contact
    content:
      title: Vistor's map
      directions: <a href="https://clustrmaps.com/site/1bvwo"  title="Visit tracker"><img src="//www.clustrmaps.com/map_v2.png?d=QPw1wX8uwINZR0wrjvvevNVwAznnrxHsUuUFYY4C3WM&cl=ffffff" /></a>
---
