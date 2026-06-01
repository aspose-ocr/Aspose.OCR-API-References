---
title: "CarPlateRecognitionSettings"
second_title: "Referensi API Aspose.OCR untuk Java"
description: "Pengaturan untuk pengenalan nomor mobil berisi elemen yang memungkinkan penyesuaian proses pengenalan."
type: docs
weight: 12
url: /id/java/com.aspose.ocr/carplaterecognitionsettings/
---

**Inheritance:**
java.lang.Object
```
public class CarPlateRecognitionSettings
```

Pengaturan untuk pengenalan nomor mobil berisi elemen yang memungkinkan penyesuaian proses pengenalan.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [CarPlateRecognitionSettings()](#CarPlateRecognitionSettings) | Konstruktor default: set autoSkew true. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.CharactersAllowedType) | Set karakter yang diizinkan. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | Mendeteksi gambar dengan teks putih pada latar belakang gelap/hitam dan secara otomatis memilih algoritma OCR khusus untuk mereka. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | Mengatur daftar hitam untuk simbol pengenalan. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.Language) |  |
### CarPlateRecognitionSettings() {#CarPlateRecognitionSettings}
```
public CarPlateRecognitionSettings()
```


Konstruktor default: set autoSkew true.





### setAllowedCharacters(CharactersAllowedType allowedCharacters) {#setAllowedCharacters-com.aspose.ocr.CharactersAllowedType}
```
public void setAllowedCharacters(CharactersAllowedType allowedCharacters)
```


Set karakter yang diizinkan. Menentukan jenis karakter yang diizinkan untuk hasil pengenalan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| allowedCharacters | [CharactersAllowedType](../../com.aspose.ocr/charactersallowedtype/) | berisi nilai enum @see [CharactersAllowedType](../../com.aspose.ocr/charactersallowedtype/). |

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

### setLanguage(Language language) {#setLanguage-com.aspose.ocr.Language}
```
public void setLanguage(Language language)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| language | [Language](../../com.aspose.ocr/language/) | Mengatur bahasa yang digunakan untuk OCR. Multi-bahasa (none) secara default. |

