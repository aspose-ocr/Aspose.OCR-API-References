---
title: "LanguageDetectionOutput"
second_title: "Riferimento API di Aspose.OCR per Java"
description: "Lingue rilevate nel testo dell'immagine"
type: docs
weight: 14
url: /it/java/com.aspose.ocr.models/languagedetectionoutput/
---

**Inheritance:**
java.lang.Object
```
public class LanguageDetectionOutput
```

Lingue rilevate nel testo dell'immagine.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page)](#LanguageDetectionOutput-java.lang.String-java.util.List-java.util.Map.Entry-com.aspose.ocr.models.Language-java.lang.Float---int) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
| [languages](#languages) | Un elenco classificato delle lingue rilevate nel testo dell'immagine, ordinato per probabilità. |
| [page](#page) | Numero di pagina. |
| [source](#source) | Il percorso completo al file o URL, se presente. |

### LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page) {#LanguageDetectionOutput-java.lang.String-java.util.List-java.util.Map.Entry-com.aspose.ocr.models.Language-java.lang.Float---int}
```
public LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| _source | java.lang.String |  |
| _languages | java.util.List<java.util.Map.Entry<com.aspose.ocr.models.Language,java.lang.Float>> |  |
| _page | int |  |

### languages {#languages}
```
public List<Map.Entry<Language,Float>> languages
```


Un elenco classificato delle lingue rilevate nel testo dell'immagine, ordinato per probabilità.

### page {#page}
```
public int page
```


Numero di pagina.

### source {#source}
```
public String source
```


Il percorso completo al file o URL, se presente. Vuoto per stream, array di byte, base64.

