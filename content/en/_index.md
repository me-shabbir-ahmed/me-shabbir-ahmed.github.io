---
title: Home
type: landing

sections:
  # Sanity check: if this shows, sections are rendering
  - block: markdown
    id: welcome
    content:
      title: Welcome
      text: |-
        This is a test paragraph to confirm sections render on the homepage.

  # Biography card that pulls from your author profile
  - block: resume-biography-2
    id: about
    content:
      title: About
      user: admin          # must match folder name under content/authors/
      show_social: true
      show_interests: true
      show_education: true
---






