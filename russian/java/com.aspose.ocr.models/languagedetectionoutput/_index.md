---
title: "LanguageDetectionOutput"
second_title: "Aspose.OCR для Java API Reference"
description: "Языки, обнаруженные в тексте изображения"
type: docs
weight: 14
url: /ru/java/com.aspose.ocr.models/languagedetectionoutput/
---

**Inheritance:**
java.lang.Object
```
public class LanguageDetectionOutput
```

Языки, обнаруженные в тексте изображения.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page)](#LanguageDetectionOutput-java.lang.String-java.util.List-java.util.Map.Entry-com.aspose.ocr.models.Language-java.lang.Float---int) |  |
## Поля

| Поле | Описание |
| --- | --- |
| [languages](#languages) | Ранжированный список языков, обнаруженных в тексте изображения, упорядоченный по вероятности. |
| [page](#page) | Номер страницы. |
| [source](#source) | Полный путь к файлу или URL, если имеется. |

### LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page) {#LanguageDetectionOutput-java.lang.String-java.util.List-java.util.Map.Entry-com.aspose.ocr.models.Language-java.lang.Float---int}
```
public LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| _source | java.lang.String |  |
| _languages | java.util.List<java.util.Map.Entry<com.aspose.ocr.models.Language,java.lang.Float>> |  |
| _page | int |  |

### languages {#languages}
```
public List<Map.Entry<Language,Float>> languages
```


Ранжированный список языков, обнаруженных в тексте изображения, упорядоченный по вероятности.

### page {#page}
```
public int page
```


Номер страницы.

### source {#source}
```
public String source
```


Полный путь к файлу или URL, если он указан. Пусто для потоков, массивов байтов, base64.

