---
title: "LanguageDetectionOutput"
second_title: "Aspose.OCR for Java API 레퍼런스"
description: "이미지 텍스트에서 감지된 언어"
type: docs
weight: 14
url: /ko/java/com.aspose.ocr.models/languagedetectionoutput/
---

**Inheritance:**
java.lang.Object
```
public class LanguageDetectionOutput
```

이미지 텍스트에서 감지된 언어.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page)](#LanguageDetectionOutput-java.lang.String-java.util.List-java.util.Map.Entry-com.aspose.ocr.models.Language-java.lang.Float---int) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
| [languages](#languages) | 가능성에 따라 정렬된, 이미지 텍스트에서 감지된 언어의 순위 목록입니다. |
| [page](#page) | 페이지 번호. |
| [source](#source) | 파일 또는 URL의 전체 경로(있는 경우). |

### LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page) {#LanguageDetectionOutput-java.lang.String-java.util.List-java.util.Map.Entry-com.aspose.ocr.models.Language-java.lang.Float---int}
```
public LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page)
```


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| _source | java.lang.String |  |
| _languages | java.util.List<java.util.Map.Entry<com.aspose.ocr.models.Language,java.lang.Float>> |  |
| _page | int |  |

### languages {#languages}
```
public List<Map.Entry<Language,Float>> languages
```


가능성에 따라 정렬된, 이미지 텍스트에서 감지된 언어의 순위 목록입니다.

### page {#page}
```
public int page
```


페이지 번호.

### source {#source}
```
public String source
```


파일 또는 URL의 전체 경로(있는 경우). 스트림, 바이트 배열, base64의 경우 비워 둡니다.

