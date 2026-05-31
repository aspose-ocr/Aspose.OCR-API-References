---
title: "InputType"
second_title: "Aspose.OCR für Java API-Referenz"
description: "Typen von Bild-/Dokumenten für die Verarbeitung / Erkennung"
type: docs
weight: 38
url: /de/java/com.aspose.ocr/inputtype/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum InputType extends Enum<InputType>
```

Typen von Bild-/Dokumenten für Verarbeitung/Erkennung.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Base64](#Base64) | Base64-Zeichenkette mit dem Bild oder Pfad zur .txt-Datei mit dem Base64-Inhalt. |
| [Directory](#Directory) | Pfad zum Verzeichnis. |
| [PDF](#PDF) | Gescanntes PDF-Dokument aus einer Datei oder aus einem InputStream. |
| [SingleImage](#SingleImage) | Unterstützt GIF, PNG, JPEG, BMP, TIFF, JFIF, InputStream, BufferedImage. |
| [TIFF](#TIFF) | Mehrseitiges TIFF-, TIF-Dokument aus einer Datei oder aus einem InputStream. |
| [URL](#URL) | Link zum Bild. |
| [Zip](#Zip) | Vollständiger Name des ZIP-Archivs. |

### Base64 {#Base64}
```
public static final InputType Base64
```


Base64-Zeichenkette mit dem Bild oder Pfad zur .txt-Datei mit dem Base64-Inhalt. Unterstützt GIF, PNG, JPEG, BMP, TIFF.

### Directory {#Directory}
```
public static final InputType Directory
```


Pfad zum Verzeichnis. Verschachtelte Archive und Ordner werden nicht unterstützt. Unterstützt GIF, PNG, JPEG, BMP, TIFF. Standardmäßige Anzahl der verarbeiteten Bilder ist alle.

### PDF {#PDF}
```
public static final InputType PDF
```


Gescanntes PDF-Dokument aus einer Datei oder aus einem InputStream.

### SingleImage {#SingleImage}
```
public static final InputType SingleImage
```


Unterstützt GIF, PNG, JPEG, BMP, TIFF, JFIF, InputStream, BufferedImage.

### TIFF {#TIFF}
```
public static final InputType TIFF
```


Mehrseitiges TIFF-, TIF-Dokument aus einer Datei oder aus einem InputStream.

### URL {#URL}
```
public static final InputType URL
```


Link zum Bild. Unterstützt GIF, PNG, JPEG, BMP, TIFF.

### Zip {#Zip}
```
public static final InputType Zip
```


Vollständiger Name des ZIP-Archivs. Verschachtelte Archive und Ordner werden nicht unterstützt. Unterstützt GIF, PNG, JPEG, BMP, TIFF, JFIF. Standardmäßige Anzahl der verarbeiteten Bilder ist alle.
