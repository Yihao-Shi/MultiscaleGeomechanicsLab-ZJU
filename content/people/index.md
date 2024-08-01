---
title: People
date: 2022-10-24


type: landing

sections:
  - block: slider
    content:
      slides:
      - align: center
        background:
          image:
            filename: peoples.jpg
            filters:
              brightness: 0.7
          fit: cover
          position: right
          color: '#666'
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '270px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000

  - block: people
    content:
      title: Current Members
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Principal Investigators
          - Researchers
          - Students
          - Administration
          - Visitors
          - Alumni
      sort_by: 
          Params.role
      sort_ascending: false
    design:
      show_interests: false
      show_role: true
      show_social: true
      show_organizations: true
---

