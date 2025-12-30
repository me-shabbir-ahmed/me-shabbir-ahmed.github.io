---
# Leave the homepage title empty to use the site title
title:
#date: 2022-10-24
type: landing
_build:
  list: never
  render: always

sections:
  - block: resume-biography-2
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text:
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          #filename: li-yang-5h_dMuX_7RE-unsplash.webp
          filename: robot.png
          filters:
            brightness: 0.4
          size: cover
          position: center
          parallax: false
  - block: stats
    content:
      items:
        - statistic: '<i class="fas fa-wave-square"></i>'
          description: |
            Publications
        - statistic: "260+"
          description: |
            Citations
        - statistic: "8"
          description: |
            h-index
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: markdown
    content:
      title: 'Welcome 👋'
      subtitle: ''
      text: |-
        I am an Assistant Professor in the Mechanical Engineering department at South Dakota State University. I am enthusiastic about modeling dynamical systems, signals and wave propagation.

        **Specialties:** Time Series Analysis, Waves and Structures, Damage Diagnosis
    design:
      columns: '1'
  - block: collection
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 4
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
        
      # Choose how many pages you would like to offset by
      offset: 1
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: card
      columns: '1'
      #view: date-title-summary
      # Reduce spacing
      #spacing:
        #padding: [0, 0, 0, 0]
  
---
