---
# Leave the homepage title empty to use the site title
title: "전북대학교 윤한서"
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
      text: |
        <div style="font-size:115%; text-align:center;">
          안녕하세요 😊 <b>전북대학교 컴퓨터인공지능학부</b> 2학년에 재학중인 윤한서입니다.<br>
          인공지능, 항공우주, 게임개발 분야에 매료되어 끊임없이 연구중입니다 ! ✨
        </div>

        <div style="text-align:center; margin-top:20px;">
          <a href="/files/resume.pdf" 
             target="_blank" 
             style="display:inline-block; background-color:#007BFF; color:white; padding:10px 20px; border-radius:8px; text-decoration:none; font-weight:600;">
             {{< icon name="download" pack="fas" >}} 이력서 다운로드 (PDF)
          </a>
        </div>
    design:
      css_class: "text-center py-10"


  - block: collection
    id: section-3
    content:
      title: "수행한 프로젝트들"
      text: "저의 수행한 프로젝트들을 볼 수 있습니다."
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - myproject
    design:
      view: community/custom_view
      columns: '3'

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
      columns: '3'

  - block: collection
    id: section-5
    content:
      title: 취미
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
      columns: '3'
---
