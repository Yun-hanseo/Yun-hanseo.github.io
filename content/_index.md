---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

# Leave the homepage title empty to use the site title
title: "전북대학교 윤한서 | Jeonbuk National University Yoon Hanseo"
date: 2022-10-24
type: landing

sections:
  - block: slider
    id: section-1
    content:
      slides:
      - title: 인공지능
        content: '인공지능 기반의 지능형 시스템'
        align: center
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.8
          overlay_color: '#000000'
          overlay_opacity: 0.35
          position: center
          color: '#333'
      - title: 항공우주
        content: 지구를 넘어 더 넓은 세계로
        align: center
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.8
          overlay_color: '#000000'
          overlay_opacity: 0.35
          position: center
          color: '#666'
      - title: 게임개발
        content: '사용자들에게 즐거움을 주는 게임'
        align: center
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.8
          overlay_color: '#000000'
          overlay_opacity: 0.35
          position: center
          color: '#555'
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '580px'
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000
      css_class: "mt-0 pt-0 pb-6"
  
  - block: features
    id: section-2
    content:
      title: ""
      text: >
        <span style="font-size:115%">
        안녕하세요 😊 **전북대학교 컴퓨터인공지능학부** 2학년에 재학중인 윤한서입니다. 인공지능, 항공우주, 게임개발 분야에 매료되어 끊임없이 연구중입니다 !
        </span>
    design:
      css_class: "text-center py-10"
  
  - block: collection
    id: section-3
    content:
      title: 수행 프로젝트
      subtitle: 
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - myproject
    design:
      view: community/custom_view
      columns: '2'

  - block: collection
    id: section-4
    content:
      title: 관심분야
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - interest
    design:
      view: card
      columns: '2'

  - block: collection
    id: section-5
    content:
      title: like
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - like
    design:
      view: card
      columns: '2'
---
