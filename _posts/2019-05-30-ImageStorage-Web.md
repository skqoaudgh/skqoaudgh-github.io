---
layout: post
title:  "Image Storage web application"
date:   2019-05-30
excerpt: "Wanna keep funny image or something?"
project: true
tag:
- project
- web
- react.js
- graphql
- node.js
comments: true
---

![LockerImg](https://user-images.githubusercontent.com/10339017/58633752-69e22380-8324-11e9-8a1f-fbe2d0f51c65.png)
<center>See a [<a href="https://github.com/skqoaudgh/Web-BakjeStorage">source of this project</a>] hosted on GitHub.</center>


## Summary
* 이 프로젝트는 개인 프로젝트입니다.
* 웹을 통해 이미지를 업로드하고 회원들이 업로드한 이미지를 볼 수 있습니다.
* 이미지를 Base64 방식으로 인코딩하여 데이터베이스에 저장합니다.


## Tech Stack
* React.js
* Node.js
* GrahpQL
* MongoDB (NoSQL)


## Path Routing Page
* /auth - 회원가입 및 로그인
* /write: 업로드
* /list: 이미지 보기


## Feature
* 제목, 간단한 코멘트, 사진과 함께 글을 업로드할 수 있습니다.
* '인스타그램', '페이스북' 처럼 다른 사용자가 업로드한 글을 볼 수 있습니다.
* 내가 업로드한 글만 따로 볼 수 있습니다.
* 검색어를 통해 원하는 글만 볼 수 있습니다.


## I learn this
* React.js Context API를 이용한 상태관리
* GraphQL을 이용한 Endpoint 설계 및 구현 방법
* JWT의 토큰 방식의 계정 시스템 (계정생성, 로그인)
* Base64 인코딩, Multer NPM 라이브러리, Apollo 라이브러리를 이용한 파일(이미지) 업로드
* LocalStorage, SessionStorage, Cookie


## Screenshots
{% capture images %}
	https://user-images.githubusercontent.com/10339017/58633657-0c4dd700-8324-11e9-83be-bd61beba05ce.jpg
{% endcapture %}
{% include gallery images=images caption="Screenshots of project" cols=1 %}
