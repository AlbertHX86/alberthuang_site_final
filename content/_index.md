---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    content:
      title: Skills
      items:
        - name: Programming
          description: 
          icon: r-project
          icon_pack: fab
        - name: Statistics
          description: 
          icon: chart-line
          icon_pack: fas
        - name: Research
          description: 
          icon: camera-retro
          icon_pack: fas
  - block: experience
    content:
      title: Experiences
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
    items:
        title: 'Intern' 
              company: LeetCode
              company_url: ''
              company_logo: 
              location: Shanghai
              date_start: '2023-04-28'
              date_end: ''
        title: 'PTA' 
              company: Roland Berger
              company_url: ''
              company_logo: 
              location: Shanghai / Singapore
              date_start: '2022-12-01'
              date_end: '2024-02-01'
        title: 'Intern' 
              company: Ernst & Young Parthenon
              company_url: ''
              company_logo: 
              location: Shanghai
              date_start: '2022-05-01'
              date_end: '2022-08-01'

    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Please feel free to contact me!
      # Contact (add or remove contact options as necessary)
      email: huang_xiao@u.nus.edu
      phone: +65 80397262 / +86 15522133486
      appointment_url: 'https://calendly.com'
      address:
        street: 
        city: Singapore
        region: CA
        postcode: '118430'
        country: Singapore
        country_code: SG
      directions: E4A
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
