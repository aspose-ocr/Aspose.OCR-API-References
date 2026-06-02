---
title: "SkewOutput"
second_title: "Aspose.OCR for Java API 레퍼런스"
description: "파일 이름과 각도(도) 단위의 기울기 각도에 대한 데이터"
type: docs
weight: 23
url: /ko/java/com.aspose.ocr.models/skewoutput/
---

**Inheritance:**
java.lang.Object
```
public class SkewOutput
```

파일 이름과 회전 각도(도) 정보를 포함한 데이터.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [SkewOutput()](#SkewOutput) |  |
| [SkewOutput(String source, double angle, int page)](#SkewOutput-java.lang.String-double-int) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
| [Angle](#Angle) | 각도(도) 단위의 기울기 각도. |
| [Page](#Page) | 페이지 번호. |
| [Source](#Source) | 파일 또는 URL의 전체 경로(있는 경우). |

### SkewOutput() {#SkewOutput}
```
public SkewOutput()
```


### SkewOutput(String source, double angle, int page) {#SkewOutput-java.lang.String-double-int}
```
public SkewOutput(String source, double angle, int page)
```


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 소스 | java.lang.String |  |
| 각도 | double |  |
| 페이지 | int |  |

### Angle {#Angle}
```
public double Angle
```


각도(도) 단위의 기울기 각도.

### Page {#Page}
```
public int Page
```


페이지 번호.

### Source {#Source}
```
public String Source
```


파일 또는 URL의 전체 경로(있는 경우). 스트림, 바이트 배열, base64의 경우 비워 둡니다.
