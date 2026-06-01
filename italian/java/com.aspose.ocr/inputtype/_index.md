---
title: "InputType"
second_title: "Riferimento API di Aspose.OCR per Java"
description: "Tipi di immagini/documenti per l'elaborazione/riconoscimento"
type: docs
weight: 38
url: /it/java/com.aspose.ocr/inputtype/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum InputType extends Enum<InputType>
```

Tipi di immagini/documenti per l'elaborazione/riconoscimento.
## Campi

| Campo | Descrizione |
| --- | --- |
| [Base64](#Base64) | Stringa base64 con l'immagine o percorso al file .txt con il contenuto base64. |
| [Directory](#Directory) | Percorso della directory. |
| [PDF](#PDF) | Documento PDF scansionato da file o da InputStream. |
| [SingleImage](#SingleImage) | Supporta GIF, PNG, JPEG, BMP, TIFF, JFIF, InputStream, BufferedImage. |
| [TIFF](#TIFF) | Documento TIFF multipagina, TIF da file o da InputStream. |
| [URL](#URL) | Collegamento all'immagine. |
| [Zip](#Zip) | Nome completo dell'archivio ZIP. |

### Base64 {#Base64}
```
public static final InputType Base64
```


Stringa base64 con l'immagine o percorso al file .txt con il contenuto base64. Supporta GIF, PNG, JPEG, BMP, TIFF.

### Directory {#Directory}
```
public static final InputType Directory
```


Percorso della directory. Gli archivi e le cartelle nidificate non sono supportati. Supporta GIF, PNG, JPEG, BMP, TIFF. La quantità predefinita di immagini elaborate è tutte.

### PDF {#PDF}
```
public static final InputType PDF
```


Documento PDF scansionato da file o da InputStream.

### SingleImage {#SingleImage}
```
public static final InputType SingleImage
```


Supporta GIF, PNG, JPEG, BMP, TIFF, JFIF, InputStream, BufferedImage.

### TIFF {#TIFF}
```
public static final InputType TIFF
```


Documento TIFF multipagina, TIF da file o da InputStream.

### URL {#URL}
```
public static final InputType URL
```


Collegamento all'immagine. Supporta GIF, PNG, JPEG, BMP, TIFF.

### Zip {#Zip}
```
public static final InputType Zip
```


Nome completo dell'archivio ZIP. Gli archivi e le cartelle nidificate non sono supportati. Supporta GIF, PNG, JPEG, BMP, TIFF, JFIF. La quantità predefinita di immagini elaborate è tutte.
