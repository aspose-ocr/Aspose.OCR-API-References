---
title: "TaalDetectieUitvoer"
second_title: "Aspose.OCR for Java API-referentie"
description: "Talen gedetecteerd in de afbeeldingstekst"
type: docs
weight: 14
url: /nl/java/com.aspose.ocr.models/languagedetectionoutput/
---

**Inheritance:**
java.lang.Object
```
public class LanguageDetectionOutput
```

Talen gedetecteerd in de afbeeldingstekst.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page)](#LanguageDetectionOutput-java.lang.String-java.util.List-java.util.Map.Entry-com.aspose.ocr.models.Language-java.lang.Float---int) |  |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [languages](#languages) | Een gerangschikte lijst van talen gedetecteerd in de afbeeldingstekst, gesorteerd op waarschijnlijkheid. |
| [page](#page) | Paginanummer. |
| [source](#source) | Het volledige pad naar het bestand of de URL, indien aanwezig. |

### LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page) {#LanguageDetectionOutput-java.lang.String-java.util.List-java.util.Map.Entry-com.aspose.ocr.models.Language-java.lang.Float---int}
```
public LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page)
```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| _source | java.lang.String |  |
| _languages | java.util.List<java.util.Map.Entry<com.aspose.ocr.models.Language,java.lang.Float>> |  |
| _page | int |  |

### languages {#languages}
```
public List<Map.Entry<Language,Float>> languages
```


Een gerangschikte lijst van talen gedetecteerd in de afbeeldingstekst, gesorteerd op waarschijnlijkheid.

### page {#page}
```
public int page
```


Paginanummer.

### source {#source}
```
public String source
```


Het volledige pad naar het bestand of de URL, indien aanwezig. Leeg voor streams, byte‑arrays, base64.

