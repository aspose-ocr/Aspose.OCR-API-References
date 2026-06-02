---
title: "InputType"
second_title: "Aspose.OCR for Java API-referentie"
description: "Typen afbeeldingen/documenten voor verwerking/herkenning"
type: docs
weight: 38
url: /nl/java/com.aspose.ocr/inputtype/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum InputType extends Enum<InputType>
```

Typen afbeeldingen/documenten voor verwerking/herkenning.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [Base64](#Base64) | base64‑string met de afbeelding of pad naar het .txt‑bestand met de base64‑inhoud. |
| [Directory](#Directory) | Pad naar de map. |
| [PDF](#PDF) | Gescanst PDF‑document uit een bestand of uit een InputStream. |
| [SingleImage](#SingleImage) | Ondersteunt GIF, PNG, JPEG, BMP, TIFF, JFIF, InputStream, BufferedImage. |
| [TIFF](#TIFF) | Meervoudige TIFF‑, TIF‑document uit een bestand of uit een InputStream. |
| [URL](#URL) | Link naar de afbeelding. |
| [Zip](#Zip) | Volledige naam van het ZIP‑archief. |

### Base64 {#Base64}
```
public static final InputType Base64
```


base64‑string met de afbeelding of pad naar het .txt‑bestand met de base64‑inhoud. Ondersteunt GIF, PNG, JPEG, BMP, TIFF.

### Directory {#Directory}
```
public static final InputType Directory
```


Pad naar de map. Geneste archieven en mappen worden niet ondersteund. Ondersteunt GIF, PNG, JPEG, BMP, TIFF. Standaard is het aantal verwerkte afbeeldingen alles.

### PDF {#PDF}
```
public static final InputType PDF
```


Gescanst PDF‑document uit een bestand of uit een InputStream.

### SingleImage {#SingleImage}
```
public static final InputType SingleImage
```


Ondersteunt GIF, PNG, JPEG, BMP, TIFF, JFIF, InputStream, BufferedImage.

### TIFF {#TIFF}
```
public static final InputType TIFF
```


Meervoudige TIFF‑, TIF‑document uit een bestand of uit een InputStream.

### URL {#URL}
```
public static final InputType URL
```


Link naar de afbeelding. Ondersteunt GIF, PNG, JPEG, BMP, TIFF.

### Zip {#Zip}
```
public static final InputType Zip
```


Volledige naam van het ZIP‑archief. Geneste archieven en mappen worden niet ondersteund. Ondersteunt GIF, PNG, JPEG, BMP, TIFF, JFIF. Standaard is het aantal verwerkte afbeeldingen alles.
