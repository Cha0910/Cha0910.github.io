---
title: 'Projects'
date: 2024-05-19
type: page

# Optional header image (relative to `assets/media/` folder).
banner:
  image: 'project.jpg'  # 배너 이미지 파일 이름
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/)'  # 이미지 캡션

sections:
  - block: collection
    content:
      title: Projects
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
      offset: 0
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
    design:
      # Choose a listing view
      view: compact
---
