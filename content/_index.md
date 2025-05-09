---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false 
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: card
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ""
      count: 2
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
     # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
      view: citation
---
