---
title: "DefectType"
second_title: "Referensi API Aspose.OCR untuk Java"
description: "Jenis-jenis cacat gambar"
type: docs
weight: 22
url: /id/java/com.aspose.ocr.models/defecttype/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DefectType extends Enum<DefectType>
```

Jenis-jenis cacat gambar.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [ALL](#ALL) | Semua cacat gambar yang didukung. |
| [BLUR](#BLUR) | Gambar tidak fokus. |
| [GLARE](#GLARE) | Area dalam gambar yang disebabkan oleh pencahayaan tidak merata, seperti lampu sorot atau kilat. |
| [LOW_CONTRAST](#LOW-CONTRAST) | Sorotan dan bayangan yang biasanya muncul pada halaman melengkung. |
| [SALT_PEPPER_NOISE](#SALT-PEPPER-NOISE) | Piksel putih dan hitam acak tersebar di seluruh area. |

### ALL {#ALL}
```
public static final DefectType ALL
```


Semua cacat gambar yang didukung.

### BLUR {#BLUR}
```
public static final DefectType BLUR
```


Gambar tidak fokus. Algoritma deteksi ini hanya dapat mengidentifikasi seluruh gambar sebagai buram. Area spesifik tidak dapat dideteksi.

### GLARE {#GLARE}
```
public static final DefectType GLARE
```


Area dalam gambar yang disebabkan oleh pencahayaan tidak merata, seperti lampu sorot atau kilat.

### LOW_CONTRAST {#LOW-CONTRAST}
```
public static final DefectType LOW_CONTRAST
```


Sorotan dan bayangan yang biasanya muncul pada halaman melengkung.

### SALT_PEPPER_NOISE {#SALT-PEPPER-NOISE}
```
public static final DefectType SALT_PEPPER_NOISE
```


Piksel putih dan hitam acak tersebar di seluruh area. Sering terjadi pada foto digital.

