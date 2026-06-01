---
title: "LanguageDetectionOutput"
second_title: "Referensi API Aspose.OCR untuk Java"
description: "Bahasa yang terdeteksi dalam teks gambar"
type: docs
weight: 14
url: /id/java/com.aspose.ocr.models/languagedetectionoutput/
---

**Inheritance:**
java.lang.Object
```
public class LanguageDetectionOutput
```

Bahasa yang terdeteksi dalam teks gambar.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page)](#LanguageDetectionOutput-java.lang.String-java.util.List-java.util.Map.Entry-com.aspose.ocr.models.Language-java.lang.Float---int) |  |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [languages](#languages) | Daftar bahasa yang terdeteksi dalam teks gambar, diurutkan berdasarkan kemungkinan. |
| [page](#page) | Nomor halaman. |
| [source](#source) | Jalur lengkap ke file atau URL, jika ada. |

### LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page) {#LanguageDetectionOutput-java.lang.String-java.util.List-java.util.Map.Entry-com.aspose.ocr.models.Language-java.lang.Float---int}
```
public LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page)
```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| _source | java.lang.String |  |
| _languages | java.util.List<java.util.Map.Entry<com.aspose.ocr.models.Language,java.lang.Float>> |  |
| _page | int |  |

### languages {#languages}
```
public List<Map.Entry<Language,Float>> languages
```


Daftar bahasa yang terdeteksi dalam teks gambar, diurutkan berdasarkan kemungkinan.

### page {#page}
```
public int page
```


Nomor halaman.

### source {#source}
```
public String source
```


Jalur lengkap ke file atau URL, jika ada. Kosong untuk aliran, array byte, base64.

