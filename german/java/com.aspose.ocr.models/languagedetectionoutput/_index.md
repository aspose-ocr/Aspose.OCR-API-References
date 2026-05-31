---
title: "LanguageDetectionOutput"
second_title: "Aspose.OCR für Java API-Referenz"
description: "In dem Bildtext erkannte Sprachen"
type: docs
weight: 14
url: /de/java/com.aspose.ocr.models/languagedetectionoutput/
---

**Inheritance:**
java.lang.Object
```
public class LanguageDetectionOutput
```

Sprachen, die im Bildtext erkannt wurden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page)](#LanguageDetectionOutput-java.lang.String-java.util.List-java.util.Map.Entry-com.aspose.ocr.models.Language-java.lang.Float---int) |  |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [languages](#languages) | Eine nach Wahrscheinlichkeit geordnete Rangliste der im Bildtext erkannten Sprachen. |
| [page](#page) | Seitennummer. |
| [source](#source) | Der vollständige Pfad zur Datei oder URL, falls vorhanden. |

### LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page) {#LanguageDetectionOutput-java.lang.String-java.util.List-java.util.Map.Entry-com.aspose.ocr.models.Language-java.lang.Float---int}
```
public LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| _source | java.lang.String |  |
| _languages | java.util.List<java.util.Map.Entry<com.aspose.ocr.models.Language,java.lang.Float>> |  |
| _page | int |  |

### languages {#languages}
```
public List<Map.Entry<Language,Float>> languages
```


Eine nach Wahrscheinlichkeit geordnete Rangliste der im Bildtext erkannten Sprachen.

### page {#page}
```
public int page
```


Seitennummer.

### source {#source}
```
public String source
```


Der vollständige Pfad zur Datei oder URL, falls vorhanden. Leer für Streams, Byte‑Arrays, Base64.

