---
layout: post
title:  "Event booking web application"
date:   2019-05-30
excerpt: "Make event and booking with web easily"
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
	https://user-images.githubusercontent.com/10339017/58616567-eced8480-82f8-11e9-84f5-f709b9338f6c.jpg
{% endcapture %}
{% include gallery images=images caption="Screenshots of project" cols=1 %}
