---
layout: post
title: "구글 애널리틱스"
date: 2021-12-16 19:40:34 +0900
categories: jekyll update
comments: true
---
1. 구글 애널리틱스 홈페이지에 들어가 회원가입을 한다.
2. 웹사이트 스트림을 만든다.
3. 측정 ID를 복사하여 config.yml에 
analytics:
  provider : "google-gtag"
  google:
    tracking_id: ID
로 추가한다
4. 구글 애널리틱스에 접속해 접속자 수를 확인한다.