---
layout: post
title:  "Game Shopping Web Application"
date:   2019-05-30
excerpt: "Pick up what you want to play"
project: true
tag:
- project
- web
- node.js
- bootstrap
comments: true
---

![AppImg](https://user-images.githubusercontent.com/10339017/59604420-10ad2900-9147-11e9-92e0-db494674b198.png)
<center>See a [<a href="https://github.com/skqoaudgh/Web-Nodejs-MongoDB-Shopping">source of this project</a>] hosted on GitHub.</center>


## Summary
* 이 프로젝트는 개인 프로젝트입니다. (2019-05-31 ~ 2019-06-17)
* 웹을 통해 제공되는 게임을 쇼핑카트에 담을 수 있습니다.
* 쇼핑카트에 담긴 게임들을 결제하여 구입할 수 있습니다.


## Tech Stack
* Bootstrap
* Node.js (Express)
* MongoDB (NoSQL)


## Path Routing Page
* /checkout - 결제
* /shopping - 쇼핑 카트 관리
* /users - 계정생성 및 로그인


## Feature
* Bootstrap을 이용하여 페이지 뷰가 구성되었습니다.
* 데이터베이스를 통해 게임 목록을 제공합니다.
* 계정생성 및 로그인을 할 수 있습니다.
* 원하는 게임의 버튼을 클릭하여 쇼핑 카트에 담을 수 있습니다.
* 카트에 담긴 게임을 관리할 수 있고 결제를 할 수 있습니다. 결제를 위해서 로그인을 해야합니다.
* 주문 내역을 확인할 수 있습니다.


## I learn this
* Bootstrap과 hbs(handlebars) 엔진을 이용한 페이지 View 구현
* Node.js의 라우팅
* MongoDB를 이용한 브라우저 세션 활용
* Passport.js 라이브러리를 이용한 계정 시스템
* flash, logger등 다양한 Node.js 패키지


## Screenshots
{% capture images %}
	https://user-images.githubusercontent.com/10339017/59606013-0f7dfb00-914b-11e9-9a49-aee62ae74351.jpg
{% endcapture %}
{% include gallery images=images caption="Screenshots of project" cols=1 %}


## Reference
[Academind Node.js, MongoDB Shopping Cart Tutorial (Youtube)](https://www.youtube.com/watch?v=-3vvxn78MH4&list=PL55RiY5tL51rajp7Xr_zk-fCFtzdlGKUp&index=2)
* 이 튜토리얼을 참고하여 프로젝트를 진행하였으며 아래의 사항을 새롭게 추가하여 개발하였습니다.
  1. 자바스크립트 최신 문법 적용 (let, const, arrow function, async/await)
  2. 라우터의 세분화
