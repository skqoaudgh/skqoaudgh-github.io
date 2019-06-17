---
layout: post
title:  "Locker Management Application"
date:   2019-03-21
excerpt: "Applying, Managing a locker with GUI (Java Swing)"
project: true
tag:
- project 
- java
comments: true
---

![LockerImg](https://user-images.githubusercontent.com/10339017/54734183-24490200-4be1-11e9-9bc7-5f6e3b62b748.png)
<center>See a [<a href="https://github.com/flokker/Object_Programming">source of this project</a>] hosted on GitHub.</center>


## Summary
* 이 프로젝트는 팀 프로젝트입니다.
* 이 프로젝트는 객체지향설계 능력을 함양시키기 위해 시작된 프로젝트입니다.
* 이 프로젝트는 Java Swing을 이용한 GUI 사물함 관리및 신청 어플리케이션을 목표로 합니다.
* 엑셀을 데이터베이스로서 사용하기 위해 아파치 POI를 사용했습니다.
     

## Tech Stack
* Java
* Apache POI 라이브러리


## Feature
* GUI를 이용하여 사물함의 관리 및 신청
* 사물함의 상태에 따라 다른 색깔을 사용하여 쉽게 확인
* 여러 조건을 검색어로 사용하여 사물함 확인
* 현재 보고 있는 위치에 따라 미니맵의 위치정보 변경
* 미니맵과 좌우 이동 버튼을 통해 여러 구역의 사물함 확인
* 엑셀로 데이터가 저장되어 관리


## This is my Part
* 데이터 관리및 검색 기능
* GUI와 Operation의 인터페이스 연동
* POI 라이브러리를 이용한 엑셀 연동


## I learn this
* 객체지향설계 방법
* Swing을 이용한 자바 GUI 코딩
* 인터페이스 형식 통일화의 중요성


## Screenshots
{% capture images %}
	https://user-images.githubusercontent.com/10339017/54734693-be5e7980-4be4-11e9-84c6-9d33c585d143.png
	https://user-images.githubusercontent.com/10339017/54735155-b18f5500-4be7-11e9-824b-f20f169e5b1c.png
{% endcapture %}
{% include gallery images=images caption="Screenshots of project" cols=2 %}
