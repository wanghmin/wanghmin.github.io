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
      view: citation
  - block: contact
    id: contact
    content:
      title: Contact     
      # Contact (add or remove contact options as necessary)
      email: wanghmin 'at' gmail 'dot' com
      address:
        street: 99 Shuanglong Street
        city: Hangzhou
        region: Zhejiang, China
        postcode: '310000'
        country: China
        country_code: CN
      directions: Enter Building A of Sanshen International and take an elevator to Floor 3
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '30.2935'
        longitude: '120.0713'      
      # Automatically link email and phone or display as text?
      autolink: true      
    design:
      columns: '2'    
---
