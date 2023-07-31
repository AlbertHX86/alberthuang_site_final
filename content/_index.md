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
            - Another point in the description.
            - And yet another point.

        - title: 'PTA'
          company: Roland Berger
          company_url: 'https://www.rolandberger.com/en/'
          company_logo:
          location: Shanghai / Singapore
          date_start: '2022-12-01'
          date_end: '2024-02-01'
          description: |2-
            - Description point 1.
            - Description point 2.
            - Description point 3.

        - title: 'Intern'
          company: Ernst & Young Parthenon
          company_url: 'https://www.ey.com/en_gl/strategy/about-ey-parthenon'
          company_logo:
          location: Shanghai
          date_start: '2022-05-01'
          date_end: '2022-08-01'
          description: |2-
            - Description for the internship at EY Parthenon.
            - Additional point about the internship.

    design:
      columns: '2'
  
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
---
