---
title: "Markdown 이미지 크기 조절, 정렬 방법"
date: "2019-05-06"
template: "post"
draft: false
path: "/posts/markdown-image-tag/"
description: "github에서 Markdown 형식의 문서를 작성할 때, 이미지의 크기를 조절하는 방법과 정렬하는 방법을 정리한 글입니다."
category: "ETC"
---

## 이미지 첨부 : 간단버전

이미지를 첨부하는 가장 간단한 방법은 아래와 같다.

    ![alt](src)

## 이미지 크기 조정하기

`<img>` 태그로 이미지를 첨부하고, width, height 속성을 준다.

    <img src="image_src" height="100px" width="300px">

## 이미지 정렬하기

### 가운데 정렬하기

마찬가지로 `<img>` 태그로 이미지를 첨부하고, 이미지 태그를 p태그로 감싼다.

    <p align="center"><img src="image_src"></p>

### 오른쪽 정렬하기, 왼쪽 정렬하기

왼쪽 정렬은 기본값이며, 오른쪽 정렬은 `img` 태그에 align 속성을 준다.

    <img src="image_src" align="right">

---

## 참고링크

-   [aligning-images.md](https://gist.github.com/DavidWells/7d2e0e1bc78f4ac59a123ddf8b74932d)
