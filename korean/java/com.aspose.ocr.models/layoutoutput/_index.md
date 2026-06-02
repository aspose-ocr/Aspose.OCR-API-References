---
title: "LayoutOutput"
second_title: "Aspose.OCR for Java API 레퍼런스"
description: "이미지에서 감지된 콘텐츠 영역에 대한 정보"
type: docs
weight: 15
url: /ko/java/com.aspose.ocr.models/layoutoutput/
---

**Inheritance:**
java.lang.Object
```
public class LayoutOutput
```

이미지에서 감지된 콘텐츠 영역에 대한 정보.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [LayoutOutput()](#LayoutOutput) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
| [captions](#captions) | 감지된 캡션. |
| [equations](#equations) | 감지된 방정식. |
| [headers](#headers) | 감지된 헤더. |
| [images](#images) | 감지된 사진/일러스트. |
| [lists](#lists) | 감지된 목록. |
| [page](#page) | 페이지 번호. |
| [paragraphs](#paragraphs) | 감지된 단락. |
| [source](#source) | 파일 또는 URL의 전체 경로(있는 경우). |
| [tables](#tables) | 감지된 표. |

### LayoutOutput() {#LayoutOutput}
```
public LayoutOutput()
```


### captions {#captions}
```
public ArrayList<ContentArea> captions
```


감지된 캡션.

### equations {#equations}
```
public ArrayList<ContentArea> equations
```


감지된 방정식.

### headers {#headers}
```
public ArrayList<ContentArea> headers
```


감지된 헤더.

### images {#images}
```
public ArrayList<ContentArea> images
```


감지된 사진/일러스트.

### lists {#lists}
```
public ArrayList<ContentArea> lists
```


감지된 목록.

### page {#page}
```
public int page
```


페이지 번호.

### paragraphs {#paragraphs}
```
public ArrayList<ContentArea> paragraphs
```


감지된 단락.

### source {#source}
```
public String source
```


파일 또는 URL의 전체 경로(있는 경우). 스트림, 바이트 배열, base64의 경우 비워 둡니다.

### tables {#tables}
```
public ArrayList<ContentArea> tables
```


감지된 표.

