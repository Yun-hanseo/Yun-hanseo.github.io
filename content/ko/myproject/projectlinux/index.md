---
title: "리눅스 계산 프로그램"
subtitle: "터미널 환경에서 동작하는 C 기반 계산기"
date: 2025-09-25
summary: "리눅스 환경에서 사칙연산과 괄호 연산을 수행하는 콘솔 프로그램"
layout: single
type: myproject
featured: true

image:
  filename: linux.jpg
  caption: 'Image credit: [**Unsplash**](https://unsplash.com)'

links:
  - icon: github
    icon_pack: fab
    url: https://github.com/Yun-hanseo/Linux-menu
---

![계산기 초기 화면](hsprojects/accountcreate.png)
**▲ 계좌 만들기**<br>
사용자가 ID,이름,계좌정보를 입력시 입력한 내용대로 데이터베이스에 저장

![연산 테스트](hsprojects/accountcheck.png)
**▲ 계좌 정보 확인**<br>
계좌 정보 확인을위해 ID 입력 시, ID,이름,계좌정보를 출력

![에러 처리](hsprojects/accountupdate.png)
**▲ 입출금하기**<br>
ID 입력 후 향수값 입력 시 출금을, 음수값 입력 시 입금을 한다.
양수값 입력 시 잔액보다 많으면 출금을 수행 하지 않는다.
