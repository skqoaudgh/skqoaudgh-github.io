---
layout: post
title:  "Phonebook API"
date:   2019-08-27
excerpt: "Phonebook API made with Node.js for Rest API, GraphQL API"
project: true
tag:
- project
- web
- node.js
- rest
- graphql
comments: true
---

![server-client-exchange](https://user-images.githubusercontent.com/10339017/63743285-b4991a80-c8d6-11e9-8811-a1d9d7732580.png)
<center>See a [<a href="https://github.com/skqoaudgh/Node.js-Phonebook-RestAPI">source of this project</a>] hosted on GitHub.</center>


## Summary
* 이 프로젝트는 개인 프로젝트입니다.
* 계정 생성, 전화번호부, 번호차단목록의 관리를 위한 API 입니다.
* Rest API, GraphQL API의 두 가지 API 버전이 있습니다.


## Tech Stack
* Node.js (Express, ejs)
* MongoDB (NoSQL)
* Rest, GraphQL


## Path Routing Page
* Rest API
  * /auth - 권한 자원의 접근을 위한 엔드포인트
  * /users - 사용자 계정 자원의 접근을 위한 엔드포인트
  * /users/:userId/phonebooks - 전화번호부 자원의 접근을 위한 엔드포인트
  * /users/:userId/blacklist - 번호차단목록 자원의 접근을 위한 엔드포인트

* GraphQL
  * /graphql - 모든 자원의 접근을 위한 엔드포인트


## Feature
* bcrypt(Hashing Function)을 이용하여 사용자의 개인정보를 보호합니다.
* jwt를 이용하여 권한을 가진 사용자만 자원에 접근할 수 있습니다.
* Rest API와 GraphQL API로 자원에 접근할 수 있습니다.
* 예외및 오류 발생 시, HTTP 상태코드와 함께 메시지를 보내 사용자가 인지할 수 있습니다.


## I learn this
* bcrypt(Hashing Function)을 이용한 정보 보안
* Rest, GraphQL의 개념과 사용, 장단점
