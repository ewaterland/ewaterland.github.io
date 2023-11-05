---
layout: page
title: MFC 노래 퀴즈 프로그램
description: 2022.11.-2022.12. <br/> C++ / MFC / Visual Studio 2019
img: assets/img/projects/4_project_1.png
importance: 3
category: Team
---

해당 프로그램은 정보통신공학부의 학부 과정인 "통신SW설계" 과목을 수강하면서 진행하게 된 팀 프로젝트입니다. 팀원은 총 3명으로 구성되어 있으며, 제가 조장으로서 프로그램 개발을 맡았습니다.

## 프로젝트 목표
- 하나의 서버에 여러 참가자들이 모여서 재생되는 노래를 듣고, 채팅을 이용해 선착순으로 노래 제목을 맞추는 게임

---

## 프로젝트 내용
1. 클라이언트가 닉네임을 설정한 후 서버와 연결
2. 서버 또는 클라이언트에서 원하는 모드로 게임 시작
  - 일반 모드: 노래 30초 재생
  - 하드 모드: 노래 MR 30초 재생
3. 노래가 나오는 동안 참가자들은 채팅을 이용해 노래의 제목을 맞힘
4. 선착순으로 정답을 가장 빨리 맞힌 참가자 1명에게 점수가 주어짐
  - 일반 모드: 1점
  - 하드 모드: 2점
5. 서버에서 게임을 종료하거나 순위를 보고 싶은 참가자가 있다면 순위 공개

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/4_project_2.png" title="Flow image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    프로그램 흐름도
</div>

---

## 프로젝트 결과

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/4_project_1.png" title="Result image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    프로그램 작동 결과물
</div>


