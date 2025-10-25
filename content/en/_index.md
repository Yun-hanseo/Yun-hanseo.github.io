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
              brightness: 0.6
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
              brightness: 0.6
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
        <div style="font-size:115%; text-align:center;">
          Hello 😊
          <b>Jeonbuk National University, School of Computer Science and Artificial Intelligence</b> 🎓

          I’m Hanseo Yun, a sophomore majoring in Computer Science and Artificial Intelligence at Jeonbuk National University.
          I have a deep passion for Artificial Intelligence (AI), Aerospace, and Game Development.

          Through AI, I aim to design intelligent systems that mimic and extend human thinking,
          and ultimately contribute to the advancement of autonomous flight and space exploration technologies.
          In addition, I aspire to create immersive and creative experiences through game development.

          My ultimate goal is to become a developer who applies AI technology in real-world fields to make meaningful innovations. ✨
        </div>

        <div style="text-align:center; margin-top:20px;">
          <a href="/files/resume.pdf" 
             target="_blank" 
             style="display:inline-block; background-color:#007BFF; color:white; padding:10px 20px; border-radius:8px; text-decoration:none; font-weight:600;">
             {{< icon name="download" pack="fas" >}} Download Resume (PDF)
          </a>
        </div>
    design:
      css_class: "text-center py-10"

  - block: collection
    content:
      id: section-3
      title: "Projects"
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
      title: Interest
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
      title: Hobby
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
