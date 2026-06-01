---
title: "Sumber daya"
second_title: "Referensi API Aspose.OCR untuk Java"
description: "Kelola sumber daya yang dapat diunduh yang meningkatkan kemampuan pengenalan Aspose.OCR"
type: docs
weight: 32
url: /id/java/com.aspose.ocr/resources/
---

**Inheritance:**
java.lang.Object
```
public class Resources
```

Kelola sumber daya yang dapat diunduh yang meningkatkan kemampuan pengenalan Aspose.OCR.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Resources()](#Resources) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [AllowAutomaticDownloads(Boolean allow)](#AllowAutomaticDownloads-java.lang.Boolean) | Izinkan (true) atau blokir (false) pengunduhan otomatis sumber daya yang diperlukan dari repositori online. |
| [FetchAll()](#FetchAll) | Unduh semua sumber daya yang kompatibel dari repositori online. |
| [FetchResource(String name)](#FetchResource-java.lang.String) | Unduh sumber daya yang ditentukan dalam parameter name dari repositori daring. |
| [FetchResources(String[] names)](#FetchResources-java.lang.String) | Unduh sumber daya yang ditentukan dalam parameter names dari repositori daring. |
| [GetLocalPath()](#GetLocalPath) | Kembalikan jalur lengkap ke direktori tempat sumber daya akan diunduh. |
| [GetRepository()](#GetRepository) | Kembalikan URL repositori daring dari mana sumber daya Aspose.OCR diunduh. |
| [ListLocal()](#ListLocal) | Daftar semua sumber daya Aspose.OCR yang disimpan di direktori lokal. |
| [ListRemote()](#ListRemote) | Daftar semua sumber daya yang kompatibel dari repositori daring. |
| [ReleaseMemory()](#ReleaseMemory) | Bongkar modul OCR untuk membebaskan memori. |
| [RemoveLocal(String name)](#RemoveLocal-java.lang.String) | Menghapus sumber daya Aspose.OCR yang disimpan secara lokal. |
| [SetLocalPath(String path)](#SetLocalPath-java.lang.String) | Tentukan jalur absolut atau relatif ke direktori tempat sumber daya akan diunduh. |
| [SetLocalPath(String path, Boolean create)](#SetLocalPath-java.lang.String-java.lang.Boolean) | Tentukan jalur absolut atau relatif ke direktori tempat sumber daya akan diunduh. |
| [SetRepository(String url)](#SetRepository-java.lang.String) | Tentukan URL repositori daring dari mana sumber daya Aspose.OCR akan diunduh. |

### Resources() {#Resources}
```
public Resources()
```


### AllowAutomaticDownloads(Boolean allow) {#AllowAutomaticDownloads-java.lang.Boolean}
```
public static void AllowAutomaticDownloads(Boolean allow)
```


Izinkan (true) atau blokir (false) pengunduhan otomatis sumber daya yang diperlukan dari repositori daring. Secara default, sumber daya akan diunduh secara otomatis ketika metode yang bergantung padanya dipanggil.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| izinkan | java.lang.Boolean | Nilai Boolean untuk mengizinkan atau memblokir pengunduhan otomatis sumber daya yang diperlukan. |

### FetchAll() {#FetchAll}
```
public static void FetchAll()
```


Unduh semua sumber daya yang kompatibel dari repositori daring. File sumber daya yang ada akan ditimpa.

### FetchResource(String name) {#FetchResource-java.lang.String}
```
public static void FetchResource(String name)
```


Unduh sumber daya yang ditentukan dalam parameter name dari repositori daring. Jika sumber daya sudah diunduh, akan ditimpa. Anda dapat menghilangkan ekstensi .OCR dan hanya menggunakan nama file.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | String dengan nama sumber daya. Lihat metode ListRemote. |

### FetchResources(String[] names) {#FetchResources-java.lang.String}
```
public static void FetchResources(String[] names)
```


Unduh sumber daya yang ditentukan dalam parameter names dari repositori daring. Jika satu atau lebih sumber daya sudah diunduh, mereka akan ditimpa. Anda dapat menghilangkan ekstensi .OCR dan hanya menggunakan nama file.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| names | java.lang.String[] | Array dengan nama-nama sumber daya. Lihat metode ListRemote. |

### GetLocalPath() {#GetLocalPath}
```
public static String GetLocalPath()
```


Kembalikan jalur lengkap ke direktori tempat sumber daya akan diunduh.

**Returns:**
java.lang.String - String dengan jalur ke direktori sumber daya.
### GetRepository() {#GetRepository}
```
public static String GetRepository()
```


Kembalikan URL repositori daring dari mana sumber daya Aspose.OCR diunduh.

**Returns:**
java.lang.String - URL repositori daring.
### ListLocal() {#ListLocal}
```
public static List<String> ListLocal()
```


Daftar semua sumber daya Aspose.OCR yang disimpan di direktori lokal.

**Returns:**
java.util.List<java.lang.String> - Daftar semua sumber daya Aspose.OCR yang disimpan di direktori lokal.
### ListRemote() {#ListRemote}
```
public static List<String> ListRemote()
```


Daftar semua sumber daya yang kompatibel dari repositori daring.

**Returns:**
java.util.List<java.lang.String> - Daftar nama sumber daya.
### ReleaseMemory() {#ReleaseMemory}
```
public static void ReleaseMemory()
```


Melepas modul OCR untuk membebaskan memori. File modul yang diunduh akan tetap utuh.

### RemoveLocal(String name) {#RemoveLocal-java.lang.String}
```
public static void RemoveLocal(String name)
```


Menghapus sumber daya Aspose.OCR yang disimpan secara lokal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String |  |

### SetLocalPath(String path) {#SetLocalPath-java.lang.String}
```
public static void SetLocalPath(String path)
```


Tentukan jalur absolut atau relatif ke direktori tempat sumber daya akan diunduh. Jika direktori tidak ada, maka akan dibuat secara otomatis. Secara default, sumber daya diunduh ke direktori aspose\_data di direktori kerja aplikasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| jalur | java.lang.String | Jalur absolut atau relatif ke direktori. |

### SetLocalPath(String path, Boolean create) {#SetLocalPath-java.lang.String-java.lang.Boolean}
```
public static void SetLocalPath(String path, Boolean create)
```


Tentukan jalur absolut atau relatif ke direktori tempat sumber daya akan diunduh. Berikan nilai false pada parameter create untuk mencegah direktori dibuat secara otomatis. Jika direktori yang diberikan tidak ada dan pembuatan tidak diizinkan, sumber daya akan dimuat ke direktori aspose\_data di direktori kerja aplikasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| jalur | java.lang.String | Jalur absolut atau relatif ke direktori. |
| create | java.lang.Boolean | Parameter untuk mencegah direktori dibuat secara otomatis. |

### SetRepository(String url) {#SetRepository-java.lang.String}
```
public static void SetRepository(String url)
```


Tentukan URL repositori online tempat sumber daya Aspose.OCR akan diunduh. Secara default, sumber daya diunduh dari https://github.com/aspose-ocr/resources/.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | java.lang.String | URL repositori online. |


