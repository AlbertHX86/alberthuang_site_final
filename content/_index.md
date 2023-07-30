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
          description: Python, C++, Matlab, R
          icon: r-project
          icon_pack: fab
        - name: Statistics
          description: ML, Linear Programming, Bayesian 
          icon: chart-line
          icon_pack: fas
        - name: Research
          description: Smart grids, Dynamic pricing
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
        - title: 'Product Manager Intern (C-end Algorithms)' 
          company: LeetCode
          company_url: ''
          company_logo: 
          location: Shanghai
          date_start: '2023-04-28'
          date_end: '2023-07-28'
          description: 
          company: Roland Berger
          company_url: ''
          company_logo: 
          location: Shanghai / Singapore
          date_start: '2022-12-01'
          date_end: '2024-02-01'
          descriptions:
        - title: 'Project Intern' 
          company: Ernst & Young Parthenon
          company_url: ''
          company_logo: 
          location: Shanghai
          date_start: '2022-05-01'
          date_end: '2022-08-01'
    design:
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
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
        region: SG
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
    content:
      title: Vistor's map
      directions: 
---
