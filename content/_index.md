---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

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
        - statistic: "15"
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
    first_name: Shabbir
    last_name: Ahmed
    role: Assistant Professor

    organizations:
    - name: South Dakota State University
    url: https://www.sdstate.edu/directory/shabbir-ahmed

    bio: >
    Assistant Professor in Mechanical Engineering at SDSU. Research in structural
    health monitoring (ultrasonic guided waves), battery diagnostics, and
    data-driven system identification (ARX/VARX, DMD/DMDc, Koopman).

    interests:
    - Structural health monitoring (Lamb waves)
    - Battery SoC/SoH & degradation modeling
    - Koopman/operator learning & time series
    - Controls & robotics

    education:
    courses:
    - course: PhD in Mechanical Engineering
      institution: Rensselaer Polytechnic Institute
      year: 2022
    - course: MS in Mechanical Engineering
      institution: North Dakota State University
      year: 2017
    - course: BSc in Mechanical Engineering
      institution: Bangladesh University of Engineering and Technology
      year: 2013

    social:
    - icon: envelope
      icon_pack: fas
      link: mailto:shabbir.ahmed@sdstate.edu
    - icon: linkedin
      icon_pack: fab
      link: https://www.linkedin.com/in/shabbir-ahmed-81146a116/
    - icon: google-scholar
      icon_pack: ai
      link: https://scholar.google.com/citations?user=wYxw9ZgAAAAJ&hl=en&inst=5831747260623323207
    - icon: orcid
      icon_pack: ai
      link: https://orcid.org/0000-0001-8296-6025

  status:
    icon: "☕️"
  work:
    - position: Assistant Professor
    company_name: South Dakota State University
    company_url: 'https://www.sdstate.edu'
    company_logo: ''
    date_start: 2022-08-01
    date_end: ''
    summary: |
      Department of Mechanical Engineering
      
      Responsibilities include:
      - Teaching undergraduate and graduate courses in mechanical engineering
      - Conducting research in structural health monitoring and battery diagnostics
      - Advising graduate students in research projects
      - Developing lab facilities for ultrasonic testing and system identification
  
    - position: Postdoctoral Researcher
    company_name: Rensselaer Polytechnic Institute
    company_url: 'https://www.rpi.edu'
    company_logo: ''
    date_start: 2022-05-01
    date_end: 2022-07-31
    summary: |
      Mechanical, Aerospace, and Nuclear Engineering Department
      
      - Conducted research on guided wave-based structural health monitoring
      - Developed data-driven system identification algorithms
  
    - position: Graduate Research Assistant
    company_name: Rensselaer Polytechnic Institute
    company_url: 'https://www.rpi.edu'
    company_logo: ''
    date_start: 2017-08-01
    date_end: 2022-05-01
    summary: |
      PhD Research
      
      - Investigated ultrasonic guided waves for structural health monitoring
      - Developed Koopman operator-based methods for battery diagnostics
      - Published research in peer-reviewed journals
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
      count: 5
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
      #offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      #order: desc
    design:
      # Choose a layout view
      #view: date-title-summary
      columns: '1'
      # Reduce spacing
      #spacing:
        #padding: [0, 0, 0, 0]
  
---
