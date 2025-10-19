---
# Leave the homepage title empty to use the site title
title: "Jeonbuk National University / Yun Hanseo"
date: 2022-10-24
type: landing

sections:
  - block: slider
    id: section-1
    content:
      slides:
      - title: Aritificial Inteeligence
        content: "Inteeligent systems based on AI technology"
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
      - title: Aerospace
        content: "Beyond the Earth, toward a broader univers"
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
      - title: Game Development
        content: 'Creating games that bring joy to people'
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
          Hello 😊 I'm **Hanseo Yun**, a sophomore majoring in Computer Science and Artificial Intelligence at **Jeonbuk National University**.  
        I'm deeply fascinated by Artificial Intelligence, Aerospace, and Game Development, and I’m constantly exploring new ideas in these fields! ✨
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
      title: "My projects"
      text: "Explore the projects I have worked on."
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - myproject
    design:
      view: card
      columns: "3"
      
---
