---
title: "ReceiptRecognitionSettings"
second_title: "Referensi API Aspose.OCR untuk Java"
description: "Pengaturan untuk pengenalan kwitansi berisi elemen yang memungkinkan penyesuaian proses pengenalan."
type: docs
weight: 25
url: /id/java/com.aspose.ocr/receiptrecognitionsettings/
---

**Inheritance:**
java.lang.Object
```
public class ReceiptRecognitionSettings
```

Pengaturan untuk pengenalan kwitansi berisi elemen yang memungkinkan penyesuaian proses pengenalan.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ReceiptRecognitionSettings()](#ReceiptRecognitionSettings) | Konstruktor default: set autoSkew true. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType) | Set karakter yang diizinkan. |
| [setAllowedCharacters(String allowedCharacters)](#setAllowedCharacters-java.lang.String) | Set karakter yang diizinkan. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | Mendeteksi gambar dengan teks putih pada latar belakang gelap/hitam dan secara otomatis memilih algoritma OCR khusus untuk mereka. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | Mengatur daftar hitam untuk simbol pengenalan. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.models.Language) |  |
| [setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)](#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel) | Menentukan tingkat deteksi bahasa untuk pengenalan teks. |
| [setThreadsCount(int threadsCount)](#setThreadsCount-int) | Mendapatkan atau mengatur jumlah thread untuk pemrosesan. |
| [setUpscaleSmallFont(boolean upscaleSmallFont)](#setUpscaleSmallFont-boolean) | Memungkinkan Anda menggunakan algoritma tambahan khusus untuk pengenalan font kecil. |
### ReceiptRecognitionSettings() {#ReceiptRecognitionSettings}
```
public ReceiptRecognitionSettings()
```


Konstruktor default: set autoSkew true.



### setAllowedCharacters(CharactersAllowedType allowedCharacters) {#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType}
```
public void setAllowedCharacters(CharactersAllowedType allowedCharacters)
```


Set karakter yang diizinkan. Menentukan jenis karakter yang diizinkan untuk hasil pengenalan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| allowedCharacters | [CharactersAllowedType](../../com.aspose.ocr.models/charactersallowedtype/) | berisi nilai enum @see [CharactersAllowedType](../../com.aspose.ocr.models/charactersallowedtype/). |

### setAllowedCharacters(String allowedCharacters) {#setAllowedCharacters-java.lang.String}
```
public void setAllowedCharacters(String allowedCharacters)
```


Set karakter yang diizinkan. Menentukan array karakter yang diizinkan untuk hasil pengenalan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| allowedCharacters | java.lang.String | berisi array karakter. |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


Mendeteksi gambar dengan teks putih pada latar belakang gelap/hitam dan secara otomatis memilih algoritma OCR khusus untuk mereka.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| automaticColorInversion | boolean | berisi nilai boolean - sebuah automaticColorInversion diatur. |

### setIgnoredCharacters(String characters) {#setIgnoredCharacters-java.lang.String}
```
public void setIgnoredCharacters(String characters)
```


Mengatur daftar hitam untuk simbol pengenalan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| characters | java.lang.String | Karakter yang dikecualikan dari pengenalan. |

### setLanguage(Language language) {#setLanguage-com.aspose.ocr.models.Language}
```
public void setLanguage(Language language)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| language | [Language](../../com.aspose.ocr.models/language/) | Mengatur bahasa yang digunakan untuk OCR. Multi-bahasa (none) secara default. |

### setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel) {#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel}
```
public void setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)
```


Menentukan tingkat deteksi bahasa untuk pengenalan teks. Hanya berfungsi jika bahasa yang dipilih adalah Language.MULTILANGUAGE, Language.AUTO, atau Language.UNIVERSAL. Proses ini memakan waktu dan secara signifikan memperlambat pengenalan secara keseluruhan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| languageDetectionLevel | [LanguageDetectionLevel](../../com.aspose.ocr.models/languagedetectionlevel/) | nilai enum untuk mengatur tingkat (Paragraph, Word, Page). |

### setThreadsCount(int threadsCount) {#setThreadsCount-int}
```
public void setThreadsCount(int threadsCount)
```


Mendapatkan atau mengatur jumlah thread untuk pemrosesan. Secara default, 0 berarti gambar akan diproses dengan jumlah thread yang sama dengan jumlah prosesor Anda. ThreadsCount = 1 berarti gambar akan diproses di thread utama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threadsCount | int | jumlah thread yang akan dibuat untuk pengenalan paralel fragmen gambar. |

### setUpscaleSmallFont(boolean upscaleSmallFont) {#setUpscaleSmallFont-boolean}
```
public void setUpscaleSmallFont(boolean upscaleSmallFont)
```


Memungkinkan Anda menggunakan algoritma tambahan khusus untuk pengenalan font kecil. Berguna untuk gambar dengan karakter berukuran kecil.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| upscaleSmallFont | boolean | berisi nilai boolean - sebuah upscaleSmallFont diatur. |