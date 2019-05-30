---
layout: post
title:  "Event booking web application"
date:   2019-05-30
excerpt: " "
project: true
tag:
- project
- web
- react.js
- graphql
- node.js
comments: true
---

![LockerImg](https://user-images.githubusercontent.com/10339017/58608209-827b1b00-82dd-11e9-88c7-0b47bab07c63.PNG)
<center>See a [<a href="https://github.com/skqoaudgh/graphQL-React-BookingApp">source of this project</a>] hosted on GitHub.</center>


## Project summary
* 이 프로젝트는 개인 프로젝트입니다.
* 웹을 통해 이벤트(행사)를 등록하고 다른 사용자가 예약할 수 있도록 합니다.
     

## Tech Stack
* React.js
* Node.js
* GrahpQL
* MongoDB (NoSQL)


## Path Routing Page
* /auth - 회원가입 및 로그인
* /events: 이벤트 등록 및 확인
* /bookings: 예약된 이벤트 확인


## Feature
* 제목, 가격, 시간, 설명을 작성하여 이벤트를 등록할 수 있습니다.
* 등록된 이벤트를 예약할 수 있고, 예약한 이벤트에 대한 통계를 그래프로 확인할 수 있습니다.
* 계정을 등록할 수 있고 로그아웃 전 까지 계속 로그인이 유지됩니다.


## Screenshots
{% capture images %}
	https://user-images.githubusercontent.com/10339017/58608235-9757ae80-82dd-11e9-9540-5d6ab70b3b2f.PNG
	https://user-images.githubusercontent.com/10339017/58608239-99217200-82dd-11e9-8fd1-592126ebff17.PNG
  https://user-images.githubusercontent.com/10339017/58608240-99ba0880-82dd-11e9-9108-fb4c5b1d2bcb.PNG
  https://user-images.githubusercontent.com/10339017/58608242-9aeb3580-82dd-11e9-8839-94668e56aab5.PNG
{% endcapture %}
{% include gallery images=images caption="Screenshots of project" cols=2 %}
