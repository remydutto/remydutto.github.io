---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: PhD student
          company: Vitesco Technologies
          company_url: https://www.vitesco-technologies.com/fr-fr
          company_logo: VT_logo
          location: Toulouse, France
          date_start: '2021-10-10'
          date_end: ''
          description: |2-
              Realted topics:

              * Optimal Control
              * Neural Network
              * Numerical methods
        - title: Apprenticeship
          company: Thales Alenia Space 
          company_url: https://www.thalesaleniaspace.com/fr
          company_logo: TAS_logo
          location: Cannes, France
          date_start: '2020-10-05'
          date_end: '2021-09-30'
          description: |2-
              Realted topics:

              * Reinforcement Learning
              * Neural Network 
              * Anomaly detection 
    design:
      columns: '2'
  - block: collection
    # id: publications
    content:
      title: Publications
      count: 3
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation
  - block: collection
    # id: talks
    content:
      title: Talks
      count: 3
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: tag_cloud
    content:
      title: Main Topics
    design:
      columns: '2'
---