---
title: "Lisensi"
second_title: "Referensi API Aspose.OCR untuk Java"
description: "Menyediakan metode untuk melisensikan komponen"
type: docs
weight: 21
url: /id/java/com.aspose.ocr/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

Menyediakan metode untuk melisensikan komponen.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [License()](#License) | Menginisialisasi instance baru dari kelas ini. |
## Metode

| Metode | Deskripsi |
| --- | --- |

| [setLicense(File licenseFile)](#setLicense-java.io.File) | Melisensikan komponen. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream) | Melisensikan komponen. |
| [setLicense(String licenseFilePath)](#setLicense-java.lang.String) | Melisensikan komponen. |
| [isValid()](#isValid--) | Periksa lisensi. |
### License() {#License}
```
public License()
```


Menginisialisasi instance baru dari kelas ini.


### setLicense(File licenseFile) {#setLicense-java.io.File}
```
public static void setLicense(File licenseFile)
```


Melisensikan komponen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| licenseFile | java.io.File | representasi jalur nama file |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream}
```
public static void setLicense(InputStream stream)
```


Melisensikan komponen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran yang berisi lisensi. |

### setLicense(String licenseFilePath) {#setLicense-java.lang.String}
```
public static void setLicense(String licenseFilePath)
```


Melisensikan komponen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| licenseFilePath | java.lang.String | Dapat berupa nama file lengkap atau pendek. Gunakan string kosong untuk beralih ke mode evaluasi. |



### isValid() {#isValid--}
```
public static boolean isValid()
```


Periksa lisensi.

**Returns:**
boolean - Nilai Boolean apakah lisensi valid.
