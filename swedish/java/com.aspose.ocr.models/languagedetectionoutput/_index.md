---
title: "LanguageDetectionOutput"
second_title: "Aspose.OCR för Java API-referens"
description: "Språk som upptäckts i bildens text"
type: docs
weight: 14
url: /sv/java/com.aspose.ocr.models/languagedetectionoutput/
---

**Inheritance:**
java.lang.Object
```
public class LanguageDetectionOutput
```

Språk som upptäckts i bildtexten.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page)](#LanguageDetectionOutput-java.lang.String-java.util.List-java.util.Map.Entry-com.aspose.ocr.models.Language-java.lang.Float---int) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [languages](#languages) | En rangordnad lista över språk som upptäckts i bildens text, sorterade efter sannolikhet. |
| [page](#page) | Sidnummer. |
| [source](#source) | Den fullständiga sökvägen till filen eller URL:en, om någon. |

### LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page) {#LanguageDetectionOutput-java.lang.String-java.util.List-java.util.Map.Entry-com.aspose.ocr.models.Language-java.lang.Float---int}
```
public LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| _source | java.lang.String |  |
| _languages | java.util.List<java.util.Map.Entry<com.aspose.ocr.models.Language,java.lang.Float>> |  |
| _page | int |  |

### languages {#languages}
```
public List<Map.Entry<Language,Float>> languages
```


En rangordnad lista över språk som upptäckts i bildens text, sorterade efter sannolikhet.

### page {#page}
```
public int page
```


Sidnummer.

### source {#source}
```
public String source
```


Den fullständiga sökvägen till filen eller URL:en, om någon. Tom för strömmar, byte‑arrayer, base64.

