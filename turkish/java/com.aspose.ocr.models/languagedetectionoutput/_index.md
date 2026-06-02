---
title: "LanguageDetectionOutput"
second_title: "Aspose.OCR for Java API Referansı"
description: "Görüntü metninde tespit edilen diller"
type: docs
weight: 14
url: /tr/java/com.aspose.ocr.models/languagedetectionoutput/
---

**Inheritance:**
java.lang.Object
```
public class LanguageDetectionOutput
```

Görüntü metninde algılanan diller.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page)](#LanguageDetectionOutput-java.lang.String-java.util.List-java.util.Map.Entry-com.aspose.ocr.models.Language-java.lang.Float---int) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [languages](#languages) | Görüntü metninde tespit edilen dillerin olasılığa göre sıralanmış bir listesi. |
| [page](#page) | Sayfa numarası. |
| [source](#source) | Dosyanın veya URL'nin tam yolu, varsa. |

### LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page) {#LanguageDetectionOutput-java.lang.String-java.util.List-java.util.Map.Entry-com.aspose.ocr.models.Language-java.lang.Float---int}
```
public LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| _source | java.lang.String |  |
| _languages | java.util.List<java.util.Map.Entry<com.aspose.ocr.models.Language,java.lang.Float>> |  |
| _page | int |  |

### languages {#languages}
```
public List<Map.Entry<Language,Float>> languages
```


Görüntü metninde tespit edilen dillerin olasılığa göre sıralanmış bir listesi.

### page {#page}
```
public int page
```


Sayfa numarası.

### source {#source}
```
public String source
```


Dosyanın veya URL'nin tam yolu, varsa. Akışlar, bayt dizileri, base64 için boş bırakılır.

