---
title: "DetectAreasMode"
second_title: "Referensi API Aspose.OCR untuk Java"
description: 
type: docs
weight: 28
url: /id/java/com.aspose.ocr.models/detectareasmode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DetectAreasMode extends Enum<DetectAreasMode>
```
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [CURVED_TEXT](#CURVED-TEXT) | Secara otomatis meluruskan garis teks melengkung dalam gambar, meningkatkan akurasi pengenalan dan memungkinkan lebih banyak teks dipulihkan serta diekstrak. |
| [FORMULA](#FORMULA) | Mendeteksi semua blok dengan rumus matematika. |
| [LEAN](#LEAN) | Memprioritaskan kecepatan dan mengurangi konsumsi sumber daya dengan menghilangkan dukungan untuk tata letak kompleks. |
| [MULTICOLUMN](#MULTICOLUMN) | Mendeteksi blok teks besar yang diformat dalam kolom. |
| [TABLE](#TABLE) | Mendeteksi struktur tabel dalam gambar dan mengekstrak teks dari sel individual. |
| [UNIVERSAL](#UNIVERSAL) | Mendeteksi semua blok teks dalam gambar, termasuk teks yang jarang dan tidak teratur pada foto. |

### CURVED_TEXT {#CURVED-TEXT}
```
public static final DetectAreasMode CURVED_TEXT
```


Secara otomatis meluruskan garis teks melengkung dalam gambar, meningkatkan akurasi pengenalan dan memungkinkan lebih banyak teks dipulihkan serta diekstrak. Membutuhkan daya pemrosesan dan RAM yang signifikan.

### FORMULA {#FORMULA}
```
public static final DetectAreasMode FORMULA
```


Mendeteksi semua blok dengan rumus matematika.

### LEAN {#LEAN}
```
public static final DetectAreasMode LEAN
```


Memprioritaskan kecepatan dan mengurangi konsumsi sumber daya dengan menghilangkan dukungan untuk tata letak kompleks. Hanya cocok untuk gambar sederhana dengan beberapa baris teks tanpa ilustrasi atau format.

### MULTICOLUMN {#MULTICOLUMN}
```
public static final DetectAreasMode MULTICOLUMN
```


Mendeteksi blok teks besar yang diformat dalam kolom. Pilihan terbaik untuk tata letak multi-kolom seperti halaman buku, artikel, atau kontrak.

### TABLE {#TABLE}
```
public static final DetectAreasMode TABLE
```


Mendeteksi struktur tabel dalam gambar dan mengekstrak teks dari sel individual. Direkomendasikan untuk spreadsheet yang dipindai, laporan, dan dokumen berbasis tabel lainnya.

### UNIVERSAL {#UNIVERSAL}
```
public static final DetectAreasMode UNIVERSAL
```


Mendeteksi semua blok teks dalam gambar, termasuk teks yang jarang dan tidak teratur pada foto. Pilihan serbaguna untuk kebanyakan gambar, kecuali tabel dan tata letak multi-kolom.

