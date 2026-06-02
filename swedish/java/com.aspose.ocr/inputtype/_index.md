---
title: "InputType"
second_title: "Aspose.OCR för Java API-referens"
description: "Typer av bild/dokument för bearbetning/igenkänning"
type: docs
weight: 38
url: /sv/java/com.aspose.ocr/inputtype/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum InputType extends Enum<InputType>
```

Typer av bilder/dokument för bearbetning/igenkänning.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Base64](#Base64) | base64-sträng med bilden eller sökväg till .txt-filen med base64-innehållet. |
| [Directory](#Directory) | Sökväg till katalogen. |
| [PDF](#PDF) | Skannad PDF-dokument från fil eller från InputStream. |
| [SingleImage](#SingleImage) | Stöder GIF, PNG, JPEG, BMP, TIFF, JFIF, InputStream, BufferedImage. |
| [TIFF](#TIFF) | Fler-sidig TIFF-, TIF-dokument från fil eller från InputStream. |
| [URL](#URL) | Länk till bilden. |
| [Zip](#Zip) | Fullständigt namn på ZIP-arkivet. |

### Base64 {#Base64}
```
public static final InputType Base64
```


base64-sträng med bilden eller sökväg till .txt-filen med base64-innehållet. Stöder GIF, PNG, JPEG, BMP, TIFF.

### Directory {#Directory}
```
public static final InputType Directory
```


Sökväg till katalogen. Inbäddade arkiv och mappar stöds inte. Stöder GIF, PNG, JPEG, BMP, TIFF. Standardantalet bearbetade bilder är alla.

### PDF {#PDF}
```
public static final InputType PDF
```


Skannad PDF-dokument från fil eller från InputStream.

### SingleImage {#SingleImage}
```
public static final InputType SingleImage
```


Stöder GIF, PNG, JPEG, BMP, TIFF, JFIF, InputStream, BufferedImage.

### TIFF {#TIFF}
```
public static final InputType TIFF
```


Fler-sidig TIFF-, TIF-dokument från fil eller från InputStream.

### URL {#URL}
```
public static final InputType URL
```


Länk till bilden. Stöder GIF, PNG, JPEG, BMP, TIFF.

### Zip {#Zip}
```
public static final InputType Zip
```


Fullständigt namn på ZIP-arkivet. Inbäddade arkiv och mappar stöds inte. Stöder GIF, PNG, JPEG, BMP, TIFF, JFIF. Standardantalet bearbetade bilder är alla.
