---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Hello!
        
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        I am JaeHyeon Cha, an aspiring developer B.A. degree expected in Computer Science at Jeonbuk National University. I am interested in game development and backend system architecture, with a goal of continuous growth.
  
  - block: slider
    content:
      slides:
      - title: 👋 Welcome!
        content: Here is the portfolio of JaeHyeon Cha, an aspiring developer.
        align: center
        background:
          image:
            filename: hello.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: I am...
        content: 'interested in game development and backend systems.'
        align: left
        background:
          image:
            filename: introduce.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
        link:
          icon: user
          icon_pack: fas
          text: Introduce
          url: ..en/author/jaehyeoncha/
          
      - title: Projects
        content: 'I am gaining experience through projects like the following.'
        align: left
        background:
          image:
            filename: project.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: book-open
          icon_pack: fas
          text: Projects
          url: ../projects/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '400px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 4000
---
