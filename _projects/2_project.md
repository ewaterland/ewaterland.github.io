---
layout: page
title: 대학·기업·병원 협업 프로젝트
description: 2022 / Python / Deep Learning / Jupyter Notebook
img: assets/img/3.jpg
importance: 2
category: Team
giscus_comments: true
---

## 프로젝트 목표
- 기존에 있는 U-Net을 개발하여 성능 향상
- 직접 라벨링한 치아 데이터셋을 이용하여 성능 확인

## 프로젝트 내용
- [Supervise.ly](https://supervisely.com/)를 사용하여 병원에서 제공한 치아 데이터셋 103장 라벨링
- 라벨링한 치아 데이터셋을 활용하여 구조를 변경한 U-Net 성능 확인

## 프로젝트 결과
- Original U-Net Accuracy: 0.96734
- IU-Net Accuracy: 0.96897 => 약 0.17% 향상
- Si-yun Jeon, Su-ji Lee, Gyu-bin Kim. "Performance Analysis of various U-Net architectures for Image Segmentation". KIIS Autumn Conference 2022 Vol. 32, No. 2

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/2_project_1.jpg" title="result image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    IU-Net Result Image
</div>
