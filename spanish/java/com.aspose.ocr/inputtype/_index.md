---
title: "InputType"
second_title: "Referencia de API de Aspose.OCR para Java"
description: "Tipos de imágenes/documentos para procesamiento/reconocimiento"
type: docs
weight: 38
url: /es/java/com.aspose.ocr/inputtype/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum InputType extends Enum<InputType>
```

Tipos de imágenes/documentos para procesamiento/reconocimiento.
## Campos

| Campo | Descripción |
| --- | --- |
| [Base64](#Base64) | cadena base64 con la imagen o ruta al archivo .txt con el contenido base64. |
| [Directory](#Directory) | Ruta al directorio. |
| [PDF](#PDF) | Documento PDF escaneado desde archivo o desde InputStream. |
| [SingleImage](#SingleImage) | Compatible con GIF, PNG, JPEG, BMP, TIFF, JFIF, InputStream, BufferedImage. |
| [TIFF](#TIFF) | Documento TIFF multipágina, TIF desde archivo o desde InputStream. |
| [URL](#URL) | Enlace a la imagen. |
| [Zip](#Zip) | Nombre completo del archivo ZIP. |

### Base64 {#Base64}
```
public static final InputType Base64
```


cadena base64 con la imagen o ruta al archivo .txt con el contenido base64. Compatible con GIF, PNG, JPEG, BMP, TIFF.

### Directory {#Directory}
```
public static final InputType Directory
```


Ruta al directorio. Los archivos y carpetas anidados no son compatibles. Compatible con GIF, PNG, JPEG, BMP, TIFF. La cantidad predeterminada de imágenes procesadas es todas.

### PDF {#PDF}
```
public static final InputType PDF
```


Documento PDF escaneado desde archivo o desde InputStream.

### SingleImage {#SingleImage}
```
public static final InputType SingleImage
```


Compatible con GIF, PNG, JPEG, BMP, TIFF, JFIF, InputStream, BufferedImage.

### TIFF {#TIFF}
```
public static final InputType TIFF
```


Documento TIFF multipágina, TIF desde archivo o desde InputStream.

### URL {#URL}
```
public static final InputType URL
```


Enlace a la imagen. Compatible con GIF, PNG, JPEG, BMP, TIFF.

### Zip {#Zip}
```
public static final InputType Zip
```


Nombre completo del archivo ZIP. Los archivos y carpetas anidados no son compatibles. Compatible con GIF, PNG, JPEG, BMP, TIFF, JFIF. La cantidad predeterminada de imágenes procesadas es todas.
