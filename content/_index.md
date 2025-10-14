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
        content: '사용자들에게 더 좋고 더 나은 앱/웹 개발'
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
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
