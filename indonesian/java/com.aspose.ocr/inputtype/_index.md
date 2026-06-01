---
title: "InputType"
second_title: "Referensi API Aspose.OCR untuk Java"
description: "Jenis gambar/dokumen untuk pemrosesan/pengenalan"
type: docs
weight: 38
url: /id/java/com.aspose.ocr/inputtype/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum InputType extends Enum<InputType>
```

Jenis gambar/dokumen untuk pemrosesan / pengenalan.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [Base64](#Base64) | string base64 dengan gambar atau jalur ke file .txt yang berisi konten base64. |
| [Directory](#Directory) | Jalur ke direktori. |
| [PDF](#PDF) | Dokumen PDF yang dipindai dari file atau dari InputStream. |
| [SingleImage](#SingleImage) | Mendukung GIF, PNG, JPEG, BMP, TIFF, JFIF, InputStream, BufferedImage. |
| [TIFF](#TIFF) | Dokumen TIFF multipage, TIF dari file atau dari InputStream. |
| [URL](#URL) | Tautan pada gambar. |
| [Zip](#Zip) | Nama lengkap arsip ZIP. |

### Base64 {#Base64}
```
public static final InputType Base64
```


string base64 dengan gambar atau jalur ke file .txt yang berisi konten base64. Mendukung GIF, PNG, JPEG, BMP, TIFF.

### Directory {#Directory}
```
public static final InputType Directory
```


Jalur ke direktori. Arsip dan folder bersarang tidak didukung. Mendukung GIF, PNG, JPEG, BMP, TIFF. Jumlah gambar yang diproses secara default adalah semua.

### PDF {#PDF}
```
public static final InputType PDF
```


Dokumen PDF yang dipindai dari file atau dari InputStream.

### SingleImage {#SingleImage}
```
public static final InputType SingleImage
```


Mendukung GIF, PNG, JPEG, BMP, TIFF, JFIF, InputStream, BufferedImage.

### TIFF {#TIFF}
```
public static final InputType TIFF
```


Dokumen TIFF multipage, TIF dari file atau dari InputStream.

### URL {#URL}
```
public static final InputType URL
```


Tautan pada gambar. Mendukung GIF, PNG, JPEG, BMP, TIFF.

### Zip {#Zip}
```
public static final InputType Zip
```


Nama lengkap arsip ZIP. Arsip dan folder bersarang tidak didukung. Mendukung GIF, PNG, JPEG, BMP, TIFF, JFIF. Jumlah gambar yang diproses secara default adalah semua.
