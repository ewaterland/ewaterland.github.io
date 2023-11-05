---
layout: page
title: 인생네컷 프로그램
description: 2022.05.-2022.06. <br/> C++ / Visual Studio
img: assets/img/projects/9_project_thumbnail.png
importance: 3
category: Single
---

## 프로젝트 목표
- 사진 3장을 입력하면 셀프 스튜디오처럼 사진을 출력하기

---

## 프로젝트 내용
- 주제: 인생네컷 프로그램

- 과정
1. 구현할 사진을 RAW 파일로 변환
2. 3장의 컬러 이미지 파일 입력
3. 메뉴바에서 보정 종류 선택
4. 선택한 보정에 따라 영상처리

- 기능
메뉴바
[ 1 인생네컷 ]
- 3컷 -> 자동으로 사진 3개 입력창 띄움 -> 가로 3컷
- 4컷 -> 자동으로 사진 4개 입력창 띄움 -> 세로 4컷

문제1. 입력 따로 보정 따로 하는 작업에서 무한로딩 오류 발생
해결1. viewMode를 지우고, 무조건 4컷으로 출력


[ 2 보정 ]
- 좌우반전
- 흑백
- 밝게 => 산술덧셈 + 산술곱셈
- 어둡게 => 산술뺄셈 + 히스토그램 평활화
- 대비되게 => 산술곱셈 + 히스토그램 평활화

---

## 프로젝트 결과

<div class="col-sm mt-3 mt-md-0">
  {% include figure.html path="assets/img/projects/9_project_1.png" title="Menu" class="img-fluid rounded z-depth-1" %}
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/9_project_2.png" title="Result_대비되게" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/9_project_3.png" title="Result_밝게" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/9_project_4.png" title="Result_선명하게" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/9_project_5.PNG" title="Result_어둡게 " class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/9_project_6.png" title="Result_좌우반전 " class="img-fluid rounded z-depth-1" %}
    </div>
</div>
