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
        # Experiences data here...

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
        - name: Machine Learning
          tag: Machine Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'

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
    id: visitor_map
    content:
      title: Vistor's map
      directions:<script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?d=QPw1wX8uwINZR0wrjvvevNVwAznnrxHsUuUFYY4C3WM"></script>
---
