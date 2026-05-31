---
title: "LanguageDetectionOutput"
second_title: "Aspose.OCR for Java API 参考"
description: "图像文本中检测到的语言"
type: docs
weight: 14
url: /zh/java/com.aspose.ocr.models/languagedetectionoutput/
---

**Inheritance:**
java.lang.Object
```
public class LanguageDetectionOutput
```

图像文本中检测到的语言。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page)](#LanguageDetectionOutput-java.lang.String-java.util.List-java.util.Map.Entry-com.aspose.ocr.models.Language-java.lang.Float---int) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
| [languages](#languages) | 按可能性排序的图像文本中检测到的语言列表。 |
| [page](#page) | 页码。 |
| [source](#source) | 文件或 URL 的完整路径（如果有）。 |

### LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page) {#LanguageDetectionOutput-java.lang.String-java.util.List-java.util.Map.Entry-com.aspose.ocr.models.Language-java.lang.Float---int}
```
public LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| _source | java.lang.String |  |
| _languages | java.util.List<java.util.Map.Entry<com.aspose.ocr.models.Language,java.lang.Float>> |  |
| _page | int |  |

### languages {#languages}
```
public List<Map.Entry<Language,Float>> languages
```


按可能性排序的图像文本中检测到的语言列表。

### page {#page}
```
public int page
```


页码。

### source {#source}
```
public String source
```


文件或 URL 的完整路径（如果有）。对于流、字节数组、base64 为空。

