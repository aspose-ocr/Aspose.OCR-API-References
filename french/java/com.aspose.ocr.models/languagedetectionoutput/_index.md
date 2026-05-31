---
title: "LanguageDetectionOutput"
second_title: "Référence API d'Aspose.OCR pour Java"
description: "Langues détectées dans le texte de l'image"
type: docs
weight: 14
url: /fr/java/com.aspose.ocr.models/languagedetectionoutput/
---

**Inheritance:**
java.lang.Object
```
public class LanguageDetectionOutput
```

Langues détectées dans le texte de l'image.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page)](#LanguageDetectionOutput-java.lang.String-java.util.List-java.util.Map.Entry-com.aspose.ocr.models.Language-java.lang.Float---int) |  |
## Champs

| Champ | Description |
| --- | --- |
| [languages](#languages) | Une liste classée des langues détectées dans le texte de l'image, ordonnée par probabilité. |
| [page](#page) | Numéro de page. |
| [source](#source) | Le chemin complet du fichier ou de l'URL, le cas échéant. |

### LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page) {#LanguageDetectionOutput-java.lang.String-java.util.List-java.util.Map.Entry-com.aspose.ocr.models.Language-java.lang.Float---int}
```
public LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| _source | java.lang.String |  |
| _languages | java.util.List<java.util.Map.Entry<com.aspose.ocr.models.Language,java.lang.Float>> |  |
| _page | int |  |

### languages {#languages}
```
public List<Map.Entry<Language,Float>> languages
```


Une liste classée des langues détectées dans le texte de l'image, ordonnée par probabilité.

### page {#page}
```
public int page
```


Numéro de page.

### source {#source}
```
public String source
```


Le chemin complet vers le fichier ou l'URL, le cas échéant. Vide pour les flux, les tableaux d'octets, base64.

