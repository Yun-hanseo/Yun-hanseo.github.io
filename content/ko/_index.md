---
# Leave the homepage title empty to use the site title
title: "전북대학교 윤한서"
date: 2022-10-24
type: landing

background:
  color_light: "#C9D6E2"
  color_dark: "#6a7b94ff"

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
              brightness: 0.6
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
              brightness: 0.6
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
              brightness: 0.6
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
        <div style="text-align: justify; text-justify: inter-word; line-height: 1.8; word-break: keep-all; hyphens: auto;">
           안녕하세요 😊 <b>전북대학교 컴퓨터인공지능학부 🎓 저는 전북대학교 컴퓨터인공지능학부 2학년 윤한서입니다.
           
           인공지능, 항공우주, 그리고 게임개발 분야에 깊은 열정을 가지고 있습니다.
          인공지능(AI)을 통해 인간의 사고를 모방하고 확장하는 지능형 시스템을 구현하고자 하며,
          이를 기반으로 자율비행·우주탐사 같은 항공우주 기술 발전에 기여하는 것이 목표입니다.
          또한 게임개발을 통해 플레이어에게 몰입감 있고 창의적인 경험을 제공하고 싶습니다.
          궁극적으로는 AI 기술을 실질적으로 적용하는 개발자로 성장하는 것이 제 꿈입니다. ✨
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
    content:
      id: section-3
      title: "프로젝트"
      subtitle: 
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - myproject
    design:
      view: card
      columns: '3'

  - block: collection
    content:
      id: section-4
      title: 관심분야
      subtitle: 
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
    content:
      id: section-5
      title: 취미
      subtitle:
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
