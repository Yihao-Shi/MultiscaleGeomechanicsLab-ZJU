---
title: Home
date: 2022-10-24

type: landing

sections:
  - block: slider
    content:
      slides:
      - title: Multiscale Geomechanics Lab
        content: Zhejiang University
        align: center
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
        url: ../people/
      - title: 
        content: We are looking for highly motivated Master/Ph.D. students and postdoc researchers
        align: right
        background:
          image:
            filename: sand.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../openings/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 60

  - block: markdown
    content:
      title: About Us
      text: |
        The Multiscale Geomechanics Lab at Zhejiang University strives to 
        {{% cta cta_link="./people/" cta_text="Current Members →" %}}
    design:
      columns: '1'

  - block: collection
    content:
      title: Recent News
      text: ""
      count: 5
      filters:
        folders:
          - news
        author: ""
        category: ""
        tag: ""
        publication_type: ""
        featured_only: false
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      offset: 0
      sort_by: 'Date'
      sort_ascending: false
    design:
      columns: '1'

  - block: markdown
    content:
      title: 
      text: |
        <font size=5> __Multiscale Geomechanics Lab__ </p>
        <font size=3> College of Civil Engineering and Architecture, Zhejiang University <br>
        Yu Hangtang Road, 866, China <br>
        nguo "at" zju "dot" edu "dot" cn
      link: ""
    design:
      background:
        image: 
          filename: 
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
---
