---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        안녕하세요!
        
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        전북대학교 컴퓨터공학부에서 재학 중인 개발자 지망생 차재현입니다. 저는 게임 개발 및 백엔드 시스템 구축에 관심을 두고 지속적인 성장에 목표를 두고 있습니다.
  
  - block: slider
    content:
      slides:
      - title: 👋 어서오세요!
        content: 개발자 지망생 차재현의 포트폴리오입니다.
        align: center
        background:
          image:
            filename: hello.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: 저는..
        content: '게임 개발과 백엔드에 관심을 갖고 있습니다'
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
          url: ../author/차재현/
          
      - title: 프로젝트
        content: '다음과 같은 프로젝트로 경험을 쌓고 있습니다.'
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
