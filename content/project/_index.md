---
title: 'Projects'
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
# content/project/_index.md
sections:
  - block: collection
    content:
      title: Current
      text: My ongoing research projects.
      page_type: project
      count: 0
      filters:
        tag: "current"      # <- singular
    design: { view: article-grid, fill_image: false, columns: 3, show_date: false, show_read_time: false, show_read_more: false }

  - block: collection
    content:
      title: Past
      text: Previous projects.
      page_type: project
      count: 0
      filters:
        tag: "past"         # <- singular
    design: { view: article-grid, fill_image: false, columns: 3, show_date: false, show_read_time: false, show_read_more: false }
---
