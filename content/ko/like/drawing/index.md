---
title: "그림그리기"
subtitle: "보고 따라그리기"
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
      저는 어렸을때부터 꿈이 화가였을 정도로 그림그리는 것을 좋아했습니다. 
      최근에는 그림을 잘 그리지는 않지만 초등학교,중학교,고등학교때는 틈틈히 시간이 나면 모두 그림을 그렸습니다. 그림을 그리다보면 몇시간씩 훌쩍 지나가기 때문에 잡생각없이 온전히 그림에 집중할 수 있어서 좋았습니다.<br>
      하지만 저보다 그림을 잘 그리는 사람이 많기에 꿈을 포기할 수 밖에 없었습니다.
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


