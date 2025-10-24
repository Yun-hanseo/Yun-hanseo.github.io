---
title: "Drawing"
subtitle: "Drawing by Observation"
date: 2025-10-13
summary: ""
type: like
layout: single
show_author: false

image:
  filename: drawintro.jpg
  caption: 'Image credit: [**Unsplash**](https://unsplash.com)'
---

<div style="
  display: flex; 
  align-items: stretch; 
  justify-content: center; 
  flex-wrap: wrap; 
  background: #dfddddff;; 
  border-radius: 20px; 
  overflow: hidden; 
  box-shadow: 0 6px 18px rgba(0,0,0,0.15);
  max-width: 1100px;
  margin: 50px auto;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
">
  
  <div style="flex: 1 1 50%; min-width: 350px; overflow: hidden;">
    <img src="drawing.jpg" alt="그림" 
         style="width: 100%; height: 100%; object-fit: cover; transition: transform 0.4s ease;">
  </div>

  <div style="flex: 1 1 50%; padding: 40px; background-color: #dfddddff; display: flex; flex-direction: column; justify-content: center;">
    <h2 style="font-size: 1.2rem; color: #003366; margin-bottom: 12px;">🎨 귀여니 / 그놈은 멋있었다</h2>
    <p style="font-size: 1rem; color: #333; line-height: 1.2;  word-break: keep-all; hyphens: auto;">
    I have loved drawing ever since I was a child — I even dreamed of becoming a painter.
    Although I don’t draw as often these days, I used to draw whenever I had free time in elementary, middle, and high school.
    When I draw, time flies by so quickly that I can focus completely on it without any distractions, which I really enjoy.
    However, I had to give up on my dream because I realized there were many people who were much better at drawing than I was.
    </p>
  </div>

</div>

<!-- Hover 효과 -->
<style>
  div[style*="max-width: 1100px;"]:hover {
    transform: translateY(-8px);
    box-shadow: 0 12px 28px rgba(0,0,0,0.2);
  }
  div[style*="max-width: 1100px;"]:hover img {
    transform: scale(1.05);
  }
</style>