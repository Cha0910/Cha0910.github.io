---
title: 'Projects'
date: 2024-05-19
type: landing

#design:
#  # Section spacing
#  spacing: '5rem'

## Page sections
#sections:
#  - block: collection
#    content:
#      title: Selected Projects
#      text: I enjoy making things. Here are a selection of projects that I have worked on over the years.
#      filters:
#        folders:
#          - project
#        featured_only: false
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#    offset: 0
#    sort_by: 'Date'
#    sort_ascending: false
#    design:
#      view: card
#      fill_image: false
#      columns: 3
#--- 
sections:
  - block: collection
    content:
      title: Recent Posts
      subtitle: ''
      text: 'Check out my recent blog posts below!'
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - project
        author: ""
        category: ""
        tag: ""
        publication_type: ""
        featured_only: false
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      # Choose how many pages you would like to offset by
      # Useful if you wish to show the first item in the Featured widget
      offset: 0
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
    design:
      view: article-grid
      fill_image: false
      columns: 3
---
