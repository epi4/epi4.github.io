---
layout: post
title: 포트폴리오
excerpt: "이무정 포트폴리오"
description: ""
categories: programming
tags: [포트폴리오]
author: epi4
comments: true
share: true
---

##### 점프 올스타즈
개발 도구 : C++, Win32

캐릭터들이 서로 싸우는 대전 액션 게임

개발 기간 : 2014.03.18 ~ 2014.04.08

http://www.mediafire.com/file/2vesckvoouoixfx/JumpAllstars_ver_65.zip

<iframe width="560" height="315" src="https://www.youtube.com/embed/Su7p872klT4" frameborder="0" allowfullscreen></iframe>

1인 개발. WinAPI를 배우고 처음 작업한 프로젝트.

##### 스타크래프트
개발 도구 : C++, Directx9, MFC

전략시뮬레이션 게임

개발 기간 : 2014.05.16 ~ 2014.06.10

http://www.mediafire.com/file/1jg419j2zeli7zr/StarCraft_ver_80.zip

<iframe width="560" height="315" src="https://www.youtube.com/embed/hFHVYx8Zppc" frameborder="0" allowfullscreen></iframe>

1인 개발. MFC로 맵툴을 만들어서 제작. 각 건물, 유닛의 HP, 빌드 시간 등을 툴로 만든 후 클라이언트에서 데이터를 파싱하는 방식이다. 옵저버 패턴을 사용하여 UI에서 HP 상태들을 받게 하였다.

##### 리그오브레전드
개발 도구 : C++, Directx9, MFC

AOS 게임

개발 기간 : 2014.08.08 ~ 2014.09.29

http://www.mediafire.com/file/qoz27se1e406xm6/LoL_ver.79.zip

<iframe width="560" height="315" src="https://www.youtube.com/embed/uJ4ETEhGc9c" frameborder="0" allowfullscreen></iframe>

1인 개발. 네비메쉬를 이용하여 길찾기를 구현. 시연회용으로 각 캐릭터를 단축키를 통해 변경하며 스킬을 사용할 수 있게 하였다.

##### 킬링플로어
개발 도구 : C++, Winsock

멀티 FPS 게임

개발 기간 : 2014.10.25 ~ 2014.12.24

http://www.mediafire.com/file/2q9933oxjwml9kd/MooServerEngine13.zip

<iframe width="560" height="315" src="https://www.youtube.com/embed/dBJnLg2pYzc" frameborder="0" allowfullscreen></iframe>

6인 팀프로젝트. 서버 부분을 맡았다. 메모리 풀을 통해 버퍼를 재사용하여 new/delete의 비용을 줄였다. 자체 log 파일을 이용하여 로그를 쉽게 남기게끔 하였다.

##### 팔라독&히어로즈
개발 도구 : C++, Winsock, mysql, asp.net

모바일 타워 디펜스형 게임

참여 기간 : 2015.03.23 ~ 2016.04.11

<iframe width="560" height="315" src="https://www.youtube.com/embed/f2aRNIY_UCw" frameborder="0" allowfullscreen></iframe>

C++ 기반의 서버 프레임워크에서 컨텐츠 추가하는 업무를 담당하였다. 새로운 패킷이나 아이템 타입을 구현하여 이를 DB에 추가했다. 신규 아이템인 룬, 정수, 우편함 모두 받기 기능 등을 맡았다. 그 외에 asp.net 운영툴을 통해 GM에게 서비스하였다.

##### 자동차 시뮬레이터
개발 도구 : Unigine Engine

자동차 가상 훈련 시뮬레이터

참여 기간 : 2016.07.25 ~ 2017.08.31

<iframe width="560" height="315" src="https://www.youtube.com/embed/NOjdWAiYVGk" frameborder="0" allowfullscreen></iframe>

Unigine 엔진 기반으로 신규 컨텐츠 추가를 담당했다. 링크한 영상외에 회사에서 외부로 보여주는 자료가 없어서 직접 작업한 부분은 나오지 않고 있다.

Unigine 엔진 1.0에서 2.0으로 엔진 컨버팅 작업과 미니맵 뷰, 리플레이 뷰 UI 추가, 신규 모션 프로그램인 InnoMotion과 연동 기능들을 맡았다.

##### FaceAPI
개발 도구 : C++, opencv

캠으로 얼굴 인식하여 얼굴의 rotation 값을 받는 프로그램

개발 기간 : 2017.06.02 ~ 2017.08.08

https://github.com/epi4/faceapi

<iframe width="560" height="315" src="https://www.youtube.com/embed/Ay68ptWH6oU" frameborder="0" allowfullscreen></iframe>

캠에 찍힌 영상을 통해 얼굴 인식을 하고 얼굴의 x축, y축 값을 받는 프로그램을 기반으로 작업. 내가 담당한 부분은 오픈소스에서 제공해주는 API를 통해 사용자가 왼쪽/오른쪽을 바라보는지, 밑/아래를 바라보는지를 확인해서 이 값을 시뮬레이터에 전송해주는 부분을 맡았다.