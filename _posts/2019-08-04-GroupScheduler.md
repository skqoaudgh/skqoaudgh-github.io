---
layout: post
title:  "Group Scheduler"
date:   2019-08-04
excerpt: "Make schedules with many peaple"
project: true
tag:
- project
- web
- node.js
comments: true
---

![calendar](https://user-images.githubusercontent.com/10339017/62419626-f1029d80-b6bf-11e9-9f9a-bd1941b565ce.png)
<center>See a [<a href="https://github.com/skqoaudgh/Node.js-GroupScheduler">source of this project</a>] hosted on GitHub.</center>


## Summary
* 이 프로젝트는 개인 프로젝트입니다. (2019-07-30 ~ 2019-08-10)
* 여러 사람들과 일정(약속)을 잡을 때 사용할 수 있는 웹입니다.
* 일정을 만들고 자신의 가능하거나 불가능한 기간을 입력하여 모두가 가능한 기간을 보여줍니다.


## Tech Stack
* Node.js (Express, ejs)
* MongoDB (NoSQL)


## Path Routing Page
* /index - 메인 페이지 (일정 목록 출력)
* /create - 일정 만들기
* /schedule/:id - 일정에 대한 상세 설명
* /schedule/calendar/:id - 일정에 대해 사용자들이 입력한 기간 표시
* /auth/:id - 일정에 대한 보안코드 입력


## Feature
* Express ejs 템플릿 뷰를 이용하여 페이지를 제공합니다.
* 일정을 만들고 여러 사람들과 공유할 수 있습니다.
* 사진자료, 설명 등을 함께 올려 일정에 대한 상세 설명을 볼 수 있습니다.
* 일정 목록이 시간 내림차순으로 정렬되며 마감된 목록은 가장 아래에서 출력됩니다.
* 보안코드를 입력하여 일정에 접근해야 하므로 특정 사람만 접근하도록 할 수 있습니다.
* 일정에 대해 사용자들이 가능하거나 불가능한 기간을 입력하고 그에 따른 가능한 기간을 달력에 표시하여 보여줍니다.
* 날짜에 대해 어느 사용자가 불가능한 기간을 입력했는지 확인할 수 있습니다.


## I learn this
* Express ejs 템플릿 뷰의 활용
* Node.js의 라우팅
* multer 패키지를 이용한 파일 업로드
* bitly API
* AWS Lightsail Node.js 배포

## Screenshots
{% capture images %}
	https://user-images.githubusercontent.com/10339017/62419910-ce738300-b6c5-11e9-9fa3-8638972bb3d7.jpg
{% endcapture %}
{% include gallery images=images caption="Screenshots of project" cols=1 %}
