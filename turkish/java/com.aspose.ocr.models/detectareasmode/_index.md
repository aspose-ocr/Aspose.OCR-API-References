---
title: "DetectAreasMode"
second_title: "Aspose.OCR for Java API Referansı"
description: 
type: docs
weight: 28
url: /tr/java/com.aspose.ocr.models/detectareasmode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DetectAreasMode extends Enum<DetectAreasMode>
```
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [CURVED_TEXT](#CURVED-TEXT) | Görüntüdeki eğri metin satırlarını otomatik olarak düzleştirir, tanıma doğruluğunu artırır ve daha fazla metnin geri kazanılmasını ve çıkarılmasını sağlar. |
| [FORMULA](#FORMULA) | Matematiksel formüller içeren tüm blokları algılar. |
| [LEAN](#LEAN) | Hızı önceliklendirir ve karmaşık düzen desteğini atlayarak kaynak tüketimini azaltır. |
| [MULTICOLUMN](#MULTICOLUMN) | Sütunlarda biçimlendirilmiş büyük metin bloklarını algılar. |
| [TABLE](#TABLE) | Görüntüdeki tablo yapısını algılar ve bireysel hücrelerden metni çıkarır. |
| [UNIVERSAL](#UNIVERSAL) | Görüntüdeki tüm metin bloklarını, fotoğraflardaki seyrek ve düzensiz metinler dahil, algılar. |

### CURVED_TEXT {#CURVED-TEXT}
```
public static final DetectAreasMode CURVED_TEXT
```


Görüntüdeki eğri metin satırlarını otomatik olarak düzleştirir, tanıma doğruluğunu artırır ve daha fazla metnin geri kazanılmasını ve çıkarılmasını sağlar. Önemli işlem gücü ve RAM gerektirir.

### FORMULA {#FORMULA}
```
public static final DetectAreasMode FORMULA
```


Matematiksel formüller içeren tüm blokları algılar.

### LEAN {#LEAN}
```
public static final DetectAreasMode LEAN
```


Hızı önceliklendirir ve karmaşık düzen desteğini atlayarak kaynak tüketimini azaltır. Sadece illüstrasyon veya biçimlendirme içermeyen birkaç satır metin bulunan basit görüntüler için uygundur.

### MULTICOLUMN {#MULTICOLUMN}
```
public static final DetectAreasMode MULTICOLUMN
```


Sütunlarda biçimlendirilmiş büyük metin bloklarını algılar. Kitap sayfaları, makaleler veya sözleşmeler gibi çok sütunlu düzenler için en iyi seçim.

### TABLE {#TABLE}
```
public static final DetectAreasMode TABLE
```


Görüntüdeki tablo yapısını algılar ve bireysel hücrelerden metni çıkarır. Tarama yoluyla elde edilen elektronik tablolar, raporlar ve diğer tablo tabanlı belgeler için önerilir.

### UNIVERSAL {#UNIVERSAL}
```
public static final DetectAreasMode UNIVERSAL
```


Görüntüdeki tüm metin bloklarını, fotoğraflardaki seyrek ve düzensiz metinler dahil, algılar. Tablolar ve çok sütunlu düzenler dışındaki çoğu görüntü için çok yönlü bir seçenektir.

