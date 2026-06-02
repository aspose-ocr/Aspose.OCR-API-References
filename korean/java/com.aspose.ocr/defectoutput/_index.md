---
title: "DefectOutput"
second_title: "Aspose.OCR for Java API 레퍼런스"
description: "이미지에서 식별된 결함이 포함된 영역"
type: docs
weight: 16
url: /ko/java/com.aspose.ocr/defectoutput/
---

**Inheritance:**
java.lang.Object
```
public class DefectOutput
```

이미지에서 식별된 결함이 포함된 영역.
## 필드

| 필드 | 설명 |
| --- | --- |
| [Page](#Page) | 페이지 번호. |
| [Source](#Source) | 파일 또는 URL의 전체 경로(있는 경우). |
| [defectAreas](#defectAreas) | 이미지 결함 및 해당 결함이 발견된 영역 목록. |


### Page {#Page}
```
public int Page
```


페이지 번호.

### Source {#Source}
```
public String Source
```


파일 또는 URL의 전체 경로(있는 경우). 스트림, 바이트 배열 및 Base64 인코딩 파일의 경우 비워 둡니다.

### defectAreas {#defectAreas}
```
public ArrayList<DefectAreas> defectAreas
```


이미지 결함 및 해당 결함이 발견된 영역 목록.
