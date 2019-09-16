---
layout: post
title:  "Everyday Planner"
date:   2019-09-12
excerpt: "Check your plan everyday"
project: true
tag:
- project
- web
- node.js
- react
comments: true
---

![server-client-exchange](https://user-images.githubusercontent.com/10339017/64757486-478bb300-d56d-11e9-91e9-0d1bc5dbca3f.png)
<center>See a [<a href="https://github.com/skqoaudgh/Node.js-React-EverydayPlanner">source of this project</a>] hosted on GitHub.</center>


## Summary
* 이 프로젝트는 개인 프로젝트입니다.
* Node.js로 백엔드를, React로 프론트엔드를 구축하였습니다.
* 달력에 일정을 작성하여 자신의 일정을 관리할 수 있습니다.


## Tech Stack
* Node.js (Express)
* MongoDB (NoSQL)
* React


## Path Routing Page
* /auth - 계정 페이지
* /my - 달력 페이지


## Feature
* RSA 공개키 암호화를 이용하여 사용자의 개인정보를 보호합니다.
* 달력에 일정을 작성하여 자신의 일정을 관리할 수 있습니다.
* 일정의 제목, 내용, 마감날짜, 반복주기, 일정 아이콘을 설정하여 작성할 수 있습니다.
* 작성한 일정의 수정과 삭제가 가능합니다. 
* 각 계획별로 수행한 날짜에 표시할 수 있습니다. 수행한 게획은 중앙선이 씌어집니다.


## I learn this
* RSA 공개키 암호화를 이용한 정보 보안
* React와 Node.js API의 통신
* React 컨텍스트를 활용한 컴포넌트 간 정보 교환


## Screenshots
{% capture images %}
	https://user-images.githubusercontent.com/10339017/64763780-af48fa80-d57b-11e9-8816-3470016b6563.jpg
{% endcapture %}
{% include gallery images=images caption="Screenshots of project" cols=1 %}
