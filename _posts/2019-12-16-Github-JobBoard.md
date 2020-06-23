---
layout: post
title:  "Github Job Board"
date:   2019-12-16
excerpt: "Get job informations given by github"
project: true
tag:
- project
- web
- node.js
- react
- redis
comments: true
---

![](https://user-images.githubusercontent.com/10339017/85363410-d47f8600-b55b-11ea-8454-f182975d62e3.png)
<center>See a [<a href="https://github.com/skqoaudgh/job-board-app">source of this project</a>] hosted on GitHub.</center>


## Summary
* 이 프로젝트는 개인 프로젝트입니다. (2019-12-14 ~ 2019-12-16)
* Node.js로 백엔드를, React로 프론트엔드를 구축하였습니다.
* 깃허브 구인 정보를 크롤링하여 Redis에 데이터를 저장합니다.
* 구인 정보를 화면에 페이지로 나누어 보여줍니다. 목록을 클릭하면 상세 정보를 확인할 수 있습니다.


## Tech Stack
* Node.js (Express)
* React.js
* Redis


## Feature
* 크롤링을 통하여 주기적으로 깃허브 구인 정보를 Redis 데이터베이스에 저장합니다.
* 구인 정보를 페이지로 나누어 화면에 보여줍니다.
* 목록을 클릭하면 상세 정보를 확인할 수 있습니다.
* 제목 혹은 'APPLY' 버튼을 눌러 해당 기업의 웹사이트로 이동할 수 있습니다.


## I learn this
* React와 Node.js API의 통신
* Redis
* 크롤링 (CronJob)


## Screenshots
{% capture images %}
	https://user-images.githubusercontent.com/10339017/85362797-553d8280-b55a-11ea-907e-dce6de4e8d66.PNG
	https://user-images.githubusercontent.com/10339017/85362729-2a532e80-b55a-11ea-8cae-9e4c74cc6615.PNG
	https://user-images.githubusercontent.com/10339017/85362730-2a532e80-b55a-11ea-9df5-a75e49fdc4b3.PNG
{% endcapture %}
{% include gallery images=images caption="Screenshots of project" cols=1 %}
