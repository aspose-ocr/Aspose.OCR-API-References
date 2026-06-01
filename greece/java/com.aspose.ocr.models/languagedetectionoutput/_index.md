---
title: "LanguageDetectionOutput"
second_title: "Αναφορά API του Aspose.OCR για Java"
description: "Γλώσσες που εντοπίστηκαν στο κείμενο της εικόνας"
type: docs
weight: 14
url: /el/java/com.aspose.ocr.models/languagedetectionoutput/
---

**Inheritance:**
java.lang.Object
```
public class LanguageDetectionOutput
```

Γλώσσες που εντοπίστηκαν στο κείμενο της εικόνας.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page)](#LanguageDetectionOutput-java.lang.String-java.util.List-java.util.Map.Entry-com.aspose.ocr.models.Language-java.lang.Float---int) |  |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [languages](#languages) | Μια ταξινομημένη λίστα γλωσσών που εντοπίστηκαν στο κείμενο της εικόνας, ταξινομημένες κατά πιθανότητα. |
| [page](#page) | Αριθμός σελίδας. |
| [source](#source) | Η πλήρης διαδρομή προς το αρχείο ή το URL, εάν υπάρχει. |

### LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page) {#LanguageDetectionOutput-java.lang.String-java.util.List-java.util.Map.Entry-com.aspose.ocr.models.Language-java.lang.Float---int}
```
public LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page)
```


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| _source | java.lang.String |  |
| _languages | java.util.List<java.util.Map.Entry<com.aspose.ocr.models.Language,java.lang.Float>> |  |
| _page | int |  |

### languages {#languages}
```
public List<Map.Entry<Language,Float>> languages
```


Μια ταξινομημένη λίστα γλωσσών που εντοπίστηκαν στο κείμενο της εικόνας, ταξινομημένες κατά πιθανότητα.

### page {#page}
```
public int page
```


Αριθμός σελίδας.

### source {#source}
```
public String source
```


Η πλήρης διαδρομή προς το αρχείο ή το URL, εάν υπάρχει. Κενό για ροές, πίνακες byte, base64.

