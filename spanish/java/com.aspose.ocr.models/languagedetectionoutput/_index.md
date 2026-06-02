---
title: "LanguageDetectionOutput"
second_title: "Referencia de API de Aspose.OCR para Java"
description: "Idiomas detectados en el texto de la imagen"
type: docs
weight: 14
url: /es/java/com.aspose.ocr.models/languagedetectionoutput/
---

**Inheritance:**
java.lang.Object
```
public class LanguageDetectionOutput
```

Idiomas detectados en el texto de la imagen.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page)](#LanguageDetectionOutput-java.lang.String-java.util.List-java.util.Map.Entry-com.aspose.ocr.models.Language-java.lang.Float---int) |  |
## Campos

| Campo | Descripción |
| --- | --- |
| [languages](#languages) | Una lista clasificada de idiomas detectados en el texto de la imagen, ordenada por probabilidad. |
| [page](#page) | Número de página. |
| [source](#source) | La ruta completa al archivo o URL, si existe. |

### LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page) {#LanguageDetectionOutput-java.lang.String-java.util.List-java.util.Map.Entry-com.aspose.ocr.models.Language-java.lang.Float---int}
```
public LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| _source | java.lang.String |  |
| _languages | java.util.List<java.util.Map.Entry<com.aspose.ocr.models.Language,java.lang.Float>> |  |
| _page | int |  |

### languages {#languages}
```
public List<Map.Entry<Language,Float>> languages
```


Una lista clasificada de idiomas detectados en el texto de la imagen, ordenada por probabilidad.

### page {#page}
```
public int page
```


Número de página.

### source {#source}
```
public String source
```


La ruta completa al archivo o URL, si la hay. Vacío para flujos, matrices de bytes, base64.

