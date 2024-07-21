---
# Leave the homepage title empty to use the site title
title: ""
date: 2024-07-18
type: landing

design:
  # Default section spacing
  spacing: "1rem"

sections:
  - block: resume-biography
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download Resume
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
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: news
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
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      # view: date-title-summary
      view: list
      columns: 2
      # Reduce spacing
      spacing:
        padding: [0,0,1,0]
        
  - block: resume-experience
    content:
      # The user's folder name in `content/authors/`
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false

  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    content:
      title: Recent Publications
      text: ""
      count: 0
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation

  # - block: markdown
  #   id: section-1
  #   content:
  #     title: Section 1
  #     subtitle: A subtitle
  #     text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
  # - block: markdown
  #   id: section-2
  #   content:
  #     title: Section 2
  #     subtitle: A subtitle
  #     text: Add your Section 2 content here...
---
