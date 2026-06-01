---
title: "DefectOutput"
second_title: "Referensi API Aspose.OCR untuk Java"
description: "Area yang berisi cacat yang diidentifikasi dalam gambar"
type: docs
weight: 16
url: /id/java/com.aspose.ocr/defectoutput/
---

**Inheritance:**
java.lang.Object
```
public class DefectOutput
```

Area yang berisi cacat yang teridentifikasi dalam gambar.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [Page](#Page) | Nomor halaman. |
| [Source](#Source) | Jalur lengkap ke file atau URL, jika ada. |
| [defectAreas](#defectAreas) | Daftar cacat gambar dan area tempat mereka ditemukan. |


### Page {#Page}
```
public int Page
```


Nomor halaman.

### Source {#Source}
```
public String Source
```


Jalur lengkap ke file atau URL, jika ada. Kosong untuk aliran, array byte, dan file yang dienkode Base64.

### defectAreas {#defectAreas}
```
public ArrayList<DefectAreas> defectAreas
```


Daftar cacat gambar dan area tempat mereka ditemukan.
